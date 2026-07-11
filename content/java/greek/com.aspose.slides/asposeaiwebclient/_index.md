---
title: AsposeAIWebClient
second_title: Aspose.Slides για την Αναφορά API της Java
description: Μια ενσωματωμένη  υλοποίηση που συνδέεται με το δικό της LLM της Aspose.
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

Μία ενσωματωμένη [IAIWebClient](../../com.aspose.slides/iaiwebclient) υλοποίηση που συνδέεται με το δικό της LLM της Aspose. Αυτός είναι ο προεπιλεγμένος πελάτης που χρησιμοποιείται από τον κατασκευαστή SlidesAIAgent() χωρίς παραμέτρους.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Δημιουργεί ένα παράδειγμα του Aspose AI web client που συνδέεται στο προεπιλεγμένο τελικό σημείο Aspose LLM. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Δημιουργεί ένα παράδειγμα του Aspose AI web client που συνδέεται στο προεπιλεγμένο τελικό σημείο Aspose LLM χρησιμοποιώντας έναν εξωτερικά διαχειριζόμενο HttpClient. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Δημιουργεί ένα παράδειγμα του Aspose AI web client που συνδέεται σε ένα προσαρμοσμένο URL τελικού σημείου. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Δημιουργεί ένα παράδειγμα του Aspose AI web client που συνδέεται σε ένα προσαρμοσμένο URL τελικού σημείου χρησιμοποιώντας έναν εξωτερικά διαχειριζόμενο HttpClient. |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Δημιουργεί ένα παράδειγμα συνομιλίας. |
| [dispose()](#dispose--) | Απελευθερώνει τους πόρους που χρησιμοποιεί αυτό το παράδειγμα. |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Δημιουργεί ένα παράδειγμα του Aspose AI web client που συνδέεται στο προεπιλεγμένο τελικό σημείο Aspose LLM. Αυτός είναι ο πελάτης που χρησιμοποιείται από τον κατασκευαστή SlidesAIAgent() χωρίς παραμέτρους, επομένως η ρητή δημιουργία του απαιτείται μόνο όταν ο πελάτης περνιέται άμεσα στον κατασκευαστή SlidesAIAgent(IAIWebClient).

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

Δημιουργεί ένα παράδειγμα του Aspose AI web client που συνδέεται στο προεπιλεγμένο τελικό σημείο Aspose LLM χρησιμοποιώντας έναν εξωτερικά διαχειριζόμενο HttpClient. Ο παρεχόμενος HttpClient δεν διαγράφεται από αυτό το παράδειγμα και παραμένει στην ιδιοκτησία του καλούντος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Ένα εξωτερικά διαχειριζόμενο αντικείμενο HttpClient. |

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

Δημιουργεί ένα παράδειγμα του Aspose AI web client που συνδέεται σε ένα προσαρμοσμένο URL τελικού σημείου. Χρησιμοποιήστε αυτήν τη μεταφόρτωση όταν διαθέτετε ένα URL που παρέχεται από την ομάδα Aspose.Slides· διαφορετικά, χρησιμοποιήστε τη μεταφόρτωση AsposeAIWebClient() με το προεπιλεγμένο URL.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | java.lang.String | Το URL τελικού σημείου του Aspose LLM, που παρέχεται από την ομάδα Aspose.Slides. |

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

Δημιουργεί ένα παράδειγμα του Aspose AI web client που συνδέεται σε ένα προσαρμοσμένο URL τελικού σημείου χρησιμοποιώντας έναν εξωτερικά διαχειριζόμενο HttpClient. Ο παρεχόμενος HttpClient δεν διαγράφεται από αυτό το παράδειγμα και παραμένει στην ιδιοκτησία του καλούντος. Χρησιμοποιήστε αυτήν τη μεταφόρτωση όταν διαθέτετε ένα URL που παρέχεται από την ομάδα Aspose.Slides και θέλετε να παρέχετε το δικό σας HttpClient· εάν χρειάζεστε μόνο το δικό σας HttpClient με το προεπιλεγμένο URL, χρησιμοποιήστε αντί αυτού τη μεταφόρτωση AsposeAIWebClient(HttpClient).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | java.lang.String | Το URL τελικού σημείου του Aspose LLM, που παρέχεται από την ομάδα Aspose.Slides. |
| httpClient | java.net.HttpURLConnection | Ένα εξωτερικά διαχειριζόμενο αντικείμενο HttpClient. |

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

Στέλνει μια εντολή συνομιλίας στο μοντέλο AI χρησιμοποιώντας ένα παρεχόμενο αντικείμενο HttpConnection και επιστρέφει το μήνυμα απάντησης στην δεδομένη εντολή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Επιστροφή:**
java.lang.String

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Δημιουργεί ένα παράδειγμα συνομιλίας. Σε αντίθεση με τις κανονικές κλήσεις AI, οι συνομιλίες διατηρούν όλο το πλαίσιο.

**Επιστροφή:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Ένα [IAIConversation](../../com.aspose.slides/iaiconversation) παράδειγμα.

### dispose() {#dispose--}
```
public final void dispose()
```

Απελευθερώνει τους πόρους που χρησιμοποιεί αυτό το παράδειγμα.