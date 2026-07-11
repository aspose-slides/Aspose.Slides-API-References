---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides για την Αναφορά API της Java
description: Μια ενσωματωμένη υλοποίηση που συνδέεται με έναν προμηθευτή LLM συμβατό με OpenAI σε καθορισμένο βασικό URL.
type: docs
url: /el/com.aspose.slides/openaicompatiblewebclient/
---
**Κληρονομιά:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

Μια ενσωματωμένη [IAIWebClient](../../com.aspose.slides/iaiwebclient) υλοποίηση που συνδέεται σε έναν προμηθευτή LLM συμβατό με OpenAI σε καθορισμένο βασικό URL.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Δημιουργεί μια παρουσία του OpenAI-compatible web client. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Δημιουργεί μια παρουσία του OpenAI-compatible web client που χρησιμοποιεί ένα εξωτερικά διαχειριζόμενο  HttpClient . |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Δημιουργεί μια παρουσία συνομιλίας. |
| [dispose()](#dispose--) | Απελευθερώνει τους πόρους που χρησιμοποιούνται από αυτή την παρουσία. |
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

Δημιουργεί μια παρουσία του OpenAI-compatible web client.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| model | java.lang.String | Όνομα μοντέλου που υποστηρίζεται από τον προμηθευτή LLM. |
| apiKey | java.lang.String | Κλειδί API (token). |
| baseUrl | java.lang.String | Βασικό URL του OpenAI-compatible LLM. |
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

Δημιουργεί μια παρουσία του OpenAI-compatible web client που χρησιμοποιεί ένα εξωτερικά διαχειριζόμενο  HttpClient . Ο παρεχόμενος  HttpClient  δεν διαγράφεται από αυτή την παρουσία και παραμένει στην ιδιοκτησία του καλούντος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| model | java.lang.String | Όνομα μοντέλου που υποστηρίζεται από τον προμηθευτή LLM. |
| apiKey | java.lang.String | Κλειδί API (token). |
| baseUrl | java.lang.String | Βασικό URL του OpenAI-compatible LLM. |
| httpClient | java.net.HttpURLConnection | Μια εξωτερικά διαχειριζόμενη  HttpClient  παρουσία. |
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

Στέλνει μια εντολή συνομιλίας στο μοντέλο AI χρησιμοποιώντας μια παρεχόμενη παρουσία HttpConnection και επιστρέφει το μήνυμα απόκρισης στην δεδομένη εντολή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Επιστρέφει:**
java.lang.String
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Δημιουργεί μια παρουσία συνομιλίας. Σε αντίθεση με τις κανονικές κλήσεις AI, οι συνομιλίες διατηρούν ολόκληρο το πλαίσιο.

**Επιστρέφει:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Μία [IAIConversation](../../com.aspose.slides/iaiconversation) παρουσία.
### dispose() {#dispose--}
```
public final void dispose()
```

Απελευθερώνει τους πόρους που χρησιμοποιούνται από αυτή την παρουσία.