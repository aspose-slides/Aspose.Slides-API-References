---
title: AsposeAIWebClient
second_title: Aspose.Slides dla Java - Referencja API
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

Wbudowana [IAIWebClient](../../com.aspose.slides/iaiwebclient) implementacja, która łączy się z własnym LLM firmy Aspose. Jest to domyślny klient używany przez konstruktor SlidesAIAgent() bez parametrów.

## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Tworzy instancję klienta sieciowego Aspose AI, który łączy się z domyślnym punktem końcowym Aspose LLM. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Tworzy instancję klienta sieciowego Aspose AI, który łączy się z domyślnym punktem końcowym Aspose LLM przy użyciu zarządzanego zewnętrznie HttpClient. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Tworzy instancję klienta sieciowego Aspose AI, który łączy się z niestandardowym adresem URL punktu końcowego. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Tworzy instancję klienta sieciowego Aspose AI, który łączy się z niestandardowym adresem URL punktu końcowego przy użyciu zarządzanego zewnętrznie HttpClient. |

## Metody

| Metoda | Opis |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Tworzy instancję konwersacji. |
| [dispose()](#dispose--) | Zwalnia zasoby używane przez tę instancję. |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Tworzy instancję klienta sieciowego Aspose AI, który łączy się z domyślnym punktem końcowym Aspose LLM. Jest to klient używany przez konstruktor SlidesAIAgent() bez parametrów, więc tworzenie go explicite jest wymagane jedynie w przypadku przekazania klienta bezpośrednio do konstruktora SlidesAIAgent(IAIWebClient)  bezpośrednio.

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

Tworzy instancję klienta sieciowego Aspose AI, który łączy się z domyślnym punktem końcowym Aspose LLM przy użyciu zarządzanego zewnętrznie HttpClient. Dostarczony HttpClient nie jest zwalniany przez tę instancję i pozostaje własnością wywołującego.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Zarządzana zewnętrznie instancja HttpClient. |

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

Tworzy instancję klienta sieciowego Aspose AI, który łączy się z niestandardowym adresem URL punktu końcowego. Użyj tego przeciążenia, gdy posiadasz URL dostarczony przez zespół Aspose.Slides; w przeciwnym razie użyj przeciążenia AsposeAIWebClient() z domyślnym URL.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| url | java.lang.String | Adres URL punktu końcowego Aspose LLM, dostarczony przez zespół Aspose.Slides. |

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

Tworzy instancję klienta sieciowego Aspose AI, który łączy się z niestandardowym adresem URL punktu końcowego przy użyciu zarządzanego zewnętrznie HttpClient. Dostarczony HttpClient nie jest zwalniany przez tę instancję i pozostaje własnością wywołującego. Użyj tego przeciążenia, gdy posiadasz URL dostarczony przez zespół Aspose.Slides i chcesz podać własny HttpClient; jeśli potrzebujesz własny HttpClient tylko z domyślnym URL, użyj przeciążenia AsposeAIWebClient(HttpClient).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| url | java.lang.String | Adres URL punktu końcowego Aspose LLM, dostarczony przez zespół Aspose.Slides. |
| httpClient | java.net.HttpURLConnection | Zarządzana zewnętrznie instancja HttpClient. |

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

Tworzy instancję konwersacji. W przeciwieństwie do zwykłych wywołań AI, konwersacje zachowują cały kontekst.

**Zwraca:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - An [IAIConversation](../../com.aspose.slides/iaiconversation) instance.

### dispose() {#dispose--}
```
public final void dispose()
```

Zwalnia zasoby używane przez tę instancję.