---
title: SlidesAIAgent
second_title: Aspose.Slides voor Android via Java API Referentie
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
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | Initialiseert een nieuwe instantie van [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) met een aangepaste AI-client. |
| [SlidesAIAgent()](#SlidesAIAgent--) | Initialiseert een nieuwe instantie van [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) met het ingebouwde [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) met de standaardconfiguratie. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Vertaal een presentatie naar de opgegeven taal met behulp van AI (synchrone versie). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Genereert een presentatie-instantie vanuit een tekstbeschrijving. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Genereert een presentatie-instantie vanuit een tekstbeschrijving. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

Initialiseert een nieuwe instantie van [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) met een aangepaste AI-client. Gebruik deze overload om de AI-provider op te geven, uw eigen LLM te leveren, of de verbinding aan te passen (bijvoorbeeld door uw eigen java.net.HttpURLConnection te leveren). Elke implementatie van [IAIWebClient](../../com.aspose.slides/iaiwebclient) kan worden gebruikt. Om het ingebouwde [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) met de standaardconfiguratie te gebruiken, gebruikt u de  SlidesAIAgent()  overload in plaats daarvan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | AI-clientinstance. Elke implementatie van [IAIWebClient](../../com.aspose.slides/iaiwebclient) kan worden gebruikt. |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```

Initialiseert een nieuwe instantie van [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) met het ingebouwde [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) met de standaardconfiguratie. De client maakt verbinding met Aspose's eigen LLM en vereist geen extra configuratie. Om een andere AI-client te gebruiken, gebruikt u de SlidesAIAgent(IAIWebClient) overload in plaats daarvan.

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```

Vertaal een presentatie naar de opgegeven taal met behulp van AI (synchrone versie).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Doelpresentatie |
| language | java.lang.String | Doeltaal

--------------------

Het voorbeeld hieronder gebruikt de standaard [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient), die wordt gecreëerd door de parameterloze SlidesAIAgent() constructor en verbinding maakt met Aspose's eigen LLM. Om een andere AI-provider te gebruiken, uw eigen LLM te leveren, of de verbinding aan te passen (bijvoorbeeld door uw eigen java.net.HttpURLConnection te leveren), geeft u een [IAIWebClient](../../com.aspose.slides/iaiwebclient)-implementatie door aan de SlidesAIAgent(IAIWebClient) constructor.

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

Genereert een presentatie-instantie vanuit een tekstbeschrijving. Geef een onderwerp, ideeën, citaten, of tekstfragmenten op in de vereiste taal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| description | java.lang.String | Het onderwerp, ideeën, citaten, of tekstfragmenten. |
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

**Retourwaarde:**
[IPresentation](../../com.aspose.slides/ipresentation)
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```

Genereert een presentatie-instantie vanuit een tekstbeschrijving. Geef een onderwerp, ideeën, citaten, of tekstfragmenten op in de vereiste taal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| description | java.lang.String | Het onderwerp, ideeën, citaten, of tekstfragmenten. |
| presentationContentAmount | int | De hoeveelheid inhoud in de resulterende presentatie. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Een presentatie die wordt gebruikt als sjabloon voor lay-out en ontwerp, vervangt de standaard-sjabloon. |

--------------------

Het voorbeeld hieronder gebruikt de standaard [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient), die wordt gecreëerd door de parameterloze SlidesAIAgent() constructor en verbinding maakt met Aspose's eigen LLM. Om een andere AI-provider te gebruiken, uw eigen LLM te leveren, of de verbinding aan te passen (bijvoorbeeld door uw eigen java.net.HttpURLConnection te leveren), geeft u een [IAIWebClient](../../com.aspose.slides/iaiwebclient)-implementatie door aan de SlidesAIAgent(IAIWebClient) constructor.

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

**Retourwaarde:**
[IPresentation](../../com.aspose.slides/ipresentation)