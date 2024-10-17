# Cyber Kill Chain

O **Cyber Kill Chain** é um modelo desenvolvido pela Lockheed Martin que descreve as etapas de um ataque cibernético, desde o reconhecimento inicial até a exfiltração de dados ou compromissos finais. Ele ajuda a entender e detectar ameaças em suas fases iniciais e fornece uma estrutura para implementar medidas defensivas eficazes.

## Fases do Cyber Kill Chain

1. **Reconhecimento (Reconnaissance)**  
   O atacante coleta informações sobre o alvo, como endereços de IP, domínios e vulnerabilidades públicas, usando ferramentas de varredura, sites públicos ou engenharia social.

2. **Armazenamento (Weaponization)**  
   Após coletar informações, o invasor cria uma carga maliciosa (payload), geralmente combinando uma vulnerabilidade explorada com um malware ou backdoor, que será utilizado na próxima fase.

3. **Entrega (Delivery)**  
   O malware ou exploit é entregue ao alvo por meio de e-mails de phishing, downloads maliciosos, ou diretamente por meio de um vetor de ataque, como um documento infectado.

4. **Exploração (Exploitation)**  
   Nesta fase, o código malicioso é ativado no sistema do alvo, aproveitando vulnerabilidades de segurança, sejam elas conhecidas ou de dia zero (zero-day).

5. **Instalação (Installation)**  
   O atacante instala um backdoor ou um trojan no sistema da vítima, garantindo persistência para manter o acesso ao sistema comprometido.

6. **Comando e Controle (Command and Control - C2)**  
   O atacante estabelece um canal de comunicação com o sistema infectado, permitindo controlar remotamente o malware ou enviar novos comandos.

7. **Ações sobre o objetivo (Actions on Objectives)**  
   Finalmente, o atacante realiza as ações pretendidas, como roubar dados, exfiltrar informações sensíveis ou realizar movimentos laterais para comprometer outros sistemas da rede.

## Como Defender-se Usando o Cyber Kill Chain

Compreender o **Cyber Kill Chain** permite implementar defesas em múltiplas fases, prevenindo o avanço do ataque. Aqui estão algumas abordagens de defesa:

- **Reconhecimento:** Utilize monitoramento de tráfego de rede para identificar varreduras suspeitas e atividades incomuns.
- **Armazenamento e Entrega:** Implemente sistemas de detecção e prevenção de intrusão (IDS/IPS), antivírus e filtros de e-mail para bloquear cargas maliciosas.
- **Exploração:** Mantenha os sistemas atualizados e corrigidos para evitar que vulnerabilidades conhecidas sejam exploradas.
- **Instalação:** Use políticas de execução restritivas (como whitelisting) e monitoramento de integridade de arquivos para impedir a instalação de malware.
- **Comando e Controle:** Inspecione o tráfego de rede em busca de comunicações com servidores C2, utilizando firewalls e proxies para bloquear conexões maliciosas.
- **Ações sobre o objetivo:** Estabeleça monitoramento contínuo e resposta a incidentes para mitigar danos, caso a fase final seja atingida.

## Conclusão

O **Cyber Kill Chain** fornece uma estrutura clara para detectar e mitigar ataques cibernéticos em suas diversas fases. Ao implementar controles de segurança adequados em cada uma dessas etapas, é possível aumentar significativamente a proteção contra ataques sofisticados.

## Referências

- [Lockheed Martin Cyber Kill Chain](https://www.lockheedmartin.com/en-us/capabilities/cyber/cyber-kill-chain.html)
- [MITRE ATT&CK Framework](https://attack.mitre.org/)

