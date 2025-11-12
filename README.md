# 💸 App de Organização de Finanças Pessoais com Vibe Coding

Aprenda a **criar soluções com IA** de forma criativa, guiando ferramentas como o **Copilot** e o **Lovable** com uma comunicação simples e natural. O foco é desenvolver o conceito de um **App de Organização de Finanças Pessoais**, mas, acima de tudo, aprender o **jeito Vibe de programar com IA**.

## ✨ O que é Vibe Coding

**Vibe Coding** é uma forma leve e criativa de desenvolver com IA, baseada em **conversas naturais e bem estruturadas**. Você não precisa escrever código linha por linha. Em vez disso, aprende a **guiar a IA** descrevendo suas ideias de forma clara, com **intenção e contexto**. Em outras palavras:

> Você mostra a vibe da sua ideia e a IA transforma em solução (ou em um caminho para ela).

## 🎯 Desafio

Problema: Muitas pessoas não conseguem manter um controle financeiro porque os aplicativos exigem muita entrada de dados manual, e a criação de orçamentos é vista como algo tedioso. 

Precisamos de uma solução que permita **controlar as finanças por meio de uma conversa simples**, com **agentes de IA** capazes de criar **planos de economia personalizados e automatizados**. Você deve utilizar as ideias de **Vibe Coding** e **MVP (Produto Mínimo Viável)** para desenvolver o **conceito de um aplicativo** que resolva o problema citado.

> [!IMPORTANT]
> Você **não precisa construir o código**! O foco está em **usar a IA como sua parceira criativa**, transformando boas ideias e prompts em conceitos funcionais que simulam um produto real.

## 🪄 Etapas do Desafio

### 1. Saber o que Pedir é a Chave! Otimize seus Prompts!

Antes de pedir para a IA "criar um app", é importante definir com clareza o que você quer construir e por quê. Para isso, você vai criar um **PRD (Product Requirements Document)** simplificado, uma especificação que serve como _briefing_ para a IA entender sua ideia.

Um bom PRD deve descrever o problema, quem será beneficiado, as principais funcionalidades e o que você espera que a IA entregue. Use o modelo abaixo como ponto de partida e adapte conforme o seu estilo:

```txt
# Contexto
Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário.  
A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas.

# Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização.  
Quero resolver isso com uma experiência de conversa e recomendações automáticas de economia.

# Público-Alvo
Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes.

# Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural.  
2. Classificar automaticamente as transações.  
3. Definir e acompanhar metas financeiras.  
4. Receber dicas de economia do “Agente Financeiro”.  
5. Visualizar relatórios simples e personalizados.

# Entregável da IA
Gerar um plano de MVP com as principais telas, recursos necessários e um esboço de validação inicial.  
Usar tom educativo e linguagem acessível, em português.
```

Depois de preencher o modelo, use o Copilot Web para revisar e melhorar o seu prompt antes de ir ao Lovable. A ideia é lapidar o texto até que ele fique claro, direto e reflita exatamente a sua intenção.

> [!TIP]
> Pense no PRD/Prompt como “o briefing que a IA precisa para entender sua vibe”. Portanto, quanto mais claro e intencional for o texto, mais próximas do ideal serão as respostas da IA.

### 2. Explorando o Lovable na Prática

Com seu PRD pronto e revisado, é hora de colocar a IA em ação. Abra o Lovable, cole seu prompt completo e peça o plano inicial do MVP do seu aplicativo. Como o plano gratuito limita você a 5 interações por dia, seja estratégico:
- Faça perguntas diretas e construtivas, como “crie o fluxo de telas com base nas funcionalidades listadas” ou “gere uma versão resumida do plano de MVP”;
- Priorize clareza nas instruções para aproveitar ao máximo cada resposta;

Durante essa etapa, você pode orientar a IA para três entregas principais:
1. Agente Financeiro: defina o comportamento e o tom de voz de um consultor financeiro pessoal, alinhado ao público e objetivo do app.
2. Fluxo de Telas: peça à IA para gerar o fluxo conceitual de telas com base nas funcionalidades descritas no PRD, simulando a interação por conversa.
3. Plano de MVP: solicite um resumo das 5 funcionalidades principais, dos recursos necessários e um plano de validação inicial (como medir se o app cumpre seu propósito).

> [!TIP]
> Se preferir, você pode fazer tudo com o **Copilot**. O importante é exercitar a habilidade de transformar intenções em instruções claras e testar os limites da IA como parceira criativa.

### 3. Entregando o Desafio na DIO

Finalize seu projeto criando um **repositório no GitHub** (pode ser um **fork** deste).  
No README do seu repositório, inclua:

PRD Usado:
```
1. Contexto
Criar um aplicativo de Organização de Finanças Pessoais baseado em interações por linguagem natural. O objetivo é simplificar o controle financeiro, eliminando formulários complexos e planilhas, oferecendo uma experiência fluida e acessível.

2. Problema a Resolver
Usuários desistem de apps financeiros por excesso de entrada manual.
Falta de personalização e recomendações práticas.
Necessidade de uma experiência mais natural e educativa.

3. Público-Alvo
Pessoas iniciantes no controle financeiro.
Usuários que buscam praticidade e simplicidade.
Pessoas que preferem conversar em vez de preencher dados.

4. Funcionalidades-Chave (MVP)
Registro de gastos via chat

Usuário informa em linguagem natural: “Gastei R$50 no mercado”.
Sistema interpreta valor, categoria e data automaticamente.
Classificação automática de transações
Algoritmo de NLP + regras simples para categorizar (alimentação, transporte, lazer).
Metas financeiras
Usuário define objetivos (“Quero economizar R$500 este mês”).
Sistema acompanha progresso e envia alertas.
Agente Financeiro (assistente virtual)
Sugestões de economia personalizadas.
Mensagens educativas e motivacionais.
Relatórios simples e personalizados
Gráficos básicos (pizza, barras).
Resumo semanal/mensal em linguagem acessível.

5. Entregáveis da IA
Plano de MVP com:

Principais telas:
Tela de chat (entrada de dados).
Tela de metas.
Tela de relatórios.
Tela de dicas do agente financeiro.

Recursos necessários:
Motor de NLP em português.
Banco de dados para transações e metas.
Módulo de relatórios (visualização simples).
Sistema de notificações.
Esboço de validação inicial:
Testar com grupo piloto de 10–20 usuários iniciantes.
Medir engajamento (quantidade de registros via chat).
Avaliar clareza das dicas e relatórios.

6. Tom e Linguagem
Educativo e acessível, em português.
Evitar termos técnicos complexos.
Usar frases curtas e diretas.
```
<img width="1110" height="586" alt="1" src="https://github.com/user-attachments/assets/79a76175-24be-4cf9-a2ed-83e5e080a6d2" />

<img width="1331" height="836" alt="3" src="https://github.com/user-attachments/assets/290d79f7-2a45-4d9b-bc2f-ab6efc7a0d8c" />

<img width="1296" height="701" alt="4" src="https://github.com/user-attachments/assets/6b5e9365-6758-459f-91d3-1fc8ddfa462b" />

Um resumo do que o seu **App de Finanças Pessoais** faz;
-   Separa gastos em categorias automaticamente
-   Registra as transações recentes e o progresso da meta
-   Exibe o saldo atual, gastos e economia.
-   Possui assistente financeiro via chat.

- Uma breve **reflexão sobre o processo**:
  - O que funcionou bem?
    R: O processo foi simples e mesmo sem escrever uma linha de código, obtive o resultado desejado.
  
  - O que não funcionou como o esperado?
    R: A necessidade de lidar com créditos no plano gratuito do lovable limita a experimentação e ajustes finos.
    
  - O que aprendeu sobre conversar com IAs?
    R: A tecnologia dos LLMs vem avançando a passos largos em pouquíssimo tempo.

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
