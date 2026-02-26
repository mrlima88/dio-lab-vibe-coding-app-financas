# 💸 App quiz interativo sobre Scrum, com Vibe Coding

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
Contexto
Criar um aplicativo de quiz sobre Scrum, com perguntas de múltipla escolha (4 alternativas). O sistema deve permitir que usuários se cadastrem, respondam às questões e sejam ranqueados conforme acertam, promovendo aprendizado gamificado e competitivo.

Problema
Os simulados e materiais de estudo tradicionais são maçantes e pouco interativos, o que desmotiva os candidatos que querem se preparar para certificações Scrum. Falta uma forma mais dinâmica e divertida de praticar os conteúdos.

Público-Alvo
• 	Profissionais que desejam aperfeiçoar suas habilidades em Scrum.
• 	Estudantes e candidatos que estão se preparando para certificações oficiais (PSM, CSM, etc.).
• 	Qualquer pessoa interessada em aprender Scrum de forma prática e engajante.

Funcionalidades-Chave
• 	Cadastro/Login de usuários com nome e sobrenome.
• 	Banco inicial de 20 perguntas sobre Scrum, com 4 alternativas e apenas 1 correta.
• 	Sistema de pontuação: cada resposta correta soma pontos definidos pelo administrador.
• 	Ranking em tempo real dos usuários com maior pontuação.
• 	Interface administrativa com:
• 	CRUD de perguntas (criar, editar, excluir).
• 	Gestão de usuários.
• 	Interação com IA em linguagem natural para:
• 	Criar novas perguntas automaticamente.
• 	Gerar questões a partir de links indicados.
• 	Solicitar diretamente no chat a criação de perguntas.
• 	Feedback imediato após cada resposta (correto/incorreto).
• 	Expansão futura: possibilidade de incluir novos módulos de estudo ou diferentes níveis de dificuldade.

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

- Seu **prompt final** (PRD);
Após conversar com o copilot solicitei que ele criace um prompt + PRD completo + as 20 perguntas iniciais.

Vou colocar aqui a forma de texto apenas.

🚀 Prompt para Lovable
Prompt:
“Criar um aplicativo de quiz sobre Scrum com cadastro/login de usuários, banco inicial de 20 perguntas, sistema de pontuação, 
ranking em tempo real e painel administrativo com interação via IA em linguagem natural. As perguntas iniciais já estão incluídas abaixo.”

PRD Final – Quiz Scrum App
Contexto
Criar um aplicativo de quiz sobre Scrum, com perguntas de múltipla escolha (4 alternativas). O sistema deve permitir que usuários se cadastrem, respondam às questões e sejam ranqueados conforme acertam, promovendo aprendizado gamificado e competitivo.
Problema
Os simulados e materiais de estudo tradicionais são maçantes e pouco interativos, o que desmotiva os candidatos que querem se preparar para certificações Scrum.
Público-Alvo
- Profissionais que desejam aperfeiçoar suas habilidades em Scrum.
- Estudantes e candidatos que estão se preparando para certificações oficiais (PSM, CSM, etc.).
- Qualquer pessoa interessada em aprender Scrum de forma prática e engajante.
Funcionalidades-Chave
- Cadastro/Login de usuários com nome e sobrenome.
- Banco inicial de 20 perguntas sobre Scrum, com 4 alternativas e apenas 1 correta.
- Sistema de pontuação: cada resposta correta soma pontos definidos pelo administrador.
- Ranking em tempo real dos usuários com maior pontuação.
- Interface administrativa com CRUD de perguntas e gestão de usuários.
- Interação com IA em linguagem natural para criar novas perguntas, gerar questões a partir de links e solicitar diretamente no chat.
- Feedback imediato após cada resposta.
- Expansão futura para novos módulos e níveis de dificuldade.
Requisitos Funcionais
- Perguntas com 4 alternativas e apenas 1 correta.
- Usuário só pode responder cada pergunta uma vez.
- Ranking atualizado automaticamente.
- Administrador pode adicionar novas perguntas manualmente ou via IA.
- IA deve aceitar comandos como:
- “Adicione 5 perguntas sobre Daily Scrum.”
- “Crie questões baseadas neste link [URL].”
- “Simplifique as perguntas para nível iniciante.”
Requisitos Não Funcionais
- Performance: respostas e ranking devem ser atualizados em tempo real.
- Segurança: autenticação básica para usuários e administrador.
- Escalabilidade: permitir expansão do banco de perguntas.
- Usabilidade: interface intuitiva, acessível em dispositivos móveis e desktop.
Critérios de Aceitação
- Usuário consegue se cadastrar e responder às 20 perguntas iniciais.
- Ranking mostra corretamente os usuários com maior pontuação.
- Administrador consegue adicionar novas perguntas via interface ou IA.
- Sistema atribui pontuação correta e atualiza ranking automaticamente.
Dependências
- Plataforma Lovable para desenvolvimento sem código.
- Banco de dados para armazenar usuários, perguntas e pontuações.
- Módulo de IA/NLP para interação em linguagem natural e geração de perguntas.
Priorização
- Cadastro/Login de usuários.
- Banco inicial de 20 perguntas sobre Scrum.
- Sistema de pontuação e ranking.
- Interface administrativa.
- Interação com IA para criação e gestão de perguntas.


  ------------O que funcionou bem?--------
  - O Quiz com as perguntas e ranking que são o coração do app estão funcionando muito bem.
    
  - ----------O que não funcionou como o esperado?------
  -  Na primeira vez que mandei o comando ele não criou a pagina do adm, porém logo que terminou de executar me deu opção de criar essa parte que faltava.
  -  
    -----------O que aprendeu sobre conversar com IAs?--------
  -  Está sendo uma experiencia maravilhosa, tando que tive um problema e precisei resolver
  -  Por algum motivo minha senha parou de funcionar, como eu não tinha inserido uma função para quem esquece a senha precisei pedir a Lovable e ele em seguida já criou.
        INteração com a lovable chat   [=Inclua uma opção para pode redefinir a senha quando o usuário a esquece
 Vou adicionar a funcionalidade de redefinição de senha.
Vou adicionar a funcionalidade de redefinição de senha.
Add forgot/reset password flow
Pronto! Agora na tela de login há o link "Esqueceu a senha?" que envia um e-mail de redefinição, e a página /reset-password permite ao usuário definir uma nova senha.
]
> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
