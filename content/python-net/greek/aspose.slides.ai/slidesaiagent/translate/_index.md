---
title: translate method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.ai/slidesaiagent/translate/
weight: 30
---
## translate(self, presentation, language) {#ipresentation-str}
Μεταφράζει μια παρουσίαση στην καθορισμένη γλώσσα χρησιμοποιώντας AI (συγχρονική έκδοση).

```python
def translate(self, presentation, language):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation) | Target presentation |
| language | **str** | Target language |

### Παρατηρήσεις

Το παράδειγμα παρακάτω χρησιμοποιεί το προεπιλεγμένο [`AsposeAIWebClient`](/slides/python-net/el/aspose.slides.ai/asposeaiwebclient), το οποίο δημιουργείται από τον χωρίς παραμέτρους **SlidesAIAgent.#ctor** κατασκευαστή και συνδέεται με το δικό του LLM της Aspose. Για να χρησιμοποιήσετε διαφορετικό πάροχο AI, παρέχετε το δικό σας LLM ή προσαρμόστε τη σύνδεση (για παράδειγμα, παρέχοντας το δικό σας `HttpClient`), περάστε μια [`IAIWebClient`](/slides/python-net/el/aspose.slides.ai/iaiwebclient) υλοποίηση στο **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** κατασκευαστή. Διαθέσιμες υλοποιήσεις περιλαμβάνουν:

* [`AsposeAIWebClient`](/slides/python-net/el/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/el/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/el/aspose.slides.ai/openaicompatiblewebclient)

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Δεν παρέχεται το στιγμιότυπο παρουσίασης |
| **RuntimeError(Proxy error(ArgumentException))** | Η τιμή της γλώσσας δεν μπορεί να είναι None ή κενή |

### Δείτε επίσης
* κλάση [`AsposeAIWebClient`](/slides/python-net/el/aspose.slides.ai/asposeaiwebclient)
* κλάση [`IAIWebClient`](/slides/python-net/el/aspose.slides.ai/iaiwebclient)
* κλάση [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation)
* κλάση [`OpenAICompatibleWebClient`](/slides/python-net/el/aspose.slides.ai/openaicompatiblewebclient)
* κλάση [`OpenAIWebClient`](/slides/python-net/el/aspose.slides.ai/openaiwebclient)
* κλάση [`SlidesAIAgent`](/slides/python-net/el/aspose.slides.ai/slidesaiagent)
* μονάδα [`aspose.slides.ai`](/slides/python-net/el/aspose.slides.ai)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)