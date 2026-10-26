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
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | Initializes a new instance of [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) with a custom AI client. |
| [SlidesAIAgent()](#SlidesAIAgent--) | Initializes a new instance of [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) using the built-in [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) with its default configuration. |
## Métodos

| Método | Descrição |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Translates a presentation to the specified language using AI (synchronous version). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Generates a presentation instance from a text description. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Generates a presentation instance from a text description. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

Inicializa uma nova instância de [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) com um cliente de IA personalizado. Use esta sobrecarga para especificar o provedor de IA, fornecer seu próprio LLM ou personalizar a conexão (por exemplo, fornecendo seu próprio java.net.HttpURLConnection). Qualquer implementação de [IAIWebClient](../../com.aspose.slides/iaiwebclient) pode ser usada. Para usar o [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) interno com sua configuração padrão, use a  SlidesAIAgent()  sobrecarga em vez disso.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | AI client instance. Any implementation of [IAIWebClient](../../com.aspose.slides/iaiwebclient) can be used. |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```

Inicializa uma nova instância de [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) usando o [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) interno com sua configuração padrão. O cliente conecta ao LLM próprio da Aspose e não requer configuração adicional. Para usar um cliente de IA diferente, use a sobrecarga SlidesAIAgent(IAIWebClient) em vez disso.

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```

Translates a presentation to the specified language using AI (synchronous version).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Target presentation |
| language | java.lang.String | Target language

--------------------

O exemplo abaixo usa o [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) padrão, que é criado pelo construtor SlidesAIAgent() sem parâmetros e conecta ao LLM próprio da Aspose. Para usar um provedor de IA diferente, forneça seu próprio LLM ou personalize a conexão (por exemplo, fornecendo seu próprio java.net.HttpURLConnection), passe uma implementação [IAIWebClient](../../com.aspose.slides/iaiwebclient) ao construtor SlidesAIAgent(IAIWebClient).

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

Generates a presentation instance from a text description. Provide a topic, ideas, quotes, or text snippets in the required language.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| description | java.lang.String | The topic, ideas, quotes, or text snippets. |
| presentationContentAmount | int | The amount of content in the resulting presentation.

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

**Retorno:**
[IPresentation](../../com.aspose.slides/ipresentation)
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```

Generates a presentation instance from a text description. Provide a topic, ideas, quotes, or text snippets in the required language.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| description | java.lang.String | The topic, ideas, quotes, or text snippets. |
| presentationContentAmount | int | The amount of content in the resulting presentation. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | A presentation to use as a template for layout and design, replacing the default template.

--------------------

O exemplo abaixo usa o [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) padrão, que é criado pelo construtor SlidesAIAgent() sem parâmetros e conecta ao LLM próprio da Aspose. Para usar um provedor de IA diferente, forneça seu próprio LLM ou personalize a conexão (por exemplo, fornecendo seu próprio java.net.HttpURLConnection), passe uma implementação [IAIWebClient](../../com.aspose.slides/iaiwebclient) ao construtor SlidesAIAgent(IAIWebClient).

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

**Retorno:**
[IPresentation](../../com.aspose.slides/ipresentation)