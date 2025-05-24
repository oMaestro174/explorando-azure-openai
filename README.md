# 🧠 Explorando Azure OpenAI: Primeiras Experiências com Modelos GPT

Durante os testes com a criação e uso da instância **Azure OpenAI**, explorei várias funcionalidades importantes da plataforma, desde a implantação até ajustes de comportamento do modelo. Abaixo, compartilho um resumo dessa jornada.

---

## ☁️ Etapa 1 – Criando a Instância do Azure OpenAI

No portal do Azure, criei uma instância do serviço **Azure OpenAI** a partir da galeria de recursos. O processo é semelhante à criação de outros serviços no Azure.

![Criação da instância](assets/02-azure-openai-instance-create.png)

---

## 🧪 Etapa 2 – Explorando a Foundry

Após a criação, acessei a seção **Foundry**, onde é possível visualizar os modelos disponíveis e seus detalhes. A interface é intuitiva e permite entender rapidamente o que cada modelo oferece.

![Foundry do Azure OpenAI](assets/06-azure-openai-foundry.png)

---

## 📊 Etapa 3 – Visualizando os Modelos Disponíveis

A Foundry apresenta diversos modelos, incluindo variantes da série GPT, com informações sobre versão, desempenho e uso recomendado. Nesse momento, me chamou atenção a presença do **GPT-4.1**.

![Modelos disponíveis](assets/07-azure-openai-foundry-modelos.png)

---

## ✅ Etapa 4 – Conclusões sobre o Modelo GPT-4.1 Implantado

Ao analisar os detalhes do modelo implantado, verifiquei que o **GPT-4.1** estava disponível para uso imediato com suporte a personalização de parâmetros.

![Conclusão do modelo implantado](assets/09-azure-openai-foundry-conclusoes-usar-modelo-gpt-4.1-implantadado.png)

---

## 🔡 Etapa 5 – Tokenização com tiktoken

A tokenização é um aspecto importante ao trabalhar com modelos de linguagem. A ferramenta `tiktoken` foi essencial para visualizar como o texto seria convertido em tokens.

![Tokenização](assets/10-tokenizacao-tiktoken.png)

---

## 🎛️ Etapa 6 – Testando Parâmetros no Playground

No playground do Azure OpenAI, realizei testes alterando parâmetros como temperatura, top_p e frequência de penalização, observando como isso impactava nas respostas do modelo.

![Parâmetros do playground](assets/12-azure-playground-parametros.png)

---

## 🧩 Etapa 7 – Personalizando Instruções e Contexto

Foi possível personalizar o comportamento do modelo com instruções específicas e exemplos de contexto, o que direcionou melhor as respostas para minha necessidade.

![Alterando instruções e contexto](assets/13-azure-playground-alterando-instrucoes-e-contexto.png)

---

## 🐞 Etapa 8 – Lidando com um Bug no Playground

Durante os testes, encontrei um pequeno bug de exibição na interface do playground, que não afetou a funcionalidade mas vale o registro.

![Bug no playground](assets/14-azure-playground-erro-bug.png)

---

## 💬 Etapa 9 – Resposta Gerada pelo Modelo

Com os parâmetros ajustados, obtive uma resposta clara e coerente do modelo. Esse momento confirmou o potencial da ferramenta para aplicações reais.

![Resposta do modelo](assets/15-azure-playground-resposta.png)

---

## 🧠 Etapa 10 – Resposta Personalizada

Após personalizar ainda mais o prompt e o sistema de contexto, o modelo respondeu com maior alinhamento à expectativa.

![Resposta personalizada](assets/15-azure-playground-resposta-personalizada.png)

---

## ✍️ Conclusão

Explorar o **Azure OpenAI** foi uma experiência reveladora. Além de testar modelos como o GPT-4.1, entendi melhor como os parâmetros e o contexto influenciam o comportamento da IA. Pretendo avançar para integrações via API, explorar fine-tuning e desenvolver soluções com base nesse serviço robusto e flexível.

---
