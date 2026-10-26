---
title: OpenAICompatibleWebClient
second_title: Αναφορά API Aspose.Slides για Java
description: Μια ενσωματωμένη υλοποίηση που συνδέεται με έναν παροχέα LLM συμβατό με OpenAI σε καθορισμένη βασική διεύθυνση URL.
type: docs
url: /el/com.aspose.slides/openaicompatiblewebclient/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IIAWebClient, System.IDisposable
```

Μια ενσωματωμένη [IAIWebClient](../../com.aspose.slides/iaiwebclient) υλοποίηση που συνδέεται με έναν προμηθευτή LLM συμβατό με OpenAI σε καθορισμένη βασική διεύθυνση URL.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Δημιουργεί ένα στιγμιότυπο του OpenAI-compatible web client. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Δημιουργεί ένα στιγμιότυπο του OpenAI-compatible web client που χρησιμοποιεί εξωτερικά διαχειριζόμενο  HttpURLConnection . |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Στέλνει μια εντολή chat στο μοντέλο AI χρησιμοποιώντας εξωτερικά διαχειριζόμενο HttpURLConnection instance και επιστρέφει το μήνυμα απάντησης στην δεδομένη εντολή. |
| [createConversation()](#createConversation--) | Δημιουργεί ένα στιγμιότυπο συνομιλίας. |
| [dispose()](#dispose--) | Απελευθερώνει τους πόρους που χρησιμοποιούνται από αυτό το στιγμιότυπο. |

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

Δημιουργεί ένα στιγμιότυπο του OpenAI-compatible web client.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| model | java.lang.String | Όνομα μοντέλου που υποστηρίζεται από τον πάροχο LLM. |
| apiKey | java.lang.String | Κλειδί API (token). |
| baseUrl | java.lang.String | Βασική διεύθυνση URL του OpenAI-compatible LLM. |
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

Δημιουργεί ένα στιγμιότυπο του OpenAI-compatible web client που χρησιμοποιεί εξωτερικά διαχειριζόμενο  HttpURLConnection . Το παρεχόμενο  HttpURLConnection  δεν διαχειρίζεται από αυτό το στιγμιότυπο και παραμένει στην ιδιοκτησία του καλούντος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| model | java.lang.String | Όνομα μοντέλου που υποστηρίζεται από τον πάροχο LLM. |
| apiKey | java.lang.String | Κλειδί API (token). |
| baseUrl | java.lang.String | Βασική διεύθυνση URL του OpenAI-compatible LLM. |
| httpClient | java.net.HttpURLConnection | Μια εξωτερικά διαχειριζόμενη  HttpURLConnection  παρουσία. |
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

Στέλνει μια εντολή chat στο μοντέλο AI χρησιμοποιώντας εξωτερικά διαχειριζόμενο HttpURLConnection instance και επιστρέφει το μήνυμα απάντησης στην δεδομένη εντολή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| instruction | java.lang.String | Η εντολή ή το μήνυμα που θα επεξεργαστεί το μοντέλο AI. |

**Επιστρέφει:**
java.lang.String - Το μήνυμα που δημιουργείται από το μοντέλο AI ως απάντηση στην δεδομένη εντολή.

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Δημιουργεί ένα στιγμιότυπο συνομιλίας. Σε αντίθεση με τις κανονικές κλήσεις AI, οι συνομιλίες διατηρούν όλο το περιεχόμενο.

**Επιστρέφει:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Ένα [IAIConversation](../../com.aspose.slides/iaiconversation) αντικείμενο.

### dispose() {#dispose--}
```
public final void dispose()
```

Απελευθερώνει τους πόρους που χρησιμοποιούνται από αυτό το στιγμιότυπο.