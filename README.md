# Urna CC6522

## PROJETO 1 - Modelagem de Sistemas Orientados a Objetos


Nome|RA:

Eric Song Watanabe|22.125.086-3

Paulo Andre O. Hirata|22.125.072-3

Victor Pimentel Lario|22.125.064-0

Victor Merker Binda|22.125.075-6




ATORES:  Eleitor, candidato, admnistrador

### CASOS DE USO:

- UC01: Cadastrar Candidato
- UC02: Cadastrar Eleitor
- UC03: Identificar Eleitor
- UC04: Validar eleitores
- UC05: Autenticar administrador
- UC06: Votar Candidato
- UC07: Gerar relatórios

| Identificação | UC01 - Cadastrar Candidato |
| :---: | :--- |
| Função | O candidato cadastra no sistema para fins de identificação, assim podendo receber votos dos eleitores. |
| Atores  | Candidato |
| Pré-condição | Dados válidos, dentro das normas |
| Pós-condição  | Cadastrado no sistema e apto para a autenticação |
| Fluxo principal  | 1. O candidato informa seus dados pessoais./ 2. O sistema valida as informações./ 3. O sistema cria cadastro ao cliente. |
| Fluxo Alternativo |  |
| Fluxo Exceção | 1. O candidato informa dados pessoais./ 2. O sistema confere as informações./ 3. O sistema invalida o cadastro (dados inválidos).

| Identificação | UC02 - Cadastrar eleitor |
| :---: | :--- |
| Função | O eleitor cadastra no sistema para estar apto a votação. |
| Atores  | Eleitor  |
| Pré-condição | Dados válidos, dentro das normas |
| Pós-condição  | Cadastrado no sistema e apto para a identificação |
| Fluxo principal  | 1. O eleitor informa dados pessoais./ 2. O sistema valida as informações./ 3.O sistema cadastra o eleitor. |
| Fluxo Alternativo |  |
| Fluxo Exceção | 1. O eleitor informa dados pessoais./ 2. O sistema confere as informações./ 3. O sistema invalida o cadastro (dados inválidos).

| Identificação | UC03 -  Identificar o eleitor |
| :---: | :--- |
| Função | O eleitor se identifica na urna para ser possível realizar a votação. |
| Atores  | Eleitor  |
| Pré-condição | O eleitor precisar estar cadastrado no sistema. |
| Pós-condição  | Validação da situação do eleitor |
| Fluxo principal  | 1. O eleitor informa dados pessoais./ 2. O sistema verifica se o eleitor está cadastrado./ 3. O sistema permite o funcionamento da urna ao eleitor. |
| Fluxo Alternativo |  |
| Fluxo Exceção | 1. O eleitor informa dados pessoais./ 2. O sistema confere as informações./ 3.O sistema não encontra o cadastro do eleitor e invalida seu acesso.

| Identificação | UC04 - Validar eleitores |
| :---: | :--- |
| Função | O sistema verifica se o eleitor já realizou seu voto. |
| Atores  | Eleitor, Administrador  |
| Pré-condição | Eleitor ter se identificado |
| Pós-condição  | Permissão do eleitor a votar. |
| Fluxo principal  | 1. O sistema verifica o histórico do eleitor./ 2. É apresentado que o eleitor não votou na eleição do turno presente./ 3. O sistema autoriza a votação ao eleitor. |
| Fluxo Alternativo |  |
| Fluxo Exceção | 1. O sistema verifica o histórico do eleitor./ 2. É apresentado que o eleitor votou na eleição do turno presente./ 3. O sistema não permite a opção de voto ao eleitor.

| Identificação | UC05 - Autenticar administrador |
| :---: | :--- |
| Função | O administrador se autententifica para poder acessar o sistema |
| Atores  | Administrador  |
| Pré-condição | Administrador possuir um login e senha válidos cadastrados no sistema. |
| Pós-condição  | Administrador recebe o acesso |
| Fluxo principal  | 1. Administrador acessa a página de login do sistema./ 2. Administrador informa suas credenciais e senha./ 3. O sistema valida as credenciais e concede o acesso ao sistema. |
| Fluxo Alternativo | 1. Administrador esquece a senha./ 2. Clica na opção “Esqueci minha senha”./ 3. O Sistema envia instruções de recuperação de senha por e-mail./ 4. O administrador acessa o sistema. |
| Fluxo Exceção | 1. Administrador informa login ou senha incorretos./ 2. Sistema exibe mensagem de erro./ 3. Após 3 tentativas falhas, o sistema bloqueia temporariamente o acesso.

| Identificação | UC06 - Votar Candidato |
| :---: | :--- |
| Função | O eleitor vota no candidato a sua escolha. |
| Atores  | Eleitor, Candidato  |
| Pré-condição | Eleitor estar válido |
| Pós-condição  | Voto registrado no sistema |
| Fluxo principal  | 1. Eleitor se dirige a urna./ 2. Eleitor vota no candidato a sua escolha./ 3. O sistema registra o voto. |
| Fluxo Alternativo |  |
| Fluxo Exceção | 1. Eleitor se dirige a urna./ 2. Eleitor vota em um número de candidato que não existe./ 3. O sistema não registra o voto e reinicia para o eleitor votar novamente.

| Identificação | UC07 - Gerar relatórios |
| :---: | :--- |
| Função | O administrador consegue gerar relatórios sobre os dados das urnas. |
| Atores  | Administrador  |
| Pré-condição | Administrador estar autenticado |
| Pós-condição  | Relatórios gerados |
| Fluxo principal  | 1. Administrador acessa a Urna Eletrônica de Gerenciamento./ 2. Administrador gera os relatórios por meio do sistema./ 3. Relatórios são gerados com os dados de votação das urnas. |
| Fluxo Alternativo |  |
| Fluxo Exceção | 1. Administrador acessa a  Urna Eletrônica de Gerenciamento./ 2. Administrador gera os relatórios por meio do sistema./ 3. Relatórios não são gerados por ainda não ter nenhum voto registrado.

<img width="455" height="599" alt="image" src="https://github.com/user-attachments/assets/da7a2079-882f-4776-a166-c689dfd64ec9" />
