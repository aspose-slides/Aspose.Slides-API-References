---
title: SlidesAIAgent
second_title: Aspose.Slides voor Android via Java API-referentie
description: Biedt AI-gestuurde functies voor het verwerken van presentaties.
type: docs
url: /nl/com.aspose.slides/slidesaiagent/
---
**Erfenis:**
java.lang.Object
```
public class SlidesAIAgent
```

Biedt AI-gestuurde functies voor het verwerken van presentaties.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | SlidesAIAgent constructor |
## Methods

| Methode | Beschrijving |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Vertalt een presentatie naar de opgegeven taal met behulp van AI (synchrone versie). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Genereert een presentatie-instantie vanuit een tekstbeschrijving. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Genereert een presentatie-instantie vanuit een tekstbeschrijving. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```


SlidesAIAgent constructor

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | AI-clientinstantie |

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public void translate(IPresentation presentation, String language)
```


Vertalt een presentatie naar de opgegeven taal met behulp van AI (synchrone versie).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Doelpresentatie |
| language | java.lang.String | Doeltaal |

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


Genereert een presentatie-instantie vanuit een tekstbeschrijving. Geef een onderwerp, ideeën, citaten of tekstfragmenten op in de gewenste taal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| description | java.lang.String | Het onderwerp, ideeën, citaten of tekstfragmenten. |
| presentationContentAmount | int | De hoeveelheid inhoud in de resulterende presentatie. |

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

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation)
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```


Genereert een presentatie-instantie vanuit een tekstbeschrijving. Geef een onderwerp, ideeën, citaten of tekstfragmenten op in de gewenste taal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| description | java.lang.String | Het onderwerp, ideeën, citaten of tekstfragmenten. |
| presentationContentAmount | int | De hoeveelheid inhoud in de resulterende presentatie. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Een presentatie die als sjabloon voor lay-out en ontwerp wordt gebruikt, ter vervanging van het standaard-sjabloon.

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

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation)