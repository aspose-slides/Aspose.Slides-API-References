---
title: OpenAIWebClient
second_title: Aspose.Slides για την Αναφορά API της Java
description: Μια ενσωματωμένη υλοποίηση που συνδέεται με το OpenAI API.
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

Μία ενσωματωμένη [IAIWebClient](../../com.aspose.slides/iaiwebclient) υλοποίηση που συνδέεται με το OpenAI API.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Δημιουργεί ένα στιγμιότυπο του πελάτη web OpenAI. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Δημιουργεί ένα στιγμιότυπο του πελάτη web OpenAI που χρησιμοποιεί εξωτερικά διαχειριζόμενο HttpClient. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Δημιουργεί μια παρουσία συνομιλίας. |
| [close()](#close--) | Αποδεσμεύει τους πόρους που χρησιμοποιεί αυτή η παρουσία. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

Δημιουργεί ένα στιγμιότυπο του πελάτη web OpenAI.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| model | java.lang.String | Μοντέλο γλώσσας OpenAI. Πιθανές τιμές: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Κλειδί API OpenAI. |
| organizationId | java.lang.String | Αναγνωριστικό οργανισμού (προαιρετικό). |
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

Δημιουργεί ένα στιγμιότυπο του πελάτη web OpenAI που χρησιμοποιεί εξωτερικά διαχειριζόμενο HttpClient. Ο παρεχόμενος HttpClient δεν διατίθεται από αυτή την παρουσία και παραμένει ιδιοκτησία του καλούντος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| model | java.lang.String | Μοντέλο γλώσσας OpenAI. Πιθανές τιμές: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Κλειδί API OpenAI |
| organizationId | java.lang.String | Αναγνωριστικό οργανισμού (προαιρετικό) |
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

Αποστέλλει μια εντολή συνομιλίας στο μοντέλο AI χρησιμοποιώντας μια παρεχόμενη παρουσία HttpConnection και επιστρέφει το μήνυμα απόκρισης στην εντολή.

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

Δημιουργεί μια παρουσία συνομιλίας. Σε αντίθεση με τις κανονικές κλήσεις AI, οι συνομιλίες διατηρούν όλο το πλαίσιο.

**Επιστρέφει:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Μια [IAIConversation](../../com.aspose.slides/iaiconversation) παράδειγμα.
### close() {#close--}
```
public final void close()
```

Αποδεσμεύει τους πόρους που χρησιμοποιεί αυτή η παρουσία.