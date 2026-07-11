---
title: AsposeAIWebClient
second_title: Aspose.Slides pro Java API referenci
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

Vestavěná [IAIWebClient](../../com.aspose.slides/iaiwebclient) implementace, která se připojuje k vlastnímu LLM společnosti Aspose. Jedná se o výchozí klient, který používá konstruktor bez parametrů SlidesAIAgent().
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Vytvoří instanci Aspose AI webového klienta, který se připojí k výchozímu koncovému bodu Aspose LLM. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Vytvoří instanci Aspose AI webového klienta, který se připojí k výchozímu koncovému bodu Aspose LLM pomocí externě spravovaného HttpClient. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Vytvoří instanci Aspose AI webového klienta, který se připojí k vlastnímu koncovému bodu URL. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Vytvoří instanci Aspose AI webového klienta, který se připojí k vlastnímu koncovému bodu URL pomocí externě spravovaného HttpClient. |
## Metody

| Metoda | Popis |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Vytvoří instanci konverzace. |
| [dispose()](#dispose--) | Uvolní prostředky používané touto instancí. |
### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Vytvoří instanci Aspose AI webového klienta, který se připojí k výchozímu koncovému bodu Aspose LLM. Jedná se o klienta používaného konstruktoru bez parametrů SlidesAIAgent(), takže jeho explicitní vytvoření je vyžadováno jen při přímém předání klienta konstruktoru SlidesAIAgent(IAIWebClient) přímo.
```
using (AsposeAIWebClient aiClient = new AsposeAIWebClient())
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
```

### AsposeAIWebClient(HttpURLConnection httpClient) {#AsposeAIWebClient-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(HttpURLConnection httpClient)
```

Vytvoří instanci Aspose AI webového klienta, který se připojí k výchozímu koncovému bodu Aspose LLM pomocí externě spravovaného HttpClient. Poskytnutý HttpClient není touto instancí uvolněn a zůstává ve vlastnictví volajícího.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Externě spravovaná instance HttpClient. |
```
using (HttpClient httpClient = new HttpClient())
 {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### AsposeAIWebClient(String url) {#AsposeAIWebClient-java.lang.String-}
```
public AsposeAIWebClient(String url)
```

Vytvoří instanci Aspose AI webového klienta, který se připojí k vlastnímu URL koncovému bodu. Použijte tuto přetížení, pokud máte URL poskytnuté týmem Aspose.Slides; jinak použijte přetížení AsposeAIWebClient() s výchozím URL.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| url | java.lang.String | URL koncového bodu Aspose LLM, poskytnuté týmem Aspose.Slides. |
```
using (AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### AsposeAIWebClient(String url, HttpURLConnection httpClient) {#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(String url, HttpURLConnection httpClient)
```

Vytvoří instanci Aspose AI webového klienta, který se připojí k vlastnímu URL koncovému bodu pomocí externě spravovaného HttpClient. Poskytnutý HttpClient není touto instancí uvolněn a zůstává ve vlastnictví volajícího. Použijte tuto přetížení, pokud máte URL poskytnuté týmem Aspose.Slides a chcete dodat svůj vlastní HttpClient; pokud potřebujete pouze svůj vlastní HttpClient s výchozím URL, použijte přetížení AsposeAIWebClient(HttpClient) místo toho.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| url | java.lang.String | URL koncového bodu Aspose LLM, poskytnuté týmem Aspose.Slides. |
| httpClient | java.net.HttpURLConnection | Externě spravovaná instance HttpClient. |
```
using (HttpClient httpClient = new HttpClient())
 {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl, httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

Odešle pokyn chatu do AI modelu pomocí poskytnuté instance HttpConnection a vrátí zprávu odpovědi na zadaný pokyn.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Vrací:**
java.lang.String
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Vytvoří instanci konverzace. Na rozdíl od běžných AI volání si konverzace uchovávají celý kontext.

**Vrací:**
[IAIConversation](../../com.aspose.slides/iaiconversation) – instance [IAIConversation](../../com.aspose.slides/iaiconversation).
### dispose() {#dispose--}
```
public final void dispose()
```

Uvolní prostředky používané touto instancí.