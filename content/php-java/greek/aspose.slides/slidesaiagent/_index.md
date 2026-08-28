---
title: SlidesAIAgent
second_title: Aspose.Sildes για PHP μέσω αναφοράς API Java
description: 
type: docs

url: /el/aspose.slides/slidesaiagent/
---
## SlidesAIAgent κλάση

 Παρέχει λειτουργίες με τεχνητή νοημοσύνη για επεξεργασία παρουσιάσεων.
 
### SlidesAIAgent {#SlidesAIAgent}

| Όνομα | Περιγραφή |
| --- | --- |
| SlidesAIAgent([OpenAIWebClient](../openaiwebclient)) | Συνάρτηση SlidesAIAgent |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| aiClient | [OpenAIWebClient](../openaiwebclient) | Παράδειγμα πελάτη AI |

 **Επιστρέφει:**
SlidesAIAgent

 **Σφάλμα**

| Σφάλμα | Συνθήκη |
| --- | --- |
 | ArgumentNullException | Το παράδειγμα πελάτη AI δεν παρέχεται |


---


### generatePresentation {#generatePresentation}

| Όνομα | Περιγραφή |
| --- | --- |
| generatePresentation (String, int) | Δημιουργεί ένα αντικείμενο παρουσίασης από περιγραφή κειμένου. Παρέχετε ένα θέμα, ιδέες, αποσπάσματα ή τμήματα κειμένου στη ζητούμενη γλώσσα. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| description | String | Το θέμα, οι ιδέες, τα αποσπάσματα ή τα τμήματα κειμένου. |
| presentationContentAmount | int | Το ποσό του περιεχομένου στην προκύπτουσα παρουσίαση. String prompt = "Generate a presentation about Aspose.Slides for Java. Highlight its key features, use cases, and explain why it is better than its competitors."; OpenAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null); try { SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient); IPresentation pres = aiAgent.generatePresentation(prompt, PresentationContentAmountType.Brief); pres.save("result.pptx", SaveFormat.Pptx); } finally { if (aiWebClient != null) aiWebClient.close(); } |

 **Επιστρέφει:**
[Presentation](../presentation)

 **Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
 | ArgumentException | Η οδηγία συνομιλίας AI δεν μπορεί να είναι κενή ή μηδενική. |


---


### generatePresentation {#generatePresentation}

| Όνομα | Περιγραφή |
| --- | --- |
| generatePresentation (String, int, [Presentation](../presentation)) | Δημιουργεί ένα αντικείμενο παρουσίασης από περιγραφή κειμένου. Παρέχετε ένα θέμα, ιδέες, αποσπάσματα ή τμήματα κειμένου στη ζητούμενη γλώσσα. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| description | String | Το θέμα, οι ιδέες, τα αποσπάσματα ή τα τμήματα κειμένου. |
| presentationContentAmount | int | Το ποσό του περιεχομένου στην προκύπτουσα παρουσίαση. |
| presentationTemplate | [Presentation](../presentation) | Μια παρουσίαση που θα χρησιμοποιηθεί ως πρότυπο για διάταξη και σχεδίαση, αντικαθιστώντας το προεπιλεγμένο πρότυπο. String prompt = "Generate a presentation about Aspose.Slides for Java. Highlight its key features, use cases, and explain why it is better than its competitors."; IPresentation template = new Presentation("masterPresentation.pptx"); try { OpenAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null); try { SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient); IPresentation pres = aiAgent.generatePresentation(prompt, PresentationContentAmountType.Brief, template); pres.save("result.pptx", SaveFormat.Pptx); } finally { if (aiWebClient != null) aiWebClient.close(); } } finally { if (template != null) template.dispose(); } |

 **Επιστρέφει:**
[Presentation](../presentation)

 **Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
 | ArgumentException | Η οδηγία συνομιλίας AI δεν μπορεί να είναι κενή ή μηδενική. |


---


### translate {#translate}

| Όνομα | Περιγραφή |
| --- | --- |
| translate ([Presentation](../presentation), String) | Μεταφράζει μια παρουσίαση στην καθορισμένη γλώσσα χρησιμοποιώντας AI (συγχρονική έκδοση). |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| presentation | [Presentation](../presentation) | Προορισμένη παρουσίαση |
| language | String | Στόχος γλώσσας Presentation presentation = new Presentation("Presentation.pptx"); try { IAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", "apiKey", null); SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient); aiAgent.translate(presentation, "spanish"); presentation.save("translated.pptx", SaveFormat.Pptx); } finally { if (presentation != null) presentation.dispose(); } |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
 | ArgumentException | Η τιμή γλώσσας δεν μπορεί να είναι κενή ή μηδενική |


---