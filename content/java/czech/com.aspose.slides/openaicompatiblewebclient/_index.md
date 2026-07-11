---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides pro Java – referenční příručka API
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

Vestavěná [IAIWebClient](../../com.aspose.slides/iaiwebclient) implementace, která se připojuje k poskytovateli LLM kompatibilnímu s OpenAI na zadané základní URL.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Vytvoří instanci webového klienta kompatibilního s OpenAI. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Vytvoří instanci webového klienta kompatibilního s OpenAI, který používá externě spravovaný  HttpClient . |
## Metody

| Metoda | Popis |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Vytvoří instanci konverzace. |
| [dispose()](#dispose--) | Uvolní prostředky používané touto instancí. |
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
| baseUrl | java.lang.String | Základní URL LLM kompatibilního s OpenAI. |
```
using (OpenAICompatibleWebClient aiClient = new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1"))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)
```

Vytvoří instanci webového klienta kompatibilního s OpenAI, který používá externě spravovaný HttpClient. Poskytnutý HttpClient není touto instancí uvolněn a zůstává ve vlastnictví volajícího.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| model | java.lang.String | Název modelu podporovaný poskytovatelem LLM. |
| apiKey | java.lang.String | API klíč (token). |
| baseUrl | java.lang.String | Základní URL LLM kompatibilního s OpenAI. |
| httpClient | java.net.HttpURLConnection | Externě spravovaná instance HttpClient. |
```
using (HttpClient httpClient = new HttpClient())
 {
     OpenAICompatibleWebClient aiClient = new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1", httpClient);
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

Odešle chatovou instrukci modelu AI pomocí poskytnuté instance HttpConnection a vrátí odpovědní zprávu k dané instrukci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Vrací:**
java.lang.String
### createConversation() {#createConversation--}
```
public final IIAConversation createConversation()
```

Vytvoří instanci konverzace. Na rozdíl od běžných AI volání konverzace zachovávají celý kontext.

**Vrací:**
[IAIConversation](../../com.aspose.slides/iaiconversation) – instanci [IAIConversation](../../com.aspose.slides/iaiconversation).
### dispose() {#dispose--}
```
public final void dispose()
```

Uvolní prostředky používané touto instancí.