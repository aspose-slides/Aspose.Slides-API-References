---
title: AsposeAIWebClient
second_title: Aspose.Slides pro Java – referenční dokumentace API
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

Vestavěná [IAIWebClient](../../com.aspose.slides/iaiwebclient) implementace, která se připojuje k vlastnímu LLM společnosti Aspose. Jedná se o výchozí klient, který používá konstruktor bez parametrů  SlidesAIAgent()  .

## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Vytvoří instanci Aspose AI webového klienta, který se připojuje k výchozímu koncovému bodu Aspose LLM. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Vytvoří instanci Aspose AI webového klienta, který se připojuje k výchozímu koncovému bodu Aspose LLM pomocí externě spravovaného  HttpURLConnection . |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Vytvoří instanci Aspose AI webového klienta, který se připojuje k vlastnímu URL koncovému bodu. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Vytvoří instanci Aspose AI webového klienta, který se připojuje k vlastnímu URL koncovému bodu pomocí externě spravovaného  HttpURLConnection . |

## Metody

| Metoda | Popis |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Odesílá pokyn chatu modelu AI a vrací odpovědní zprávu na daný pokyn. |
| [createConversation()](#createConversation--) | Vytvoří instanci konverzace. |
| [dispose()](#dispose--) | Uvolňuje prostředky použité touto instancí. |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Vytvoří instanci Aspose AI webového klienta, který se připojuje k výchozímu koncovému bodu Aspose LLM. Jedná se o klienta používaného konstruktorovým voláním bez parametrů  SlidesAIAgent() , takže jeho explicitní vytvoření je potřeba jen v případě, že se klient předává přímo konstruktoru  SlidesAIAgent(IAIWebClient) .

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
| Parametr | Typ | Popis |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Externě spravovaná instance  HttpURLConnection . 

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

Vytvoří instanci Aspose AI webového klienta, který se připojuje k vlastnímu URL koncovému bodu. Použijte tuto přetíženou verzi, když máte URL poskytnuté týmem Aspose.Slides; v opačném případě použijte přetížení  AsposeAIWebClient()  s výchozím URL.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| url | java.lang.String | URL koncového bodu Aspose LLM, poskytnuté týmem Aspose.Slides. 

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

Vytvoří instanci Aspose AI webového klienta, který se připojuje k vlastnímu URL koncovému bodu pomocí externě spravovaného  HttpURLConnection . Poskytnutý  HttpURLConnection  není touto instancí uvolněn a zůstává ve vlastnictví volajícího. Použijte tuto přetíženou verzi, když máte URL poskytnuté týmem Aspose.Slides a chcete dodat vlastní  HttpURLConnection ; pokud potřebujete pouze vlastní  HttpURLConnection s výchozím URL, použijte místo toho přetížení  AsposeAIWebClient(HttpURLConnection) .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| url | java.lang.String | URL koncového bodu Aspose LLM, poskytnuté týmem Aspose.Slides. |
| httpClient | java.net.HttpURLConnection | Externě spravovaná instance  HttpURLConnection . 

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

Odesílá pokyn chatu modelu AI a vrací odpovědní zprávu na daný pokyn.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| instruction | java.lang.String | Instrukce nebo zpráva, která má být zpracována modelem AI. |

**Vrací:**
java.lang.String - Zpráva vygenerovaná modelem AI jako odpověď na zadanou instrukci.

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Vytvoří instanci konverzace. Na rozdíl od běžných volání AI konverzace zachovávají celý kontext.

**Vrací:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - An [IAIConversation](../../com.aspose.slides/iaiconversation) instance.

### dispose() {#dispose--}
```
public final void dispose()
```

Uvolňuje zdroje použité touto instancí.