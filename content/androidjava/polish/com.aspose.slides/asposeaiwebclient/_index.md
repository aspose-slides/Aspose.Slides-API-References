---
title: AsposeAIWebClient
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Wbudowana implementacja łącząca się z własnym LLM firmy Aspose.
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

Wbudowana [IAIWebClient](../../com.aspose.slides/iaiwebclient) implementacja łącząca się z własnym LLM firmy Aspose. Jest to domyślny klient używany przez konstruktor bezparametrowy SlidesAIAgent().

## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Tworzy instancję klienta sieciowego Aspose AI, który łączy się z domyślnym końcowym punktem Aspose LLM. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Tworzy instancję klienta sieciowego Aspose AI, który łączy się z domyślnym końcowym punktem Aspose LLM przy użyciu zewnętrznie zarządzanego HttpURLConnection. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Tworzy instancję klienta sieciowego Aspose AI, który łączy się z niestandardowym adresem URL końcowego punktu. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Tworzy instancję klienta sieciowego Aspose AI, który łączy się z niestandardowym adresem URL końcowego punktu przy użyciu zewnętrznie zarządzanego HttpURLConnection. |

## Metody

| Metoda | Opis |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Wysyła instrukcję czatu do modelu AI i zwraca wiadomość odpowiedzi na podaną instrukcję. |
| [createConversation()](#createConversation--) | Tworzy instancję rozmowy. |
| [dispose()](#dispose--) | Zwalnia zasoby używane przez tę instancję. |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Tworzy instancję klienta sieciowego Aspose AI, który łączy się z domyślnym końcowym punktem Aspose LLM. Jest to klient używany przez konstruktor bezparametrowy SlidesAIAgent(), więc tworzenie go ręcznie jest wymagane tylko wtedy, gdy przekazujemy klienta bezpośrednio do konstruktora SlidesAIAgent(IAIWebClient).

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

Tworzy instancję klienta sieciowego Aspose AI, który łączy się z domyślnym końcowym punktem Aspose LLM przy użyciu zewnętrznie zarządzanego HttpURLConnection. Dostarczony HttpURLConnection nie jest zwalniany przez tę instancję i pozostaje własnością wywołującego.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Instancja HttpURLConnection zarządzana zewnętrznie. |
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

Tworzy instancję klienta sieciowego Aspose AI, który łączy się z niestandardowym adresem URL końcowego punktu. Użyj tego przeciążenia, gdy posiadasz URL dostarczony przez zespół Aspose.Slides; w przeciwnym razie użyj przeciążenia AsposeAIWebClient() z domyślnym URL.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| url | java.lang.String | Adres URL końcowego punktu Aspose LLM, dostarczony przez zespół Aspose.Slides. |
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

Tworzy instancję klienta sieciowego Aspose AI, który łączy się z niestandardowym adresem URL końcowego punktu przy użyciu zewnętrznie zarządzanego HttpURLConnection. Dostarczony HttpURLConnection nie jest zwalniany przez tę instancję i pozostaje własnością wywołującego. Użyj tego przeciążenia, gdy posiadasz URL dostarczony przez zespół Aspose.Slides i chcesz podać własny HttpURLConnection; jeśli potrzebujesz własnego HttpURLConnection tylko z domyślnym URL, użyj przeciążenia AsposeAIWebClient(HttpURLConnection).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| url | java.lang.String | Adres URL końcowego punktu Aspose LLM, dostarczony przez zespół Aspose.Slides. |
| httpClient | java.net.HttpURLConnection | Instancja HttpURLConnection zarządzana zewnętrznie. |
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
java.lang.String – Wiadomość wygenerowana przez model AI w odpowiedzi na podaną instrukcję.

### createConversation() {#createConversation--}
```
public final IIAConversation createConversation()
```

Tworzy instancję rozmowy. W przeciwieństwie do zwykłych wywołań AI, rozmowy zachowują cały kontekst.

**Zwraca:**
[IAIConversation](../../com.aspose.slides/iaiconversation) – An [IAIConversation](../../com.aspose.slides/iaiconversation) instance.

### dispose() {#dispose--}
```
public final void dispose()
```

Zwalnia zasoby używane przez tę instancję.