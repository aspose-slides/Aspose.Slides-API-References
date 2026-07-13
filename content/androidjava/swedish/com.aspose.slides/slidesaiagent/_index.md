---
title: SlidesAIAgent
second_title: Aspose.Slides för Android via Java API-referens
description: Tillhandahåller AI-drivna funktioner för att bearbeta presentationer.
type: docs
url: /sv/com.aspose.slides/slidesaiagent/
---
**Arv:**
java.lang.Object
```
public class SlidesAIAgent
```

Tillhandahåller AI-drivna funktioner för att bearbeta presentationer.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | SlidesAIAgent-konstruktor |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Översätter en presentation till det angivna språket med AI (synkron version). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Skapar en presentationsinstans från en textbeskrivning. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Skapar en presentationsinstans från en textbeskrivning. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```


SlidesAIAgent-konstruktor

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | AI-klientinstans |

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public void translate(IPresentation presentation, String language)
```


Översätter en presentation till det angivna språket med AI (synkron version).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Målpresentation |
| language | java.lang.String | Målspråk

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


Skapar en presentationsinstans från en textbeskrivning. Ange ett ämne, idéer, citat eller textsnuttar på det önskade språket.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| description | java.lang.String | Ämnet, idéerna, citaten eller textsnuttarna. |
| presentationContentAmount | int | Mängden innehåll i den resulterande presentationen.

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

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation)
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```


Skapar en presentationsinstans från en textbeskrivning. Ange ett ämne, idéer, citat eller textsnuttar på det önskade språket.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| description | java.lang.String | Ämnet, idéerna, citaten eller textsnuttarna. |
| presentationContentAmount | int | Mängden innehåll i den resulterande presentationen. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | En presentation att använda som mall för layout och design, som ersätter standardmallen.

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

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation)