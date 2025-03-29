#  Projeto Intro Azure - DIO

##  Modelos de Nuvem

### Nuvem Pública
- Infraestrutura compartilhada entre múltiplos usuários.
- Escalabilidade e custo reduzido.
- Exemplos: Azure, AWS, Google Cloud.

### Nuvem Privada
- Infraestrutura exclusiva para uma organização.
- Maior controle e segurança.
- Exige mais investimento em hardware e manutenção.

### Nuvem Híbrida
- Combinação de nuvem pública e privada.
- Flexibilidade para manter dados sensíveis localmente e escalar na nuvem pública.
- Usado para cargas de trabalho variáveis e conformidade regulatória.

## Criando uma Conta de Estudante no Azure

1. Acesse [Microsoft Azure for Students](https://azure.microsoft.com/en-us/free/students/).
2. Clique em **"Start free"**.
3. Faça login com uma conta acadêmica (e-mail institucional).
4. Complete o processo de verificação (pode exigir um número de telefone, no meu caso foi só confirmação via e-mail).
5. Receba **$100 de crédito gratuito** + serviços gratuitos por 12 meses.

## Criando um Data Factory no Azure

### Passo 1: Criar um Grupo de Recursos
1. Acesse o [Portal do Azure](https://portal.azure.com/).
2. No menu, clique em **"Grupos de recursos"**.
3. Clique em **"Criar"** e forneça:
   - Nome do grupo de recursos (prefixo **rg**).
   - Região.
   - Assinatura.
4. Clique em **"Criar"**.

### 🔹 Passo 2: Criar um Azure Data Factory
1. No portal do Azure, procure por **"Data Factory"**.
2. Clique em **"Criar"** e forneça:
   - Nome do Data Factory (prefixo **adf**).
   - Grupo de recursos criado anteriormente.
   - Região.
   - Configuração de Git opcional.
3. Clique em **"Revisar + Criar"** e depois **"Criar"**.

