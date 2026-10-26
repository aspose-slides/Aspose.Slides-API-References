---
title: generate_presentation method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.ai/slidesaiagent/generate_presentation/
weight: 20
---
## generate_presentation(self, description, presentation_content_amount) {#str-presentationcontentamounttype}
Δημιουργεί ένα στιγμιότυπο παρουσίασης από μια περιγραφή κειμένου. Παρέχετε ένα θέμα, ιδέες, παραθέσεις ή αποσπάσματα κειμένου στην απαιτούμενη γλώσσα.

```python
def generate_presentation(self, description, presentation_content_amount):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| description | **str** | Το θέμα, οι ιδέες, οι παραθέσεις ή τα αποσπάσματα κειμένου. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/el/aspose.slides.ai/presentationcontentamounttype) | Η ποσότητα του περιεχομένου στην τελική παρουσίαση. |

### Παρατηρήσεις

Το παρακάτω παράδειγμα χρησιμοποιεί το προεπιλεγμένο [`AsposeAIWebClient`](/slides/python-net/el/aspose.slides.ai/asposeaiwebclient), το οποίο δημιουργείται από τον κατασκευαστή **SlidesAIAgent.#ctor** χωρίς παραμέτρους και συνδέεται με το δικό της LLM της Aspose. Για να χρησιμοποιήσετε διαφορετικό πάροχο AI, παρέχετε το δικό σας LLM ή προσαρμόστε τη σύνδεση (για παράδειγμα, παρέχοντας το δικό σας `HttpClient`), περάστε μια υλοποίηση [`IAIWebClient`](/slides/python-net/el/aspose.slides.ai/iaiwebclient) στον κατασκευαστή **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. Διαθέσιμες υλοποιήσεις περιλαμβάνουν:
             
* [`AsposeAIWebClient`](/slides/python-net/el/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/el/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/el/aspose.slides.ai/openaicompatiblewebclient)

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Η οδηγία συνομιλίας AI δεν μπορεί να είναι None ή κενή. |

## generate_presentation(self, description, presentation_content_amount, presentation_template) {#str-presentationcontentamounttype-ipresentation}
Δημιουργεί ένα στιγμιότυπο παρουσίασης από μια περιγραφή κειμένου. Παρέχετε ένα θέμα, ιδέες, παραθέσεις ή αποσπάσματα κειμένου στην απαιτούμενη γλώσσα.

```python
def generate_presentation(self, description, presentation_content_amount, presentation_template):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| description | **str** | Το θέμα, οι ιδέες, οι παραθέσεις ή τα αποσπάσματα κειμένου. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/el/aspose.slides.ai/presentationcontentamounttype) | Η ποσότητα του περιεχομένου στην τελική παρουσίαση. |
| presentation_template | [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation) | Μια παρουσίαση που θα χρησιμοποιηθεί ως πρότυπο για διάταξη και σχεδίαση, αντικαθιστώντας το προεπιλεγμένο πρότυπο. |

### Παρατηρήσεις

Το παρακάτω παράδειγμα χρησιμοποιεί το προεπιλεγμένο [`AsposeAIWebClient`](/slides/python-net/el/aspose.slides.ai/asposeaiwebclient), το οποίο δημιουργείται από τον κατασκευαστή **SlidesAIAgent.#ctor** χωρίς παραμέτρους και συνδέεται με το δικό της LLM της Aspose. Για να χρησιμοποιήσετε διαφορετικό πάροχο AI, παρέχετε το δικό σας LLM ή προσαρμόστε τη σύνδεση (για παράδειγμα, παρέχοντας το δικό σας `HttpClient`), περάστε μια υλοποίηση [`IAIWebClient`](/slides/python-net/el/aspose.slides.ai/iaiwebclient) στον κατασκευαστή **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. Διαθέσιμες υλοποιήσεις περιλαμβάνουν:
             
* [`AsposeAIWebClient`](/slides/python-net/el/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/el/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/el/aspose.slides.ai/openaicompatiblewebclient)

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Το πρότυπο παρουσίασης δεν παρέχεται. |
| **RuntimeError(Proxy error(ArgumentException))** | Η οδηγία συνομιλίας AI δεν μπορεί να είναι None ή κενή. |

### Δείτε επίσης
* κλάση [`AsposeAIWebClient`](/slides/python-net/el/aspose.slides.ai/asposeaiwebclient)
* κλάση [`IAIWebClient`](/slides/python-net/el/aspose.slides.ai/iaiwebclient)
* κλάση [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation)
* κλάση [`OpenAICompatibleWebClient`](/slides/python-net/el/aspose.slides.ai/openaicompatiblewebclient)
* κλάση [`OpenAIWebClient`](/slides/python-net/el/aspose.slides.ai/openaiwebclient)
* απαρίθμηση [`PresentationContentAmountType`](/slides/python-net/el/aspose.slides.ai/presentationcontentamounttype)
* κλάση [`SlidesAIAgent`](/slides/python-net/el/aspose.slides.ai/slidesaiagent)
* μονάδα [`aspose.slides.ai`](/slides/python-net/el/aspose.slides.ai)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)