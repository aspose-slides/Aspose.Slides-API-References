---
title: AsposeAIWebClient
second_title: Aspose.Slides pro Android přes Java API Reference
description: Vestavěná implementace, která se připojuje k vlastnímu LLM společnosti Aspose.
type: docs
url: /cs/com.aspose.slides/asposeaiwebclient/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

Vestavěná [IAIWebClient](../../com.aspose.slides/iaiwebclient) implementace, která se připojuje k vlastnímu LLM společnosti Aspose. Toto je výchozí klient používaný bez parametrů  SlidesAIAgent()  konstruktorem.

## Konstruktory

| Constructor | Description |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Vytvoří instanci Aspose AI webového klienta, který se připojuje k výchozímu koncovému bodu Aspose LLM. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Vytvoří instanci Aspose AI webového klienta, který se připojuje k výchozímu koncovému bodu Aspose LLM pomocí externě spravovaného  HttpURLConnection . |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Vytvoří instanci Aspose AI webového klienta, který se připojuje k vlastnímu URL koncového bodu. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Vytvoří instanci Aspose AI webového klienta, který se připojuje k vlastnímu URL koncového bodu pomocí externě spravovaného  HttpURLConnection . |

## Metody

| Method | Description |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Odešle chatovou instrukci modelu AI a vrátí odpovědní zprávu k dané instrukci. |
| [createConversation()](#createConversation--) | Vytvoří instanci konverzace. |
| [dispose()](#dispose--) | Uvolní prostředky používané touto instancí. |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Vytvoří instanci Aspose AI webového klienta, který se připojuje k výchozímu koncovému bodu Aspose LLM. Jedná se o klienta používaného bez parametrů  SlidesAIAgent()  konstruktorem, takže jeho explicitní vytvoření je nutné jen při předání klienta přímo konstruktoru  SlidesAIAgent(IAIWebClient) .

```
AsposeAIWebClient aiClient = new AsposeAIWebClient();
 try {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (aiClient != null) aiClient.dispose();
 }
```

### AsposeAIWebClient(HttpURLConnection httpClient) {#AsposeAIWebClient-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(HttpURLConnection httpClient)
```

Vytvoří instanci Aspose AI webového klienta, který se připojuje k výchozímu koncovému bodu Aspose LLM pomocí externě spravovaného  HttpURLConnection . Poskytnutý  HttpURLConnection  není touto instancí uvolněn a zůstává ve vlastnictví volajícího.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Externě spravovaná instance  HttpURLConnection . |
```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (httpClient != null) httpClient.disconnect();
 }
``` |

### AsposeAIWebClient(String url) {#AsposeAIWebClient-java.lang.String-}
```
public AsposeAIWebClient(String url)
```

Vytvoří instanci Aspose AI webového klienta, který se připojuje k vlastnímu URL koncového bodu. Použijte toto přetížení, pokud máte URL poskytnuté týmem Aspose.Slides; jinak použijte přetížení  AsposeAIWebClient()  s výchozím URL.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.lang.String | URL koncového bodu Aspose LLM, poskytnuté týmem Aspose.Slides. |
```
AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl);
 try {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (aiClient != null) aiClient.dispose();
 }
``` |

### AsposeAIWebClient(String url, HttpURLConnection httpClient) {#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(String url, HttpURLConnection httpClient)
```

Vytvoří instanci Aspose AI webového klienta, který se připojuje k vlastnímu URL koncového bodu pomocí externě spravovaného  HttpURLConnection . Poskytnutý  HttpURLConnection  není touto instancí uvolněn a zůstává ve vlastnictví volajícího. Použijte toto přetížení, pokud máte URL poskytnuté týmem Aspose.Slides a chcete dodat vlastní  HttpURLConnection ; pokud potřebujete vlastní  HttpURLConnection  pouze s výchozím URL, použijte místo toho přetížení  AsposeAIWebClient(HttpURLConnection) .

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.lang.String | URL koncového bodu Aspose LLM, poskytnuté týmem Aspose.Slides. |
| httpClient | java.net.HttpURLConnection | Externě spravovaná instance  HttpURLConnection . |
```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl, httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (httpClient != null) httpClient.disconnect();
 }
``` |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

Odešle chatovou instrukci modelu AI a vrátí odpovědní zprávu k dané instrukci.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| instruction | java.lang.String | Instrukce nebo zpráva, která má být zpracována modelem AI. |

**Návratová hodnota:**
java.lang.String - Zpráva vygenerovaná modelem AI jako odpověď na danou instrukci.

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Vytvoří instanci konverzace. Na rozdíl od běžných AI volání konverzace uchovávají celý kontext.

**Návratová hodnota:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - An [IAIConversation](../../com.aspose.slides/iaiconversation) instance.

### dispose() {#dispose--}
```
public final void dispose()
```

Uvolní prostředky používané touto instancí.