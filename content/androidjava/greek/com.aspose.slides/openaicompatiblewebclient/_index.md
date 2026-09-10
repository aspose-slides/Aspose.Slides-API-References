---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Μια ενσωματωμένη υλοποίηση που συνδέεται σε έναν παροχέα LLM συμβατό με OpenAI σε καθορισμένο base URL.
type: docs
url: /el/com.aspose.slides/openaicompatiblewebclient/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

Μία ενσωματωμένη [IAIWebClient](../../com.aspose.slides/iaiwebclient) υλοποίηση που συνδέεται σε έναν παροχέα LLM συμβατό με OpenAI σε καθορισμένο base URL.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Δημιουργεί ένα στιγμιότυπο του web client συμβατού με OpenAI. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Δημιουργεί ένα στιγμιότυπο του web client συμβατού με OpenAI που χρησιμοποιεί ένα εξωτερικά διαχειριζόμενο HttpURLConnection . |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Στέλνει μια οδηγία συνομιλίας στο μοντέλο AI χρησιμοποιώντας μια εξωτερικά διαχειριζόμενη HttpURLConnection και επιστρέφει το μήνυμα απάντησης στην συγκεκριμένη οδηγία. |
| [createConversation()](#createConversation--) | Δημιουργεί μια παρουσία συζήτησης. |
| [dispose()](#dispose--) | Απελευθερώνει τους πόρους που χρησιμοποιούνται από αυτήν την παρουσία. |

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

Δημιουργεί ένα στιγμιότυπο του web client συμβατού με OpenAI.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| model | java.lang.String | Το όνομα του μοντέλου που υποστηρίζεται από τον παροχέα LLM. |
| apiKey | java.lang.String | Κλειδί API (token). |
| baseUrl | java.lang.String | Base URL του LLM συμβατού με OpenAI. |
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

Δημιουργεί ένα στιγμιότυπο του web client συμβατού με OpenAI που χρησιμοποιεί ένα εξωτερικά διαχειριζόμενο HttpURLConnection . Το παρεχόμενο HttpURLConnection δεν διαχειρίζεται από αυτήν την παρουσία και παραμένει υπό τον κάτοχο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| model | java.lang.String | Το όνομα του μοντέλου που υποστηρίζεται από τον παροχέα LLM. |
| apiKey | java.lang.String | Κλειδί API (token). |
| baseUrl | java.lang.String | Base URL του LLM συμβατού με OpenAI. |
| httpClient | java.net.HttpURLConnection | Μια εξωτερικά διαχειριζόμενη HttpURLConnection. |
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

Στέλνει μια οδηγία συνομιλίας στο μοντέλο AI χρησιμοποιώντας μια εξωτερικά διαχειριζόμενη HttpURLConnection και επιστρέφει το μήνυμα απάντησης στην συγκεκριμένη οδηγία.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| instruction | java.lang.String | Η οδηγία ή το μήνυμα που θα επεξεργαστεί το μοντέλο AI. |

**Επιστρέφει:**
java.lang.String - Το μήνυμα που δημιουργήθηκε από το μοντέλο AI ως απάντηση στην δεδομένη οδηγία.

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Δημιουργεί μια παρουσία συζήτησης. Σε αντίθεση με τις κανονικές κλήσεις AI, οι συζητήσεις διατηρούν όλο το πλαίσιο.

**Επιστρέφει:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Μια [IAIConversation](../../com.aspose.slides/iaiconversation) παρουσία.

### dispose() {#dispose--}
```
public final void dispose()
```

Απελευθερώνει τους πόρους που χρησιμοποιούνται από αυτήν την παρουσία.