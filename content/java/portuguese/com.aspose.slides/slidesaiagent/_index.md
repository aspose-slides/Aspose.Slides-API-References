---
title: SlidesAIAgent
second_title: Referência da API Aspose.Slides para Java
description: Fornece recursos alimentados por IA para processar apresentações.
type: docs
url: /pt/com.aspose.slides/slidesaiagent/
---
**Herança:**
java.lang.Object
```
public class SlidesAIAgent
```

Fornece recursos alimentados por IA para processar apresentações.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | Inicializa uma nova instância de [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) com um cliente de IA personalizado. |
| [SlidesAIAgent()](#SlidesAIAgent--) | Inicializa uma nova instância de [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) usando o [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) integrado com sua configuração padrão. |
## Métodos

| Método | Descrição |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Traduz uma apresentação para o idioma especificado usando IA (versão síncrona). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Gera uma instância de apresentação a partir de uma descrição de texto. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Gera uma instância de apresentação a partir de uma descrição de texto. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

Inicializa uma nova instância de [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) com um cliente de IA personalizado. Use esta sobrecarga para especificar o provedor de IA, fornecer seu próprio LLM ou personalizar a conexão (por exemplo, fornecendo seu próprio java.net.HttpURLConnection). Qualquer implementação de [IAIWebClient](../../com.aspose.slides/iaiwebclient) pode ser usada. Para usar o [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) integrado com sua configuração padrão, use a sobrecarga  SlidesAIAgent()  em vez disso.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | Instância do cliente de IA. Qualquer implementação de [IAIWebClient](../../com.aspose.slides/iaiwebclient) pode ser usada. |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```

Inicializa uma nova instância de [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) usando o [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) integrado com sua configuração padrão. O cliente conecta ao LLM próprio da Aspose e não requer configuração adicional. Para usar um cliente de IA diferente, use a sobrecarga SlidesAIAgent(IAIWebClient) em vez disso.

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```

Traduz uma apresentação para o idioma especificado usando IA (versão síncrona).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Apresentação de destino |
| language | java.lang.String | Idioma de destino

--------------------

O exemplo abaixo usa o [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) padrão, que é criado pelo construtor SlidesAIAgent() sem parâmetros e conecta ao LLM próprio da Aspose. Para usar um provedor de IA diferente, fornecer seu próprio LLM ou personalizar a conexão (por exemplo, fornecendo seu próprio java.net.HttpURLConnection), passe uma implementação [IAIWebClient](../../com.aspose.slides/iaiwebclient) ao construtor SlidesAIAgent(IAIWebClient).

```
Presentation presentation = new Presentation("Presentation.pptx");
 try {
     IAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", "apiKey", null);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient);
     aiAgent.translate(presentation, "spanish");
     presentation.save("translated.pptx", SaveFormat.Pptx);
 } finally {
     if (presentation != null) presentation.dispose();
 }
``` |

### generatePresentation(String description, int presentationContentAmount) {#generatePresentation-java.lang.String-int-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount)
```

Gera uma instância de apresentação a partir de uma descrição de texto. Forneça um tópico, ideias, citações ou trechos de texto no idioma requerido.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| description | java.lang.String | O tópico, ideias, citações ou trechos de texto. |
| presentationContentAmount | int | A quantidade de conteúdo na apresentação resultante.

```
String prompt = "Generate a presentation about Aspose.Slides for Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
 OpenAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null);
 try {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient);
     IPresentation pres = aiAgent.generatePresentation(prompt, PresentationContentAmountType.Brief);
     pres.save("result.pptx", SaveFormat.Pptx);
 } finally {
     if (aiWebClient != null) aiWebClient.close();
 }
``` |

**Retorna:**
[IPresentation](../../com.aspose.slides/ipresentation)
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```

Gera uma instância de apresentação a partir de uma descrição de texto. Forneça um tópico, ideias, citações ou trechos de texto no idioma requerido.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| description | java.lang.String | O tópico, ideias, citações ou trechos de texto. |
| presentationContentAmount | int | A quantidade de conteúdo na apresentação resultante. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Uma apresentação para usar como modelo para layout e design, substituindo o modelo padrão.

--------------------

O exemplo abaixo usa o [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) padrão, que é criado pelo construtor SlidesAIAgent() sem parâmetros e conecta ao LLM próprio da Aspose. Para usar um provedor de IA diferente, fornecer seu próprio LLM ou personalizar a conexão (por exemplo, fornecendo seu próprio java.net.HttpURLConnection), passe uma implementação [IAIWebClient](../../com.aspose.slides/iaiwebclient) ao construtor SlidesAIAgent(IAIWebClient).

```
String prompt = "Generate a presentation about Aspose.Slides for Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
 IPresentation template = new Presentation("masterPresentation.pptx");
 try {
     OpenAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null);
     try {
         SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient);
         IPresentation pres =
             aiAgent.generatePresentation(prompt, PresentationContentAmountType.Brief, template);
         pres.save("result.pptx", SaveFormat.Pptx);
     } finally {
         if (aiWebClient != null) aiWebClient.close();
     }
 } finally {
     if (template != null) template.dispose();
 }
``` |

**Retorna:**
[IPresentation](../../com.aspose.slides/ipresentation)