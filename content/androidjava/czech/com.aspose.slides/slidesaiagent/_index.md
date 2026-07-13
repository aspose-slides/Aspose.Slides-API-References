---
title: SlidesAIAgent
second_title: Aspose.Slides pro Android přes Java API Reference
description: Poskytuje funkce poháněné AI pro zpracování prezentací.
type: docs
url: /cs/com.aspose.slides/slidesaiagent/
---
**Dědičnost:**
java.lang.Object
```
public class SlidesAIAgent
```

Poskytuje funkce poháněné AI pro zpracování prezentací.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | konstruktor SlidesAIAgent |
## Metody

| Metoda | Popis |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Překládá prezentaci do zadaného jazyka pomocí AI (synchronní verze). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Vytváří instanci prezentace z textového popisu. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Vytváří instanci prezentace z textového popisu. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```


konstruktor SlidesAIAgent

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | instance AI klienta |

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public void translate(IPresentation presentation, String language)
```


Překládá prezentaci do zadaného jazyka pomocí AI (synchronní verze).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Cílová prezentace |
| language | java.lang.String | Cílový jazyk

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


Vytváří instanci prezentace z textového popisu. Poskytněte téma, nápady, citáty nebo úryvky textu v požadovaném jazyce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| description | java.lang.String | Téma, nápady, citáty nebo úryvky textu. |
| presentationContentAmount | int | Množství obsahu ve výsledné prezentaci.

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

**Vrací:**
[IPresentation](../../com.aspose.slides/ipresentation)
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```


Vytváří instanci prezentace z textového popisu. Poskytněte téma, nápady, citáty nebo úryvky textu v požadovaném jazyce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| description | java.lang.String | Téma, nápady, citáty nebo úryvky textu. |
| presentationContentAmount | int | Množství obsahu ve výsledné prezentaci. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Prezentace, která bude použita jako šablona pro rozvržení a design, nahrazující výchozí šablonu.

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

**Vrací:**
[IPresentation](../../com.aspose.slides/ipresentation)