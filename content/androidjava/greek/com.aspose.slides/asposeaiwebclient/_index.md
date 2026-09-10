---
title: AsposeAIWebClient
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Μία ενσωματωμένη υλοποίηση που συνδέεται με το δικό της LLM της Aspose.
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

Μία ενσωματωμένη [IAIWebClient](../../com.aspose.slides/iaiwebclient) υλοποίηση που συνδέεται με το δικό της LLM της Aspose. Αυτό είναι ο προεπιλεγμένος πελάτης που χρησιμοποιείται από τον κατασκευαστή χωρίς παραμέτρους  SlidesAIAgent()  constructor.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Δημιουργεί μια παρουσία του Aspose AI web client που συνδέεται με το προεπιλεγμένο σημείο λήψης Aspose LLM. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Δημιουργεί μια παρουσία του Aspose AI web client που συνδέεται με το προεπιλεγμένο σημείο λήψης Aspose LLM χρησιμοποιώντας ένα εξωτερικά διαχειριζόμενο  HttpURLConnection . |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Δημιουργεί μια παρουσία του Aspose AI web client που συνδέεται με μια προσαρμοσμένη URL τελικού σημείου. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Δημιουργεί μια παρουσία του Aspose AI web client που συνδέεται με μια προσαρμοσμένη URL τελικού σημείου χρησιμοποιώντας ένα εξωτερικά διαχειριζόμενο  HttpURLConnection . |

## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Στέλνει μια εντολή συνομιλίας στο μοντέλο AI και επιστρέφει το μήνυμα απάντησης στην δοθείσα εντολή. |
| [createConversation()](#createConversation--) | Δημιουργεί μια παρουσία συνομιλίας. |
| [dispose()](#dispose--) | Απελευθερώνει τους πόρους που χρησιμοποιούνται από αυτήν την παρουσία. |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Δημιουργεί μια παρουσία του Aspose AI web client που συνδέεται με το προεπιλεγμένο σημείο λήψης Aspose LLM. Αυτός είναι ο πελάτης που χρησιμοποιείται από τον κατασκευαστή χωρίς παραμέτρους  SlidesAIAgent() , έτσι η ρητή δημιουργία του απαιτείται μόνο όταν περνιέται ο πελάτης απευθείας στον κατασκευαστή SlidesAIAgent(IAIWebClient)  constructor.

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

Δημιουργεί μια παρουσία του Aspose AI web client που συνδέεται με το προεπιλεγμένο σημείο λήψης Aspose LLM χρησιμοποιώντας ένα εξωτερικά διαχειριζόμενο  HttpURLConnection . Η παρεχόμενη  HttpURLConnection  δεν διαγράφεται από αυτήν την παρουσία και παραμένει στην ιδιοκτησία του καλούντος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Μία εξωτερικά διαχειριζόμενη  HttpURLConnection  παρουσία. |
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

Δημιουργεί μια παρουσία του Aspose AI web client που συνδέεται με μια προσαρμοσμένη URL τελικού σημείου. Χρησιμοποιήστε αυτήν την υπερφόρτωση όταν διαθέτετε μια URL που παρέχεται από την ομάδα Aspose.Slides· διαφορετικά, χρησιμοποιήστε την υπερφόρτωση  AsposeAIWebClient()  με την προεπιλεγμένη URL.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | java.lang.String | URL τελικού σημείου του Aspose LLM, που παρέχεται από την ομάδα Aspose.Slides. |
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

Δημιουργεί μια παρουσία του Aspose AI web client που συνδέεται με μια προσαρμοσμένη URL τελικού σημείου χρησιμοποιώντας ένα εξωτερικά διαχειριζόμενο  HttpURLConnection . Η παρεχόμενη  HttpURLConnection  δεν διαγράφεται από αυτήν την παρουσία και παραμένει στην ιδιοκτησία του καλούντος. Χρησιμοποιήστε αυτήν την υπερφόρτωση όταν διαθέτετε μια URL που παρέχεται από την ομάδα Aspose.Slides και θέλετε να παρέχετε το δικό σας  HttpURLConnection ; εάν χρειάζεστε μόνο το δικό σας  HttpURLConnection  με την προεπιλεγμένη URL, χρησιμοποιήστε την υπερφόρτωση  AsposeAIWebClient(HttpURLConnection)  αντί αυτού.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | java.lang.String | URL τελικού σημείου του Aspose LLM, που παρέχεται από την ομάδα Aspose.Slides. |
| httpClient | java.net.HttpURLConnection | Μία εξωτερικά διαχειριζόμενη  HttpURLConnection  παρουσία. |
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

Στέλνει μια εντολή συνομιλίας στο μοντέλο AI και επιστρέφει το μήνυμα απάντησης στην δοθείσα εντολή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| instruction | java.lang.String | Η εντολή ή το μήνυμα που θα επεξεργαστεί το μοντέλο AI. |

**Επιστρέφει:**
java.lang.String - Το μήνυμα που δημιουργήθηκε από το μοντέλο AI ως απάντηση στην δοθείσα εντολή.

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Δημιουργεί μια παρουσία συνομιλίας. Σε αντίθεση με τις κανονικές κλήσεις AI, οι συνομιλίες διατηρούν όλο το πλαίσιο.

**Επιστρέφει:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Μία [IAIConversation](../../com.aspose.slides/iaiconversation) παράσταση.

### dispose() {#dispose--}
```
public final void dispose()
```

Απελευθερώνει τους πόρους που χρησιμοποιούνται από αυτήν την παρουσία.