# PladixSolvers - Plataforma de Solvers de Captchas

PladixSolvers é uma plataforma avançada que integra os principais provedores de resolução de captchas, permitindo aos usuários registrarem-se, adquirirem acesso e utilizarem as APIs de forma ilimitada.

## 🚀 Provedores Integrados

- **Anticaptcha**
- **Capmonster**
- **2captcha**
- **Nextcaptcha**

## 🔑 Funcionalidades

- **Gerenciamento de API Key**: 
  - Visualização e cópia rápida da sua chave.
  - Limite de **2 redefinições** por mês.
  - Histórico detalhado de todas as API Keys geradas.

- **Uso da API**: 
  Selecione o provedor desejado e utilize a API com os seguintes parâmetros:

  ```bash
  http://localhost/PladixSolvers/api.php?api_key=SUACHAVEAQUI&provider=PROVEDOR&type={TIPO}&website_url={URL_DO_SITE}&website_key={CHAVE_DO_SITE}&action_captcha={AÇÃO_OPCIONAL}
  ```

  **Provedores Disponíveis:**
  - 2captcha
  - Anticaptcha
  - Capmonster
  - Nextcaptcha

  **Tipos de Captcha Suportados:**
  - recaptcha_v2
  - recaptcha_v3
  - hcaptcha
  - funcaptcha
  - image_captcha

  **Exemplo de Resposta:**

  ```json
  {
      "success": true,
      "solution": "03AGdBq24PBgUOEwYK...",
      "provider": "2captcha",
      "time_taken": 12.5
  }
  ```

## 📊 Histórico

- **Histórico de Captchas**: Monitoramento de todos os captchas resolvidos.
- **Histórico de Logins**: Registre os acessos à plataforma.
- **Histórico de Ações**: Acompanhe todas as operações realizadas.

## 🔒 Limite de Redefinições

Você pode redefinir sua API Key até **2 vezes por mês**. 

**Atenção:** Redefinir a API Key invalida a chave atual e todas as integrações precisarão ser atualizadas.

## ⚙️ Configurações do hCaptcha

- **Status do hCaptcha**: Indica se a proteção hCaptcha está ativada ou desativada para sua conta.
- **Segurança Adicional**: O hCaptcha ajuda a proteger contra tentativas automatizadas de login.

## 📩 Contato

Para suporte ou mais informações, entre em contato:

📬 [t.me/pladixoficial](https://t.me/pladixoficial)

---

💙 **PladixOficial** - Tecnologia em Primeiro Lugar!
