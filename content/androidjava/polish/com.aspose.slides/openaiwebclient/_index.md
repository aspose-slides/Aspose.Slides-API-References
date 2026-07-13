---
title: OpenAIWebClient
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Wbudowany lekki klient sieciowy OpenAI
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

Wbudowany lekki klient sieciowy OpenAI
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Tworzy instancję klienta sieciowego OpenAI. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Tworzy instancję klienta sieciowego OpenAI. |
## Metody

| Metoda | Opis |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Wysyła instrukcję czatu do modelu AI przy użyciu zewnętrznie zarządzanej  instancji i zwraca wiadomość odpowiedzi na podaną instrukcję. |
| [createConversation()](#createConversation--) | Tworzy instancję konwersacji. |
| [close()](#close--) | Zwalnia zasoby używane przez tę instancję. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

Tworzy instancję klienta sieciowego OpenAI.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| model | java.lang.String | Model językowy OpenAI. Możliwe wartości: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Klucz API OpenAI |
| organizationId | java.lang.String | Identyfikator organizacji (opcjonalny) |

### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```

Tworzy instancję klienta sieciowego OpenAI.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| model | java.lang.String | Model językowy OpenAI. Możliwe wartości: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Klucz API OpenAI |
| organizationId | java.lang.String | Identyfikator organizacji (opcjonalny) |
| httpClient | java.net.HttpURLConnection | Zewnętrznie zarządzana instancja HttpURLConnection. |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

Wysyła instrukcję czatu do modelu AI przy użyciu zewnętrznie zarządzanej  instancji i zwraca wiadomość odpowiedzi na podaną instrukcję.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| instruction | java.lang.String | Instrukcja lub wiadomość do przetworzenia przez model AI |

**Zwraca:**
java.lang.String - Wiadomość wygenerowana przez model AI w odpowiedzi na podaną instrukcję.
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Tworzy instancję konwersacji. W przeciwieństwie do zwykłych wywołań AI, konwersacje zachowują cały kontekst.

**Zwraca:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Instancję [IAIConversation](../../com.aspose.slides/iaiconversation).
### close() {#close--}
```
public final void close()
```

Zwalnia zasoby używane przez tę instancję.