---
title: OpenAIWebClient
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Μία ενσωματωμένη εφαρμογή που συνδέεται με το API της OpenAI.
type: docs
url: /el/com.aspose.slides/openaiwebclient/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

Μια ενσωματωμένη υλοποίηση [IAIWebClient](../../com.aspose.slides/iaiwebclient) που συνδέεται με το API της OpenAI.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Δημιουργεί μια παρουσία του πελάτη web OpenAI. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Δημιουργεί μια παρουσία του πελάτη web OpenAI που χρησιμοποιεί ένα εξωτερικά διαχειριζόμενο HttpClient . |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Δημιουργεί μια παρουσία συνομιλίας. |
| [close()](#close--) | Απελευθερώνει τους πόρους που χρησιμοποιούνται από αυτήν την παρουσία. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```


Δημιουργεί μια παρουσία του πελάτη web OpenAI.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| model | java.lang.String | Μοντέλο γλώσσας OpenAI. Πιθανές τιμές: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Κλειδί API OpenAI. |
| organizationId | java.lang.String | Αναγνωριστικό Οργανισμού (προαιρετικό). |

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


Δημιουργεί μια παρουσία του πελάτη web OpenAI που χρησιμοποιεί ένα εξωτερικά διαχειριζόμενο HttpClient . Ο παρεχόμενος HttpClient δεν διατίθεται από αυτήν την παρουσία και παραμένει στην ιδιοκτησία του καλούντος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| model | java.lang.String | Μοντέλο γλώσσας OpenAI. Πιθανές τιμές: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Κλειδί API OpenAI |
| organizationId | java.lang.String | Αναγνωριστικό Οργανισμού (προαιρετικό) |
| httpClient | java.net.HttpURLConnection | Μια εξωτερικά διαχειριζόμενη παρουσία HttpClient |

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


Δημιουργεί μια παρουσία συνομιλίας. Σε αντίθεση με τις συνηθισμένες κλήσεις AI, οι συνομιλίες διατηρούν όλο το πλαίσιο.

**Επιστρέφει:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Μια παρουσία [IAIConversation](../../com.aspose.slides/iaiconversation).
### close() {#close--}
```
public final void close()
```


Απελευθερώνει τους πόρους που χρησιμοποιούνται από αυτήν την παρουσία.