# Política de Privacidade — Bucky

**Data de vigência:** 10 de março de 2026

---

## 1. Introdução

Bem-vindo ao **Bucky** ("nós", "nosso" ou "aplicativo"), um gerenciador de clubes de leitura desenvolvido por **Devira**. Esta Política de Privacidade descreve como coletamos, usamos, armazenamos, compartilhamos e protegemos as suas informações pessoais quando você utiliza o aplicativo Bucky no Android ou iOS.

Ao utilizar o Bucky, você concorda com a coleta e o uso de informações conforme descrito nesta política. Se você não concordar com qualquer parte desta política, solicitamos que não utilize o aplicativo.

---

## 2. Informações que Coletamos

### 2.1 Informações fornecidas por você

- **Nome:** coletado durante o cadastro ou obtido do seu perfil Google/Apple.
- **Endereço de e-mail:** coletado durante o cadastro ou autenticação via Google/Apple.
- **Foto de perfil:** URL da imagem obtida do seu perfil Google (quando você faz login com o Google).
- **Progresso de leitura:** páginas lidas, progresso por clube, histórico de atualizações.
- **Histórico de livros:** livros lidos e finalizados em clubes.
- **Lista de desejos:** livros adicionados à lista de desejos dentro de clubes.
- **Código de convite (shareCode):** código alfanumérico único gerado automaticamente para identificar o seu perfil e permitir que outros usuários o adicionem a clubes.

### 2.2 Informações coletadas automaticamente

- **Identificador de usuário (UID):** gerado pelo Firebase Authentication e utilizado para identificar sua conta de forma anônima nos nossos servidores.
- **Dados de uso e diagnóstico:** coletados pelo Firebase Analytics para entender como o aplicativo é utilizado (funcionalidades acessadas, sessões, eventos de navegação). Esses dados são anonimizados e agregados.
- **Informações do dispositivo:** modelo do dispositivo, versão do sistema operacional e identificadores de publicidade, coletados pelo Firebase Analytics e/ou RevenueCat para análise de compatibilidade e processamento de assinaturas.

### 2.3 Informações de compras e assinaturas

Quando você realiza uma compra dentro do aplicativo (assinatura do plano **Bucky Ilimitado**), as seguintes informações são processadas:

- Dados da transação (ID da transação, data, valor) pelo **Google Play Billing** ou **Apple App Store**, conforme a plataforma.
- Status de entitlement (se você possui ou não o plano ativo) gerenciado pelo **RevenueCat**.

> ⚠️ **O Bucky não armazena dados de cartão de crédito, débito ou qualquer outro instrumento de pagamento.** Todos os dados financeiros são processados exclusivamente pela Google Play, Apple App Store e RevenueCat, cada um com suas próprias políticas de privacidade.

---

## 3. Como Utilizamos as Informações

Usamos as informações coletadas para as seguintes finalidades:

| Finalidade | Base legal |
|---|---|
| Autenticar sua identidade e criar/manter sua conta | Execução de contrato |
| Exibir seu nome, foto e progresso de leitura no app | Execução de contrato |
| Sincronizar dados de clubes de leitura entre dispositivos | Execução de contrato |
| Permitir que outros membros encontrem você por código de convite | Execução de contrato / consentimento |
| Processar assinaturas e verificar o plano ativo | Execução de contrato |
| Analisar o uso do aplicativo para melhorar funcionalidades | Interesse legítimo |
| Enviar notificações sobre atualizações do aplicativo (se habilitadas) | Consentimento |

---

## 4. Compartilhamento de Informações

**Não vendemos, alugamos ou compartilhamos suas informações pessoais com terceiros para fins publicitários.**

Compartilhamos dados somente nas seguintes situações:

### 4.1 Com outros usuários do aplicativo

- Seu **nome**, **foto de perfil** e **código de convite** são visíveis para membros dos clubes dos quais você participa.
- Seu **progresso de leitura** é visível para outros membros do mesmo clube.

### 4.2 Com fornecedores de serviços (terceiros)

| Fornecedor | Função | Política de Privacidade |
|---|---|---|
| **Google Firebase (Auth, Firestore, Analytics)** | Autenticação, banco de dados e análise de uso | [firebase.google.com/support/privacy](https://firebase.google.com/support/privacy) |
| **Google Sign-In (Credential Manager)** | Autenticação via conta Google | [policies.google.com/privacy](https://policies.google.com/privacy) |
| **Apple Sign-In** | Autenticação via conta Apple (iOS) | [apple.com/legal/privacy](https://www.apple.com/legal/privacy) |
| **RevenueCat** | Gerenciamento de assinaturas e compras in-app | [revenuecat.com/privacy](https://www.revenuecat.com/privacy) |
| **Google Books API** | Busca e recuperação de informações de livros | [policies.google.com/privacy](https://policies.google.com/privacy) |
| **Coil (carregamento de imagens)** | Carregamento de capas de livros e fotos de perfil | Processado localmente no dispositivo |

### 4.3 Por obrigação legal

Podemos divulgar suas informações quando exigido por lei, ordem judicial ou autoridade competente.

---

## 5. Armazenamento e Segurança dos Dados

- Os dados do usuário (nome, e-mail, progresso, clubes) são armazenados no **Google Cloud Firestore**, protegido por regras de segurança do Firebase que restringem o acesso apenas ao próprio usuário e aos membros autorizados do clube.
- A autenticação é gerenciada pelo **Firebase Authentication**, que utiliza tokens seguros (JWT) e criptografia padrão da indústria.
- Não transferimos dados para países fora do Brasil ou da União Europeia que não ofereçam nível adequado de proteção, exceto conforme necessário para operar os serviços de terceiros listados acima (Google, Apple, RevenueCat), todos aderentes a acordos internacionais de transferência de dados.

---

## 6. Retenção de Dados

- Seus dados são retidos enquanto sua conta estiver ativa no aplicativo.
- Se você solicitar a exclusão da conta, todos os seus dados pessoais armazenados no Firestore (nome, e-mail, progresso, histórico) serão excluídos em até **30 dias** úteis.
- Dados de transação relacionados a compras são mantidos pelo Google Play / Apple App Store e RevenueCat conforme suas respectivas políticas de retenção, independentemente de nossa ação.

---

## 7. Seus Direitos (LGPD — Lei nº 13.709/2018)

De acordo com a Lei Geral de Proteção de Dados (LGPD), você tem os seguintes direitos:

- **Acesso:** solicitar uma cópia dos dados pessoais que mantemos sobre você.
- **Correção:** solicitar a correção de dados incorretos ou desatualizados.
- **Exclusão:** solicitar a exclusão dos seus dados pessoais (exceto quando mantidos por obrigação legal).
- **Portabilidade:** solicitar a exportação dos seus dados em formato estruturado.
- **Revogação do consentimento:** revogar consentimentos fornecidos a qualquer momento.
- **Oposição:** opor-se ao tratamento de dados baseado em interesse legítimo.

Para exercer qualquer um desses direitos, entre em contato pelo e-mail indicado na seção 10.

---

## 8. Crianças e Adolescentes

O Bucky não é direcionado a menores de 13 anos. Não coletamos intencionalmente informações pessoais de crianças com menos de 13 anos. Se você acredita que coletamos dados de uma criança sem consentimento parental adequado, entre em contato conosco para que possamos excluir as informações imediatamente.

---

## 9. Alterações nesta Política

Podemos atualizar esta Política de Privacidade periodicamente. Quando fizermos alterações significativas, notificaremos você por meio de aviso dentro do aplicativo ou por e-mail antes que as mudanças entrem em vigor. Recomendamos que você revise esta política regularmente.

A data de vigência no topo deste documento indica quando a versão atual foi publicada.

---

## 10. Contato

Se você tiver dúvidas, solicitações ou reclamações sobre esta Política de Privacidade ou sobre o tratamento dos seus dados, entre em contato com o desenvolvedor responsável:

- **Responsável:** Devira
- **E-mail:** contato@devira.com.br
- **Aplicativo:** Bucky — Gerenciador de Clubes de Leitura
