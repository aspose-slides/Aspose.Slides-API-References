---
title: OpenAIWebClient
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Ενσωματωμένος ελαφρύς πελάτης ιστού OpenAI
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

Ενσωματωμένος ελαφρύς πελάτης ιστού OpenAI
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Δημιουργεί μια παρουσία του πελάτη Web OpenAI. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Δημιουργεί μια παρουσία του πελάτη Web OpenAI. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Στέλνει μια οδηγία συνομιλίας στο μοντέλο AI χρησιμοποιώντας μια εξωτερικά διαχειριζόμενη  παρουσία και επιστρέφει το μήνυμα απάντησης στην δοθείσα οδηγία. |
| [createConversation()](#createConversation--) | Δημιουργεί μια παρουσία συνομιλίας. |
| [close()](#close--) | Αποδεσμεύει τους πόρους που χρησιμοποιούνται από αυτήν την παρουσία. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

Δημιουργεί μια παρουσία του πελάτη Web OpenAI.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| model | java.lang.String | Μοντέλο γλώσσας OpenAI. Πιθανές τιμές: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Κλειδί API OpenAI |
| organizationId | java.lang.String | Αναγνωριστικό οργανισμού (προαιρετικό) |

### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```

Δημιουργεί μια παρουσία του πελάτη Web OpenAI.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| model | java.lang.String | Μοντέλο γλώσσας OpenAI. Πιθανές τιμές: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Κλειδί API OpenAI |
| organizationId | java.lang.String | Αναγνωριστικό οργανισμού (προαιρετικό) |
| httpClient | java.net.HttpURLConnection | Μια εξωτερικά διαχειριζόμενη παρουσία HttpURLConnection. |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

Στέλνει μια οδηγία συνομιλίας στο μοντέλο AI χρησιμοποιώντας μια εξωτερικά διαχειριζόμενη  παρουσία και επιστρέφει το μήνυμα απάντησης στην δοθείσα οδηγία.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| instruction | java.lang.String | Η οδηγία ή το μήνυμα που θα επεξεργαστεί το μοντέλο AI |

**Επιστρέφει:**
java.lang.String - Το μήνυμα που δημιουργείται από το μοντέλο AI ως απάντηση στην δοθείσα οδηγία.
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Δημιουργεί μια παρουσία συνομιλίας. Σε αντίθεση με τις κανονικές κλήσεις AI, οι συνομιλίες διατηρούν όλο το συμφραζόμενο.

**Επιστρέφει:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - An [IAIConversation](../../com.aspose.slides/iaiconversation) instance.
### close() {#close--}
```
public final void close()
```

Αποδεσμεύει τους πόρους που χρησιμοποιούνται από αυτήν την παρουσία.