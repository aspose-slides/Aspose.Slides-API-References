---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides dla Java – Dokumentacja API
description: Wbudowana implementacja, która łączy się z dostawcą LLM zgodnym z OpenAI pod określonym podstawowym adresem URL.
type: docs
url: /pl/com.aspose.slides/openaicompatiblewebclient/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

Wbudowana [IAIWebClient](../../com.aspose.slides/iaiwebclient) implementacja, która łączy się z dostawcą LLM zgodnym z OpenAI pod określonym podstawowym adresem URL.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Tworzy instancję klienta internetowego zgodnego z OpenAI. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Tworzy instancję klienta internetowego zgodnego z OpenAI, który używa zewnętrznie zarządzanego HttpClient. |
## Metody

| Metoda | Opis |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Tworzy instancję konwersacji. |
| [dispose()](#dispose--) | Zwalnia zasoby używane przez tę instancję. |
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

Tworzy instancję klienta internetowego zgodnego z OpenAI.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| model | java.lang.String | Nazwa modelu obsługiwanego przez dostawcę LLM. |
| apiKey | java.lang.String | Klucz API (token). |
| baseUrl | java.lang.String | Podstawowy adres URL zgodnego z OpenAI LLM. |
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

Tworzy instancję klienta internetowego zgodnego z OpenAI, który używa zewnętrznie zarządzanego HttpClient. Dostarczony HttpClient nie jest zwalniany przez tę instancję i pozostaje własnością wywołującego.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| model | java.lang.String | Nazwa modelu obsługiwanego przez dostawcę LLM. |
| apiKey | java.lang.String | Klucz API (token). |
| baseUrl | java.lang.String | Podstawowy adres URL zgodnego z OpenAI LLM. |
| httpClient | java.net.HttpURLConnection | Instancja HttpClient zarządzana zewnętrznie. |
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

Wysyła instrukcję czatu do modelu AI przy użyciu dostarczonej instancji HttpConnection i zwraca wiadomość odpowiedzi na podaną instrukcję.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Zwraca:**
java.lang.String
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Tworzy instancję konwersacji. W przeciwieństwie do standardowych wywołań AI, konwersacje zachowują cały kontekst.

**Zwraca:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Instancja [IAIConversation](../../com.aspose.slides/iaiconversation).
### dispose() {#dispose--}
```
public final void dispose()
```

Zwalnia zasoby używane przez tę instancję.