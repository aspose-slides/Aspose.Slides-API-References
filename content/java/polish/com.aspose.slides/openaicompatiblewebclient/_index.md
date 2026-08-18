---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides dla Java – dokumentacja API
description: Wbudowana implementacja, która łączy się z dostawcą LLM kompatybilnym z OpenAI pod określonym adresem bazowym URL.
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

Wbudowana implementacja [IAIWebClient](../../com.aspose.slides/iaiwebclient) łącząca się z dostawcą LLM kompatybilnym z OpenAI pod określonym adresem bazowym URL.

## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Tworzy instancję klienta sieciowego kompatybilnego z OpenAI. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Tworzy instancję klienta sieciowego kompatybilnego z OpenAI, który używa zewnętrznie zarządzanego HttpURLConnection. |

## Metody

| Metoda | Opis |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Wysyła instrukcję czatu do modelu AI przy użyciu zewnętrznie zarządzanej instancji HttpURLConnection i zwraca wiadomość odpowiedzi na podaną instrukcję. |
| [createConversation()](#createConversation--) | Tworzy instancję rozmowy. |
| [dispose()](#dispose--) | Zwalnia zasoby używane przez tę instancję. |

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

Tworzy instancję klienta sieciowego kompatybilnego z OpenAI.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| model | java.lang.String | Nazwa modelu obsługiwanego przez dostawcę LLM. |
| apiKey | java.lang.String | Klucz API (token). |
| baseUrl | java.lang.String | Adres bazowy URL LLM kompatybilnego z OpenAI. |
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

Tworzy instancję klienta sieciowego kompatybilnego z OpenAI, który używa zewnętrznie zarządzanego HttpURLConnection. Dostarczony HttpURLConnection nie jest zwalniany przez tę instancję i pozostaje własnością wywołującego.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| model | java.lang.String | Nazwa modelu obsługiwanego przez dostawcę LLM. |
| apiKey | java.lang.String | Klucz API (token). |
| baseUrl | java.lang.String | Adres bazowy URL LLM kompatybilnego z OpenAI. |
| httpClient | java.net.HttpURLConnection | Instancja zewnętrznie zarządzanego HttpURLConnection. |
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

Wysyła instrukcję czatu do modelu AI przy użyciu zewnętrznie zarządzanej instancji HttpURLConnection i zwraca wiadomość odpowiedzi na podaną instrukcję.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| instruction | java.lang.String | Instrukcja lub wiadomość do przetworzenia przez model AI. |

**Zwraca:**
java.lang.String - Wiadomość wygenerowana przez model AI w odpowiedzi na podaną instrukcję.

### createConversation() {#createConversation--}
```
public final IIAConversation createConversation()
```}

Tworzy instancję rozmowy. W przeciwieństwie do zwykłych wywołań AI, rozmowy zachowują pełny kontekst.

**Zwraca:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Instancja [IAIConversation](../../com.aspose.slides/iaiconversation).

### dispose() {#dispose--}
```
public final void dispose()
```

Zwalnia zasoby używane przez tę instancję.