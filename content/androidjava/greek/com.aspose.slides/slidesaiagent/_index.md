---
title: SlidesAIAgent
second_title: Αναφορά API Java για Aspose.Slides για Android
description: Παρέχει δυνατότητες AI για την επεξεργασία παρουσιάσεων.
type: docs
url: /el/com.aspose.slides/slidesaiagent/
---
**Κληρονομικότητα:**
java.lang.Object
```
public class SlidesAIAgent
```

Παρέχει δυνατότητες AI για την επεξεργασία παρουσιάσεων.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | Αρχικοποιεί μια νέα εμφάνιση του [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) με έναν προσαρμοσμένο πελάτη AI. |
| [SlidesAIAgent()](#SlidesAIAgent--) | Αρχικοποιεί μια νέα εμφάνιση του [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) χρησιμοποιώντας το ενσωματωμένο [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) με την προεπιλεγμένη του ρύθμιση. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Μεταφράζει μια παρουσίαση στην καθορισμένη γλώσσα χρησιμοποιώντας AI (συγχρονής έκδοση). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Δημιουργεί μια παρουσίαση από μια περιγραφή κειμένου. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Δημιουργεί μια παρουσίαση από μια περιγραφή κειμένου. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

Αρχικοποιεί μια νέα εμφάνιση του [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) με έναν προσαρμοσμένο πελάτη AI. Χρησιμοποιήστε αυτήν τη υπερφόρτωση για να καθορίσετε τον πάροχο AI, να παρέχετε το δικό σας LLM ή να προσαρμόσετε τη σύνδεση (για παράδειγμα, παρέχοντας το δικό σας java.net.HttpURLConnection). Μπορεί να χρησιμοποιηθεί οποιαδήποτε υλοποίηση του [IAIWebClient](../../com.aspose.slides/iaiwebclient). Για να χρησιμοποιήσετε το ενσωματωμένο [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) με την προεπιλεγμένη του ρύθμιση, χρησιμοποιήστε την υπερφόρτωση SlidesAIAgent() αντ' αυτού.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | Αντικείμενο πελάτη AI. Μπορεί να χρησιμοποιηθεί οποιαδήποτε υλοποίηση του [IAIWebClient](../../com.aspose.slides/iaiwebclient). |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```

Αρχικοποιεί μια νέα εμφάνιση του [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) χρησιμοποιώντας το ενσωματωμένο [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) με την προεπιλεγμένη του ρύθμιση. Ο πελάτης συνδέεται με το δικό του LLM της Aspose και δεν απαιτεί πρόσθετη ρύθμιση. Για να χρησιμοποιήσετε διαφορετικό πελάτη AI, χρησιμοποιήστε την υπερφόρτωση SlidesAIAgent(IAIWebClient) αντ' αυτού.

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```

Μεταφράζει μια παρουσίαση στην καθορισμένη γλώσσα χρησιμοποιώντας AI (συγχρονής έκδοση).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Στόχος παρουσίασης |
| language | java.lang.String | Στόχος γλώσσα

--------------------

Το παρακάτω παράδειγμα χρησιμοποιεί το προεπιλεγμένο [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient), το οποίο δημιουργείται από τον κατασκευαστή SlidesAIAgent() χωρίς παραμέτρους και συνδέεται με το δικό του LLM της Aspose. Για να χρησιμοποιήσετε διαφορετικό πάροχο AI, να παρέχετε το δικό σας LLM ή να προσαρμόσετε τη σύνδεση (για παράδειγμα, παρέχοντας το δικό σας java.net.HttpURLConnection), περάστε μια υλοποίηση [IAIWebClient](../../com.aspose.slides/iaiwebclient) στον κατασκευαστή SlidesAIAgent(IAIWebClient).

```
Presentation presentation = new Presentation("Presentation.pptx");
 try {
     IAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", "apiKey", null);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient);
     aiAgent.translate(presentation, "spanish");
     presentation.save("translated.pptx", SaveFormat.Pptx);
 } finally {
     if (presentation != null) presentation.dispose();
 }
``` |

### generatePresentation(String description, int presentationContentAmount) {#generatePresentation-java.lang.String-int-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount)
```

Δημιουργεί μια παρουσίαση από μια περιγραφή κειμένου. Παρέχετε ένα θέμα, ιδέες, αποσπάσματα ή αποκόμματα κειμένου στην απαιτούμενη γλώσσα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| description | java.lang.String | Το θέμα, οι ιδέες, τα αποσπάσματα ή τα αποκόμματα κειμένου. |
| presentationContentAmount | int | Η ποσότητα περιεχομένου στην προκύπτουσα παρουσίαση. |

```
String prompt = "Generate a presentation about Aspose.Slides for Android via Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
 OpenAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null);
 try {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient);
     IPresentation pres = aiAgent.generatePresentation(prompt, PresentationContentAmountType.Brief);
     pres.save("result.pptx", SaveFormat.Pptx);
 } finally {
     if (aiWebClient != null) aiWebClient.close();
 }
``` |

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation)
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```

Δημιουργεί μια παρουσίαση από μια περιγραφή κειμένου. Παρέχετε ένα θέμα, ιδέες, αποσπάσματα ή αποκόμματα κειμένου στην απαιτούμενη γλώσσα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| description | java.lang.String | Το θέμα, οι ιδέες, τα αποσπάσματα ή τα αποκόμματα κειμένου. |
| presentationContentAmount | int | Η ποσότητα περιεχομένου στην προκύπτουσα παρουσίαση. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Μια παρουσίαση που θα χρησιμοποιηθεί ως πρότυπο για διάταξη και σχεδίαση, αντικαθιστώντας το προεπιλεγμένο πρότυπο. |

--------------------

Το παρακάτω παράδειγμα χρησιμοποιεί το προεπιλεγμένο [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient), το οποίο δημιουργείται από τον κατασκευαστή SlidesAIAgent() χωρίς παραμέτρους και συνδέεται με το δικό του LLM της Aspose. Για να χρησιμοποιήσετε διαφορετικό πάροχο AI, να παρέχετε το δικό σας LLM ή να προσαρμόσετε τη σύνδεση (για παράδειγμα, παρέχοντας το δικό σας java.net.HttpURLConnection), περάστε μια υλοποίηση [IAIWebClient](../../com.aspose.slides/iaiwebclient) στον κατασκευαστή SlidesAIAgent(IAIWebClient).

```
String prompt = "Generate a presentation about Aspose.Slides for Android via Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
 IPresentation template = new Presentation("masterPresentation.pptx");
 try {
     OpenAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null);
     try {
         SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient);
         IPresentation pres =
             aiAgent.generatePresentation(prompt, PresentationContentAmountType.Brief, template);
         pres.save("result.pptx", SaveFormat.Pptx);
     } finally {
         if (aiWebClient != null) aiWebClient.close();
     }
 } finally {
     if (template != null) template.dispose();
 }
``` |

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation)