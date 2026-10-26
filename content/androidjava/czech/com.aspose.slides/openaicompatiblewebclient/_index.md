---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides pro Android – reference Java API
description: Vestavěná implementace, která se připojuje k poskytovateli LLM kompatibilnímu s OpenAI na zadané základní URL.
type: docs
url: /cs/com.aspose.slides/openaicompatiblewebclient/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

Vestavěná implementace [IAIWebClient](../../com.aspose.slides/iaiwebclient), která se připojuje k poskytovateli LLM kompatibilnímu s OpenAI na zadané základní URL.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Vytvoří instanci webového klienta kompatibilního s OpenAI. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Vytvoří instanci webového klienta kompatibilního s OpenAI, který používá externě spravované HttpURLConnection . |
## Metody

| Metoda | Popis |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Odešle chat instrukci modelu AI pomocí externě spravované instance HttpURLConnection a vrátí odpovědní zprávu na danou instrukci. |
| [createConversation()](#createConversation--) | Vytvoří instanci konverzace. |
| [dispose()](#dispose--) | Uvolní prostředky použité touto instancí. |
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

Vytvoří instanci webového klienta kompatibilního s OpenAI.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| model | java.lang.String | Název modelu podporovaný poskytovatelem LLM. |
| apiKey | java.lang.String | API klíč (token). |
| baseUrl | java.lang.String | Základní URL kompatibilního OpenAI LLM. |
```
OpenAICompatibleWebClient aiClient =
         new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1");
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

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)
```

Vytvoří instanci webového klienta kompatibilního s OpenAI, který používá externě spravované HttpURLConnection . Poskytnuté HttpURLConnection není touto instancí uvolněno a zůstává ve vlastnictví volajícího.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| model | java.lang.String | Název modelu podporovaný poskytovatelem LLM. |
| apiKey | java.lang.String | API klíč (token). |
| baseUrl | java.lang.String | Základní URL kompatibilního OpenAI LLM. |
| httpClient | java.net.HttpURLConnection | Externě spravovaná instance HttpURLConnection . |
```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     OpenAICompatibleWebClient aiClient =
             new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1", httpClient);
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

Odešle chat instrukci modelu AI pomocí externě spravované instance HttpURLConnection a vrátí odpovědní zprávu na danou instrukci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| instruction | java.lang.String | Instrukce nebo zpráva, která má být zpracována modelem AI. |

**Návratová hodnota:**
java.lang.String - Zpráva vygenerovaná modelem AI jako odpověď na danou instrukci.
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Vytvoří instanci konverzace. Na rozdíl od běžných AI volání si konverzace uchovávají celý kontext.

**Návratová hodnota:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Instanci [IAIConversation](../../com.aspose.slides/iaiconversation).
### dispose() {#dispose--}
```
public final void dispose()
```

Uvolní prostředky použité touto instancí.