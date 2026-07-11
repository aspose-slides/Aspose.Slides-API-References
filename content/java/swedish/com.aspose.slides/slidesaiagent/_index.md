---
title: SlidesAIAgent
second_title: Aspose.Slides för Java API-referens
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
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | Initierar en ny instans av [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) med en anpassad AI-klient. |
| [SlidesAIAgent()](#SlidesAIAgent--) | Initierar en ny instans av [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) med den inbyggda [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) med dess standardkonfiguration. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Översätter en presentation till det angivna språket med hjälp av AI (synkron version). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Genererar en presentationsinstans från en textbeskrivning. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Genererar en presentationsinstans från en textbeskrivning. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```


Initierar en ny instans av [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) med en anpassad AI-klient. Använd den här överlagringen för att ange AI-leverantören, tillhandahålla din egen LLM, eller anpassa anslutningen (till exempel genom att tillhandahålla din egen java.net.HttpURLConnection). Alla implementationer av [IAIWebClient](../../com.aspose.slides/iaiwebclient) kan användas. För att använda den inbyggda [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) med dess standardkonfiguration, använd SlidesAIAgent()-överlagringen istället.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | AI-klientinstans. Alla implementationer av [IAIWebClient](../../com.aspose.slides/iaiwebclient) kan användas. |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```


Initierar en ny instans av [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) med den inbyggda [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) med dess standardkonfiguration. Klienten ansluter till Asposes egen LLM och kräver ingen ytterligare konfiguration. För att använda en annan AI-klient, använd SlidesAIAgent(IAIWebClient)-överlagringen istället.

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```


Översätter en presentation till det angivna språket med hjälp av AI (synkron version).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Målpresentation |
| language | java.lang.String | Målspråk

--------------------

Exemplet nedan använder standard[AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient), som skapas av den parameterlösa SlidesAIAgent()-konstruktorn och ansluter till Asposes egen LLM. För att använda en annan AI-leverantör, tillhandahålla din egen LLM, eller anpassa anslutningen (till exempel genom att tillhandahålla din egen java.net.HttpURLConnection), skicka en [IAIWebClient](../../com.aspose.slides/iaiwebclient)-implementation till SlidesAIAgent(IAIWebClient)-konstruktorn.

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


Genererar en presentationsinstans från en textbeskrivning. Tillhandahåll ett ämne, idéer, citat eller textsnitt i det erforderliga språket.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| description | java.lang.String | Ämnet, idéerna, citaten eller textsnitten. |
| presentationContentAmount | int | Mängden innehåll i den färdiga presentationen.

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

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation)
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```


Genererar en presentationsinstans från en textbeskrivning. Tillhandahåll ett ämne, idéer, citat eller textsnitt i det erforderliga språket.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| description | java.lang.String | Ämnet, idéerna, citaten eller textsnitten. |
| presentationContentAmount | int | Mängden innehåll i den färdiga presentationen. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | En presentation att använda som mall för layout och design, som ersätter standardmallen.

--------------------

Exemplet nedan använder standard[AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient), som skapas av den parameterlösa SlidesAIAgent()-konstruktorn och ansluter till Asposes egen LLM. För att använda en annan AI-leverantör, tillhandahålla din egen LLM, eller anpassa anslutningen (till exempel genom att tillhandahålla din egen java.net.HttpURLConnection), skicka en [IAIWebClient](../../com.aspose.slides/iaiwebclient)-implementation till SlidesAIAgent(IAIWebClient)-konstruktorn.

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

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation)