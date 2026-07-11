---
title: OpenAIWebClient
second_title: Aspose.Slides dla Java – odniesienie API
description: Wbudowana implementacja, która łączy się z API OpenAI.
type: docs
url: /pl/com.aspose.slides/openaiwebclient/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

Wbudowana [IAIWebClient](../../com.aspose.slides/iaiwebclient) implementacja łącząca się z API OpenAI.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Tworzy instancję klienta internetowego OpenAI. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Tworzy instancję klienta internetowego OpenAI używającego zewnętrznie zarządzanego HttpClient. |
## Metody

| Metoda | Opis |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Tworzy instancję konwersacji. |
| [close()](#close--) | Zwalnia zasoby używane przez tę instancję. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

Tworzy instancję klienta internetowego OpenAI.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| model | java.lang.String | Model językowy OpenAI. Dostępne wartości: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Klucz API OpenAI. |
| organizationId | java.lang.String | Identyfikator organizacji (opcjonalny). |

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

Tworzy instancję klienta internetowego OpenAI używającego zewnętrznie zarządzanego HttpClient. Dostarczony HttpClient nie jest zwalniany przez tę instancję i pozostaje własnością wywołującego.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| model | java.lang.String | Model językowy OpenAI. Dostępne wartości: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Klucz API OpenAI |
| organizationId | java.lang.String | Identyfikator organizacji (opcjonalny) |
| httpClient | java.net.HttpURLConnection | Instancja HttpClient zarządzana zewnętrznie |

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

Wysyła instrukcję czatu do modelu AI przy użyciu dostarczonej instancji HttpConnection i zwraca wiadomość odpowiedzi na podaną instrukcję.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Zwraca:**
java.lang.String
### createConversation() {#createConversation--}
```
public final IIAConversation createConversation()
```

Tworzy instancję konwersacji. W przeciwieństwie do standardowych wywołań AI, konwersacje zachowują cały kontekst.

**Zwraca:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Instancja [IAIConversation](../../com.aspose.slides/iaiconversation).
### close() {#close--}
```
public final void close()
```

Zwalnia zasoby używane przez tę instancję.