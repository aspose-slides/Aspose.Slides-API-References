---
title: AsposeAIWebClient
second_title: Αναφορά API Aspose.Slides για Java
description: Μια ενσωματωμένη υλοποίηση που συνδέεται με το δικό της LLM της Aspose.
type: docs
url: /el/com.aspose.slides/asposeaiwebclient/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

Μια ενσωματωμένη υλοποίηση [IAIWebClient](../../com.aspose.slides/iaiwebclient) που συνδέεται με το δικό της LLM της Aspose. Αυτός είναι ο προεπιλεγμένος πελάτης που χρησιμοποιείται από τον κατασκευαστή χωρίς παραμέτρων  SlidesAIAgent()  .

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Δημιουργεί μια παρουσία του Aspose AI web client που συνδέεται με το προεπιλεγμένο άκρο Aspose LLM. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Δημιουργεί μια παρουσία του Aspose AI web client που συνδέεται με το προεπιλεγμένο άκρο Aspose LLM χρησιμοποιώντας ένα εξωτερικά διαχειριζόμενο  HttpURLConnection . |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Δημιουργεί μια παρουσία του Aspose AI web client που συνδέεται με μια προσαρμοσμένη διεύθυνση URL άκρου. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Δημιουργεί μια παρουσία του Aspose AI web client που συνδέεται με μια προσαρμοσμένη διεύθυνση URL άκρου χρησιμοποιώντας ένα εξωτερικά διαχειριζόμενο  HttpURLConnection . |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Στέλνει μια οδηγία συνομιλίας στο μοντέλο AI και επιστρέφει το μήνυμα απάντησης στην δεδομένη οδηγία. |
| [createConversation()](#createConversation--) | Δημιουργεί μια παρουσία συνομιλίας. |
| [dispose()](#dispose--) | Απελευθερώνει τους πόρους που χρησιμοποιούνται από αυτήν την παρουσία. |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Δημιουργεί μια παρουσία του Aspose AI web client που συνδέεται με το προεπιλεγμένο άκρο Aspose LLM. Αυτή είναι η πελάτης που χρησιμοποιείται από τον κατασκευαστή χωρίς παραμέτρους  SlidesAIAgent() , οπότε η ρητή δημιουργία του είναι απαραίτητη μόνο όταν περνάτε τον πελάτη στον κατασκευαστή  SlidesAIAgent(IAIWebClient)  απευθείας.

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

Δημιουργεί μια παρουσία του Aspose AI web client που συνδέεται με το προεπιλεγμένο άκρο Aspose LLM χρησιμοποιώντας ένα εξωτερικά διαχειριζόμενο  HttpURLConnection . Το παρεχόμενο  HttpURLConnection  δεν διαχειρίζεται από αυτήν την παρουσία και παραμένει στην κατοχή του καλούντος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Μια εξωτερικά διαχειριζόμενη  HttpURLConnection  παρουσία. |

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

Δημιουργεί μια παρουσία του Aspose AI web client που συνδέεται με μια προσαρμοσμένη διεύθυνση URL άκρου. Χρησιμοποιήστε αυτήν την υπερφόρτωση όταν έχετε μια URL που παρέχεται από την ομάδα Aspose.Slides· διαφορετικά, χρησιμοποιήστε την υπερφόρτωση  AsposeAIWebClient()  με την προεπιλεγμένη URL.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | java.lang.String | Διεύθυνση URL άκρου του Aspose LLM, που παρέχεται από την ομάδα Aspose.Slides. |

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

Δημιουργεί μια παρουσία του Aspose AI web client που συνδέεται με μια προσαρμοσμένη διεύθυνση URL άκρου χρησιμοποιώντας ένα εξωτερικά διαχειριζόμενο  HttpURLConnection . Το παρεχόμενο  HttpURLConnection  δεν διαχειρίζεται από αυτήν την παρουσία και παραμένει στην κατοχή του καλούντος. Χρησιμοποιήστε αυτήν την υπερφόρτωση όταν έχετε μια URL που παρέχεται από την ομάδα Aspose.Slides και θέλετε να παρέχετε το δικό σας  HttpURLConnection· αν χρειάζεστε μόνο το δικό σας  HttpURLConnection  με την προεπιλεγμένη URL, χρησιμοποιήστε την υπερφόρτωση  AsposeAIWebClient(HttpURLConnection)  αντ' αυτού.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | java.lang.String | Διεύθυνση URL άκρου του Aspose LLM, που παρέχεται από την ομάδα Aspose.Slides. |
| httpClient | java.net.HttpURLConnection | Μια εξωτερικά διαχειριζόμενη  HttpURLConnection  παρουσία. |

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

Στέλνει μια οδηγία συνομιλίας στο μοντέλο AI και επιστρέφει το μήνυμα απάντησης στην δοθείσα οδηγία.

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

Δημιουργεί μια παρουσία συνομιλίας. Σε αντίθεση με τις κανονικές κλήσεις AI, οι συνομιλίες διατηρούν όλο το συμφραζόμενο.

**Επιστρέφει:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Μία [IAIConversation](../../com.aspose.slides/iaiconversation) παρουσία.

### dispose() {#dispose--}
```
public final void dispose()
```

Απελευθερώνει τους πόρους που χρησιμοποιούνται από αυτήν την παρουσία.