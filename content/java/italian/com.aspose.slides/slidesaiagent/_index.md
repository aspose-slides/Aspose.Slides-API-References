---
title: SlidesAIAgent
second_title: Riferimento API Aspose.Slides per Java
description: Fornisce funzionalità basate su AI per l'elaborazione delle presentazioni.
type: docs
url: /it/com.aspose.slides/slidesaiagent/
---
**Inheritance:**
java.lang.Object
```
public class SlidesAIAgent
```

Fornisce funzionalità basate su AI per l'elaborazione delle presentazioni.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | Inizializza una nuova istanza di [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) con un client AI personalizzato. |
| [SlidesAIAgent()](#SlidesAIAgent--) | Inizializza una nuova istanza di [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) usando il [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) integrato con la sua configurazione predefinita. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Traduce una presentazione nella lingua specificata usando AI (versione sincrona). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Genera un'istanza di presentazione a partire da una descrizione testuale. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Genera un'istanza di presentazione a partire da una descrizione testuale. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

Inizializza una nuova istanza di [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) con un client AI personalizzato. Utilizza questo sovraccarico per specificare il provider AI, fornire il tuo LLM o personalizzare la connessione (ad esempio, fornendo il tuo java.net.HttpURLConnection). È possibile utilizzare qualsiasi implementazione di [IAIWebClient](../../com.aspose.slides/iaiwebclient). Per usare il [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) integrato con la sua configurazione predefinita, utilizza invece il sovraccarico SlidesAIAgent().

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | Istanza del client AI. È possibile utilizzare qualsiasi implementazione di [IAIWebClient](../../com.aspose.slides/iaiwebclient). |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```

Inizializza una nuova istanza di [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) usando il [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) integrato con la sua configurazione predefinita. Il client si connette al LLM proprietario di Aspose e non richiede configurazioni aggiuntive. Per utilizzare un client AI diverso, utilizza invece il sovraccarico SlidesAIAgent(IAIWebClient).

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```

Traduce una presentazione nella lingua specificata usando AI (versione sincrona).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentazione di destinazione |
| language | java.lang.String | Lingua di destinazione

--------------------

L'esempio seguente utilizza il [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) predefinito, creato dal costruttore senza parametri SlidesAIAgent() e collegato al LLM proprietario di Aspose. Per utilizzare un provider AI diverso, fornire il proprio LLM o personalizzare la connessione (ad esempio, fornendo il proprio java.net.HttpURLConnection), passare un'implementazione [IAIWebClient](../../com.aspose.slides/iaiwebclient) al costruttore SlidesAIAgent(IAIWebClient).

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

Genera un'istanza di presentazione a partire da una descrizione testuale. Fornisci un argomento, idee, citazioni o estratti di testo nella lingua richiesta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| description | java.lang.String | L'argomento, le idee, le citazioni o gli estratti di testo. |
| presentationContentAmount | int | La quantità di contenuto nella presentazione risultante.

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

**Ritorna:**
[IPresentation](../../com.aspose.slides/ipresentation)
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```

Genera un'istanza di presentazione a partire da una descrizione testuale. Fornisci un argomento, idee, citazioni o estratti di testo nella lingua richiesta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| description | java.lang.String | L'argomento, le idee, le citazioni o gli estratti di testo. |
| presentationContentAmount | int | La quantità di contenuto nella presentazione risultante. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Una presentazione da utilizzare come modello per layout e design, sostituendo il modello predefinito.

--------------------

L'esempio seguente utilizza il [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) predefinito, creato dal costruttore senza parametri SlidesAIAgent() e collegato al LLM proprietario di Aspose. Per utilizzare un provider AI diverso, fornire il proprio LLM o personalizzare la connessione (ad esempio, fornendo il proprio java.net.HttpURLConnection), passare un'implementazione [IAIWebClient](../../com.aspose.slides/iaiwebclient) al costruttore SlidesAIAgent(IAIWebClient).

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

**Ritorna:**
[IPresentation](../../com.aspose.slides/ipresentation)