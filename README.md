# resumo-do-lab
Contém o resumo das lições aprendidas no lad azure

### Instancia banco de dados SQL
Configuramos uma instancia de banco de dados,
definindo as configuraçẽos necessárioas para seu uso.
DESC: Nome do banco de dados, assinatura, grupo de recuros, servidor,
plano de serviços(por consumo ou fixo mensal) e configuração de backup
defininado redundancia local ou geografica.

### Arquitetura azure
Conhecemos os conceitos e quais questionamentos a serem feitos para um bom planejamento.
Criação de grupo de recuros, criação de uma rede virtual, regras de segurança, com os grupos
de segurança, provisionamento de maquinas, balanceadores de carga, implementação de serviços
de banco de dados, monitoramenot de logs, backups e redundancia.

### Configuração de recurtos e dimensionamento de maquinas
Criar a maquina virtual, escolher o tamanho da vm, configurar o sitema operacional,
escolher a opção de armazenamento, configurar a rede, configurar o backup e recuperação.

Após a maquina funcionando monitorar o seu funcionamento, no painel da VM é possivel,
acessar as metricas de consumo.

### Armazenamento
- Blob Storage, o armazenamento blob é utilizado para grandes quantidade de dados não estruturados(arquivos, imagems, vídeos).
- Azure File,  é o sistema de compartilhamento de arquivos que pode ser montado nas VMs ou acessado
via protocolo SMG(Server Message Block)
- Azure Table Storage, o armazenamento de Tabelas, é um serviço NoSql permite o armazenamento de grandes volumes de dados semi-estruturados.
- Azure Queue Storage, serviço para gerenciamento de mensagens entre componente de sistemas distribuidos.
Importante utilizar o Azure Monitor para aconpanhar o desempenho do armazenamento.

### Segurança e identidade
- Azure Active Directory (Azure AD) é o serviço de identidade da Microsoft, utilizado para gerenciar usuários, grupos e permissões de acesso em todos os serviços da Azure.
- A Autenticação Multifator (MFA) adiciona uma camada extra de segurança, exigindo dois ou mais métodos de autenticação.
- O Controle de Acesso Baseado em Funções (RBAC) permite que você controle quem tem acesso a quais recursos, atribuindo permissões específicas a usuários ou grupos.
- O Azure Policy ajuda a garantir que todos os recursos na sua assinatura estejam em conformidade com as políticas de segurança e governança da organização.
- O Azure AD Identity Protection automatiza a detecção de identidades comprometidas e responde a riscos de segurança.
- O Azure Security Center oferece uma visão abrangente da segurança dos seus recursos, com recomendações para fortalecer a postura de segurança.
- Firewalls e Grupos de Segurança de Rede (NSG) ajudam a proteger suas redes e VMs contra acessos não autorizados.
- O Azure Key Vault permite armazenar e gerenciar segredos, certificados e chaves criptográficas de forma segura

### Calculadora do TCO (Custo total de Propriedade)
Possibilita simular os custo total para implantação de uma ambiente,
selecionando servidores, banco de dados, armazenamento e rede.
Ajuste de suposições como cobertura de software, por exemplo, usando licensas pré existentes.
