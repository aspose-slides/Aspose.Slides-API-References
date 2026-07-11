---
title: SlidesAIAgent
second_title: Aspose.Slides για την τεκμηρίωση API της Java
description: Παρέχει δυνατότητες με τεχνητή νοημοσύνη για την επεξεργασία παρουσιάσεων.
type: docs
url: /el/com.aspose.slides/slidesaiagent/
---
**Κληρονομικότητα:**
java.lang.Object
```
public class SlidesAIAgent
```

Παρέχει δυνατότητες με τεχνητή νοημοσύνη για την επεξεργασία παρουσιάσεων.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | Αρχικοποιεί ένα νέο παράδειγμα του [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) με προσαρμοσμένο πελάτη AI. |
| [SlidesAIAgent()](#SlidesAIAgent--) | Αρχικοποιεί ένα νέο παράδειγμα του [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) χρησιμοποιώντας το ενσωματωμένο [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) με την προεπιλεγμένη του διαμόρφωση. |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Μεταφράζει μια παρουσίαση στην καθορισμένη γλώσσα χρησιμοποιώντας AI (συγχρονική έκδοση). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Δημιουργεί ένα παράδειγμα παρουσίασης από περιγραφή κειμένου. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Δημιουργεί ένα παράδειγμα παρουσίασης από περιγραφή κειμένου. |

### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

Αρχικοποιεί ένα νέο παράδειγμα του [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) με προσαρμοσμένο πελάτη AI. Χρησιμοποιήστε αυτήν την υπερφόρτωση για να καθορίσετε τον πάροχο AI, να παρέχετε το δικό σας LLM ή να προσαρμόσετε τη σύνδεση (για παράδειγμα, παρέχοντας το δικό σας java.net.HttpURLConnection). Μπορεί να χρησιμοποιηθεί οποιαδήποτε υλοποίηση του [IAIWebClient](../../com.aspose.slides/iaiwebclient). Για να χρησιμοποιήσετε το ενσωματωμένο [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) με την προεπιλεγμένη του διαμόρφωση, χρησιμοποιήστε την υπερφόρτωση SlidesAIAgent() αντί αυτού.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | Παράδειγμα πελάτη AI. Μπορεί να χρησιμοποιηθεί οποιαδήποτε υλοποίηση του [IAIWebClient](../../com.aspose.slides/iaiwebclient). |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```

Αρχικοποιεί ένα νέο παράδειγμα του [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) χρησιμοποιώντας το ενσωματωμένο [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) με την προεπιλεγμένη του διαμόρφωση. Ο πελάτης συνδέεται με το δικό του LLM της Aspose και δεν απαιτεί πρόσθετη διαμόρφωση. Για να χρησιμοποιήσετε διαφορετικό πελάτη AI, χρησιμοποιήστε την υπερφόρτωση SlidesAIAgent(IAIWebClient) αντί αυτού.

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```

Μεταφράζει μια παρουσίαση στην καθορισμένη γλώσσα χρησιμοποιώντας AI (συγχρονική έκδοση).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Παρουσίαση-στόχος |
| language | java.lang.String | Γλώσσα-στόχος |

--------------------

Το παρακάτω παράδειγμα χρησιμοποιεί το προεπιλεγμένο [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient), το οποίο δημιουργείται από τον κατασκευαστή SlidesAIAgent() χωρίς παραμέτρους και συνδέεται με το δικό της LLM της Aspose. Για να χρησιμοποιήσετε διαφορετικό πάροχο AI, να παρέχετε το δικό σας LLM ή να προσαρμόσετε τη σύνδεση (για παράδειγμα, παρέχοντας το δικό σας java.net.HttpURLConnection), περάστε μια υλοποίηση [IAIWebClient](../../com.aspose.slides/iaiwebclient) στον κατασκευαστή SlidesAIAgent(IAIWebClient).

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

Δημιουργεί ένα παράδειγμα παρουσίασης από περιγραφή κειμένου. Παρέχετε ένα θέμα, ιδέες, παραθέσεις ή αποσπάσματα κειμένου στην απαιτούμενη γλώσσα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| description | java.lang.String | Το θέμα, οι ιδέες, οι παραθέσεις ή τα αποσπάσματα κειμένου. |
| presentationContentAmount | int | Η ποσότητα του περιεχομένου στην προκύπτουσα παρουσίαση. |

```
String prompt = "Generate a presentation about Aspose.Slides for Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
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

Δημιουργεί ένα παράδειγμα παρουσίασης από περιγραφή κειμένου. Παρέχετε ένα θέμα, ιδέες, παραθέσεις ή αποσπάσματα κειμένου στην απαιτούμενη γλώσσα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| description | java.lang.String | Το θέμα, οι ιδέες, οι παραθέσεις ή τα αποσπάσματα κειμένου. |
| presentationContentAmount | int | Η ποσότητα του περιεχομένου στην προκύπτουσα παρουσίαση. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Μια παρουσίαση προς χρήση ως πρότυπο για διάταξη και σχεδίαση, αντικαθιστώντας το προεπιλεγμένο πρότυπο. |

--------------------

Το παρακάτω παράδειγμα χρησιμοποιεί το προεπιλεγμένο [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient), το οποίο δημιουργείται από τον κατασκευαστή SlidesAIAgent() χωρίς παραμέτρους και συνδέεται με το δικό της LLM της Aspose. Για να χρησιμοποιήσετε διαφορετικό πάροχο AI, να παρέχετε το δικό σας LLM ή να προσαρμόσετε τη σύνδεση (για παράδειγμα, παρέχοντας το δικό σας java.net.HttpURLConnection), περάστε μια υλοποίηση [IAIWebClient](../../com.aspose.slides/iaiwebclient) στον κατασκευαστή SlidesAIAgent(IAIWebClient).

```
String prompt = "Generate a presentation about Aspose.Slides for Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
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