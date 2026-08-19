---
title: OpenAIWebClient
second_title: Aspose.Slides pro referenci API Java
description: Vestavěná implementace, která se připojuje k rozhraní OpenAI API.
type: docs
url: /cs/com.aspose.slides/openaiwebclient/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

Vestavěná [IAIWebClient](../../com.aspose.slides/iaiwebclient) implementace, která se připojuje k rozhraní OpenAI API.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Vytvoří instanci webového klienta OpenAI. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Vytvoří instanci webového klienta OpenAI, který používá externě spravovaného  HttpClient . |
## Metody

| Metoda | Popis |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Vytvoří instanci konverzace. |
| [close()](#close--) | Uvolní prostředky použité touto instancí. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

Vytvoří instanci webového klienta OpenAI.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| model | java.lang.String | OpenAI jazykový model. Možné hodnoty: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Klíč API OpenAI. |
| organizationId | java.lang.String | ID organizace (volitelné).

```
using (OpenAIWebClient aiClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |
### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```

Vytvoří instanci webového klienta OpenAI, který používá externě spravovaného  HttpClient . Poskytnutý HttpClient není touto instancí uvolněn a zůstává ve vlastnictví volajícího.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| model | java.lang.String | OpenAI jazykový model. Možné hodnoty: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Klíč API OpenAI |
| organizationId | java.lang.String | ID organizace (volitelné) |
| httpClient | java.net.HttpURLConnection | Instance externě spravovaného HttpClient

```
using (HttpClient httpClient = new HttpClient())
 {
     OpenAIWebClient aiClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null, httpClient);
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

Odešle chatovou instrukci modelu AI pomocí poskytnuté instance HttpConnection a vrátí odpovědní zprávu na danou instrukci.

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

Vytvoří instanci konverzace. Na rozdíl od běžných AI volání konverzace uchovává celý kontext.

**Vrací:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Jedna [IAIConversation](../../com.aspose.slides/iaiconversation) instance.
### close() {#close--}
```
public final void close()
```

Uvolní prostředky použité touto instancí.