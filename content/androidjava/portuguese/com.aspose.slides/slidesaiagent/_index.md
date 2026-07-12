---
title: SlidesAIAgent
second_title: Aspose.Slides para Android via Referência da API Java
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
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | Construtor SlidesAIAgent |
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


Construtor SlidesAIAgent

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | Instância do cliente IA |

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public void translate(IPresentation presentation, String language)
```


Traduz uma apresentação para o idioma especificado usando IA (versão síncrona).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Apresentação de destino |
| language | java.lang.String | Idioma de destino

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


Gera uma instância de apresentação a partir de uma descrição de texto. Forneça um tópico, ideias, citações ou trechos de texto no idioma necessário.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| description | java.lang.String | O tópico, ideias, citações ou trechos de texto. |
| presentationContentAmount | int | A quantidade de conteúdo na apresentação resultante.

```
String prompt = "Generate a presentation about Aspose.Slides for Android via Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
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


Gera uma instância de apresentação a partir de uma descrição de texto. Forneça um tópico, ideias, citações ou trechos de texto no idioma necessário.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| description | java.lang.String | O tópico, ideias, citações ou trechos de texto. |
| presentationContentAmount | int | A quantidade de conteúdo na apresentação resultante. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Uma apresentação a ser usada como modelo para layout e design, substituindo o modelo padrão.

```
String prompt = "Generate a presentation about Aspose.Slides for Android via Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
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