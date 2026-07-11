---
title: SlidesAIAgent
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Παρέχει δυνατότητες με τεχνητή νοημοσύνη για την επεξεργασία παρουσιάσεων.
type: docs
url: /el/com.aspose.slides/slidesaiagent/
---
**Inheritance:**
java.lang.Object
```
public class SlidesAIAgent
```

Προσφέρει δυνατότητες με τεχνητή νοημοσύνη για την επεξεργασία παρουσιάσεων.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | SlidesAIAgent constructor |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Translates a presentation to the specified language using AI (synchronous version). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Generates a presentation instance from a text description. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Generates a presentation instance from a text description. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```


Κατασκευαστής SlidesAIAgent

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | AI client instance |

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public void translate(IPresentation presentation, String language)
```


Μεταφράζει μια παρουσίαση στην καθορισμένη γλώσσα χρησιμοποιώντας AI (συγχρονική έκδοση).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Target presentation |
| language | java.lang.String | Target language

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


Δημιουργεί ένα αντίτυπο παρουσίασης από περιγραφή κειμένου. Παρέχετε ένα θέμα, ιδέες, παραθέσεις ή αποσπάσματα κειμένου στην απαιτούμενη γλώσσα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| description | java.lang.String | The topic, ideas, quotes, or text snippets. |
| presentationContentAmount | int | The amount of content in the resulting presentation.

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


Δημιουργεί ένα αντίτυπο παρουσίασης από περιγραφή κειμένου. Παρέχετε ένα θέμα, ιδέες, παραθέσεις ή αποσπάσματα κειμένου στην απαιτούμενη γλώσσα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| description | java.lang.String | The topic, ideas, quotes, or text snippets. |
| presentationContentAmount | int | The amount of content in the resulting presentation. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | A presentation to use as a template for layout and design, replacing the default template.

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