---
title: SlidesAIAgent
second_title: Aspose.Slides pro Java - reference API
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
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | Initializes a new instance of [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) with a custom AI client. |
| [SlidesAIAgent()](#SlidesAIAgent--) | Initializes a new instance of [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) using the built-in [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) with its default configuration. |

## Metody

| Metoda | Popis |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Translates a presentation to the specified language using AI (synchronous version). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Generates a presentation instance from a text description. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Generates a presentation instance from a text description. |

### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

Inicializuje novou instanci [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) s vlastním AI klientem. Použijte toto přetížení k určení poskytovatele AI, poskytnutí vlastního LLM nebo přizpůsobení připojení (například poskytnutím vlastního java.net.HttpURLConnection). Lze použít libovolná implementace [IAIWebClient](../../com.aspose.slides/iaiwebclient). Pro použití vestavěného [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) s výchozí konfigurací použijte přetížení SlidesAIAgent().

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | AI client instance. Any implementation of [IAIWebClient](../../com.aspose.slides/iaiwebclient) can be used. |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```

Inicializuje novou instanci [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) pomocí vestavěného [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) s výchozí konfigurací. Klient se připojuje k vlastnímu LLM společnosti Aspose a nevyžaduje žádnou další konfiguraci. Pro použití jiného AI klienta použijte přetížení SlidesAIAgent(IAIWebClient).

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```

Překládá prezentaci do určeného jazyka pomocí AI (synchronní verze).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Cílová prezentace |
| language | java.lang.String | Cílový jazyk

--------------------

Příklad níže používá výchozí [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient), který je vytvořen bezparametrovým konstruktorem SlidesAIAgent() a připojuje se k vlastnímu LLM společnosti Aspose. Pro použití jiného poskytovatele AI, poskytnutí vlastního LLM nebo přizpůsobení připojení (například poskytnutím vlastního java.net.HttpURLConnection) předávejte implementaci [IAIWebClient](../../com.aspose.slides/iaiwebclient) do konstruktoru SlidesAIAgent(IAIWebClient).

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

Generuje instanci prezentace z textového popisu. Zadejte téma, nápady, citáty nebo úryvky textu v požadovaném jazyce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| description | java.lang.String | Téma, nápady, citáty nebo úryvky textu. |
| presentationContentAmount | int | Množství obsahu ve výsledné prezentaci.

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

**Návratová hodnota:**
[IPresentation](../../com.aspose.slides/ipresentation)

### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```

Generuje instanci prezentace z textového popisu. Zadejte téma, nápady, citáty nebo úryvky textu v požadovaném jazyce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| description | java.lang.String | Téma, nápady, citáty nebo úryvky textu. |
| presentationContentAmount | int | Množství obsahu ve výsledné prezentaci. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Prezentace, která bude použita jako šablona pro rozvržení a design, nahrazující výchozí šablonu.

--------------------

Příklad níže používá výchozí [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient), který je vytvořen bezparametrovým konstruktorem SlidesAIAgent() a připojuje se k vlastnímu LLM společnosti Aspose. Pro použití jiného poskytovatele AI, poskytnutí vlastního LLM nebo přizpůsobení připojení (například poskytnutím vlastního java.net.HttpURLConnection) předávejte implementaci [IAIWebClient](../../com.aspose.slides/iaiwebclient) do konstruktoru SlidesAIAgent(IAIWebClient).

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

**Návratová hodnota:**
[IPresentation](../../com.aspose.slides/ipresentation)