# Explorando_vulnerabilidades

**Resumo**
Realizei uma sessão de laboratório utilizando máquinas virtuais para fins de aprendizado e avaliação em um ambiente controlado. A seguir descrevo, as ferramentas e plataformas que utilizei durante os testes.

**Ferramentas e plataformas utilizadas**

* **Kali Linux (VM)** — plataforma atacante e ambiente de trabalho principal onde executei e coordenei as atividades de avaliação.
* **Metasploitable2 (VM)** — ambiente alvo intencionalmente vulnerável, utilizado como alvo de testes para avaliar comportamentos de serviços e respostas do sistema.
* Utilizei comandos no Medusa como o : (medusa -h (ip alvo) -u (arquivos com usuarios possiveis) -p ( arquivos com senhas possiveis) -M (tipo de "Serviço" utilizado) -t (quantidade de tentativas diretas) )
* por estar utilizando um alvo feito para ser explorado , em poucos minutos as senhas e usuarios foram descobertas.  
* **DVWA (Damn Vulnerable Web Application)** — aplicação web vulnerável utilizada como alvo para testes relacionados a serviços web.
* **Medusa** — ferramenta de força bruta paralela utilizada para automatizar tentativas de autenticação contra serviços identificados (ex.: FTP e HTTPS).
* **Cliente FTP/serviços de FTP no Metasploitable2** — serviço alvo para avaliação de autenticação.
* **Serviço HTTPS na DVWA / Metasploitable2** — serviço alvo para avaliação de autenticação e comportamento do serviço web.
* **Ferramentas de captura/monitoramento (ex.: Wireshark / tcpdump)** — utilizadas para registrar tráfego de rede e coletar evidências de execução
* **Registro de logs do sistema** — arquivos de log das VMs e serviços, usados para correlação de eventos e documentação dos achados.

**O<img width="767" height="262" alt="Captura de tela de 2025-10-04 11-54-53" src="https://github.com/user-attachments/assets/b0a31b30-9730-44b6-bca2-8512f3d9f1c4" />

bservações finais**

* Todos os testes foram conduzidos em um ambiente isolado e controlado, destinado ao aprendizado.
* O objetivo principal foi identificar comportamentos dos serviços, validar mecanismos de detecção e registrar evidências para posterior análise e propostas de mitigação.

