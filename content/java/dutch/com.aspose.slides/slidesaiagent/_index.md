---
title: SlidesAIAgent
second_title: Aspose.Slides voor Java API-referentie
description: Biedt AI-ondersteunde functies voor het verwerken van presentaties.
type: docs
url: /nl/com.aspose.slides/slidesaiagent/
---
**Erfenis:**
java.lang.Object
```
public class SlidesAIAgent
```

Biedt AI-ondersteunde functies voor het verwerken van presentaties.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | Initialiseert een nieuw exemplaar van [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) met een aangepaste AI-client. |
| [SlidesAIAgent()](#SlidesAIAgent--) | Initialiseert een nieuw exemplaar van [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) met de ingebouwde [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) met de standaardconfiguratie. |
## Methods

| Methode | Beschrijving |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Vertelt een presentatie naar de opgegeven taal met behulp van AI (synchrone versie). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Genereert een presentatie-exemplaar vanuit een tekstbeschrijving. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Genereert een presentatie-exemplaar vanuit een tekstbeschrijving. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

Initialiseert een nieuw exemplaar van [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) met een aangepaste AI-client. Gebruik deze overload om de AI-provider op te geven, uw eigen LLM te leveren, of de verbinding aan te passen (bijvoorbeeld door uw eigen java.net.HttpURLConnection te verstrekken). Elke implementatie van [IAIWebClient](../../com.aspose.slides/iaiwebclient) kan worden gebruikt. Om de ingebouwde [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) met de standaardconfiguratie te gebruiken, gebruik dan de overload SlidesAIAgent().

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | AI-client instantie. Elke implementatie van [IAIWebClient](../../com.aspose.slides/iaiwebclient) kan worden gebruikt. |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```

Initialiseert een nieuw exemplaar van [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) met de ingebouwde [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) met de standaardconfiguratie. De client maakt verbinding met Aspose’s eigen LLM en vereist geen extra configuratie. Om een andere AI-client te gebruiken, gebruik dan de overload SlidesAIAgent(IAIWebClient).

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```

Vertelt een presentatie naar de opgegeven taal met behulp van AI (synchrone versie).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Doel-presentatie |
| language | java.lang.String | Doeltaal |

--------------------

Het voorbeeld hieronder gebruikt de standaard [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient), die wordt gecreëerd door de parameterloze SlidesAIAgent()-constructor en maakt verbinding met Aspose’s eigen LLM. Om een andere AI-provider te gebruiken, uw eigen LLM te leveren, of de verbinding aan te passen (bijvoorbeeld door uw eigen java.net.HttpURLConnection te verstrekken), geef een [IAIWebClient](../../com.aspose.slides/iaiwebclient)-implementatie door aan de SlidesAIAgent(IAIWebClient)-constructor.

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

Genereert een presentatie-exemplaar vanuit een tekstbeschrijving. Geef een onderwerp, ideeën, citaten of tekstfragmenten op in de vereiste taal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| description | java.lang.String | Het onderwerp, de ideeën, citaten of tekstfragmenten. |
| presentationContentAmount | int | De hoeveelheid inhoud in de resulterende presentatie.

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

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```

Genereert een presentatie-exemplaar vanuit een tekstbeschrijving. Geef een onderwerp, ideeën, citaten of tekstfragmenten op in de vereiste taal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| description | java.lang.String | Het onderwerp, de ideeën, citaten of tekstfragmenten. |
| presentationContentAmount | int | De hoeveelheid inhoud in de resulterende presentatie. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Een presentatie die wordt gebruikt als sjabloon voor lay-out en ontwerp, ter vervanging van de standaard sjabloon.

--------------------

Het voorbeeld hieronder gebruikt de standaard [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient), die wordt gecreëerd door de parameterloze SlidesAIAgent()-constructor en maakt verbinding met Aspose’s eigen LLM. Om een andere AI-provider te gebruiken, uw eigen LLM te leveren, of de verbinding aan te passen (bijvoorbeeld door uw eigen java.net.HttpURLConnection te verstrekken), geef een [IAIWebClient](../../com.aspose.slides/iaiwebclient)-implementatie door aan de SlidesAIAgent(IAIWebClient)-constructor.

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

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)