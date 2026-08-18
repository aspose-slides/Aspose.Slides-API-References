---
title: AsposeAIWebClient
second_title: Aspose.Slides dla Java - odniesienie API
description: Wbudowana implementacja, która łączy się z własnym LLM firmy Aspose.
type: docs
url: /pl/com.aspose.slides/asposeaiwebclient/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

Wbudowana implementacja [IAIWebClient](../../com.aspose.slides/iaiwebclient) łączy się z własnym LLM firmy Aspose. Jest to domyślny klient używany przez konstruktor bezparametrowy  SlidesAIAgent()  .

## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Tworzy instancję klienta webowego Aspose AI, który łączy się z domyślnym punktem końcowym Aspose LLM. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Tworzy instancję klienta webowego Aspose AI, który łączy się z domyślnym punktem końcowym Aspose LLM przy użyciu zewnętrznie zarządzanego  HttpURLConnection . |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Tworzy instancję klienta webowego Aspose AI, który łączy się z niestandardowym URL punktu końcowego. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Tworzy instancję klienta webowego Aspose AI, który łączy się z niestandardowym URL punktu końcowego przy użyciu zewnętrznie zarządzanego  HttpURLConnection . |

## Metody

| Metoda | Opis |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Wysyła instrukcję czatu do modelu AI i zwraca wiadomość odpowiedzi na podaną instrukcję. |
| [createConversation()](#createConversation--) | Tworzy instancję konwersacji. |
| [dispose()](#dispose--) | Zwalnia zasoby używane przez tę instancję. |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Tworzy instancję klienta webowego Aspose AI, który łączy się z domyślnym punktem końcowym Aspose LLM. Jest to klient używany przez konstruktor bezparametrowy  SlidesAIAgent() , więc tworzenie go jawnie jest wymagane tylko wtedy, gdy klient jest przekazywany bezpośrednio do konstruktora  SlidesAIAgent(IAIWebClient) .

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

Tworzy instancję klienta webowego Aspose AI, który łączy się z domyślnym punktem końcowym Aspose LLM przy użyciu zewnętrznie zarządzanego  HttpURLConnection . Dostarczony  HttpURLConnection  nie jest zwalniany przez tę instancję i pozostaje własnością wywołującego.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Instancja zewnętrznie zarządzanego  HttpURLConnection . |

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

Tworzy instancję klienta webowego Aspose AI, który łączy się z niestandardowym URL punktu końcowego. Użyj tego przeciążenia, gdy masz URL dostarczony przez zespół Aspose.Slides; w przeciwnym razie użyj przeciążenia  AsposeAIWebClient()  z domyślnym URL.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| url | java.lang.String | URL punktu końcowego Aspose LLM, dostarczony przez zespół Aspose.Slides. |

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

Tworzy instancję klienta webowego Aspose AI, który łączy się z niestandardowym URL punktu końcowego przy użyciu zewnętrznie zarządzanego  HttpURLConnection . Dostarczony  HttpURLConnection  nie jest zwalniany przez tę instancję i pozostaje własnością wywołującego. Użyj tego przeciążenia, gdy masz URL dostarczony przez zespół Aspose.Slides i chcesz dostarczyć własny  HttpURLConnection ; jeśli potrzebujesz własnego  HttpURLConnection  z domyślnym URL, użyj przeciążenia  AsposeAIWebClient(HttpURLConnection)  zamiast tego.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| url | java.lang.String | URL punktu końcowego Aspose LLM, dostarczony przez zespół Aspose.Slides. |
| httpClient | java.net.HttpURLConnection | Instancja zewnętrznie zarządzanego  HttpURLConnection . |

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

Wysyła instrukcję czatu do modelu AI i zwraca wiadomość odpowiedzi na podaną instrukcję.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| instruction | java.lang.String | Instrukcja lub wiadomość do przetworzenia przez model AI. |

**Zwraca:**
java.lang.String - Wiadomość wygenerowana przez model AI w odpowiedzi na podaną instrukcję.

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Tworzy instancję konwersacji. W przeciwieństwie do zwykłych wywołań AI, konwersacje zachowują cały kontekst.

**Zwraca:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - An [IAIConversation](../../com.aspose.slides/iaiconversation) instance.

### dispose() {#dispose--}
```
public final void dispose()
```

Zwalnia zasoby używane przez tę instancję.