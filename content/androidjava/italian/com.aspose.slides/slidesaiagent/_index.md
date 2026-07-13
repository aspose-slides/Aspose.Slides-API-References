---
title: SlidesAIAgent
second_title: Aspose.Slides per Android via Riferimento API Java
description: Fornisce funzionalità basate su IA per l'elaborazione delle presentazioni.
type: docs
url: /it/com.aspose.slides/slidesaiagent/
---
**Eredità:**
java.lang.Object
```
public class SlidesAIAgent
```

Fornisce funzionalità basate su IA per l'elaborazione delle presentazioni.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | Costruttore SlidesAIAgent |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Traduce una presentazione nella lingua specificata usando IA (versione sincrona). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Genera un'istanza di presentazione da una descrizione testuale. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Genera un'istanza di presentazione da una descrizione testuale. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

Costruttore SlidesAIAgent

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | Istanza client IA |

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public void translate(IPresentation presentation, String language)
```

Traduce una presentazione nella lingua specificata usando IA (versione sincrona).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentazione di destinazione |
| language | java.lang.String | Lingua di destinazione

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

Genera un'istanza di presentazione da una descrizione testuale. Fornisci un argomento, idee, citazioni o frammenti di testo nella lingua richiesta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| description | java.lang.String | L'argomento, le idee, le citazioni o i frammenti di testo. |
| presentationContentAmount | int | La quantità di contenuto nella presentazione risultante.

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

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation)
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```

Genera un'istanza di presentazione da una descrizione testuale. Fornisci un argomento, idee, citazioni o frammenti di testo nella lingua richiesta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| description | java.lang.String | L'argomento, le idee, le citazioni o i frammenti di testo. |
| presentationContentAmount | int | La quantità di contenuto nella presentazione risultante. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Una presentazione da usare come modello per layout e design, sostituendo il modello predefinito.

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

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation)