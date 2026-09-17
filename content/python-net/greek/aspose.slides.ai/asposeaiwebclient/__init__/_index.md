---
title: AsposeAIWebClient constructor
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides.ai/asposeaiwebclient/__init__/
weight: 10
---
## __init__(self) {#}
Δημιουργεί ένα στιγμιότυπο του Aspose AI web client που συνδέεται με το προεπιλεγμένο σημείο άκρης Aspose LLM.  
Αυτό είναι ο πελάτης που χρησιμοποιείται από τον κατασκευαστή **SlidesAIAgent.#ctor** χωρίς παραμέτρους, έτσι η ρητή δημιουργία του απαιτείται μόνο όταν περνάτε τον πελάτη απευθείας στον κατασκευαστή **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**.

```python
def __init__(self):
    ...
```

## __init__(self, url) {#str}
Δημιουργεί ένα στιγμιότυπο του Aspose AI web client που συνδέεται με προσαρμοσμένο URL σημείου άκρης. Χρησιμοποιήστε αυτή τη υπερφόρτωση όταν έχετε URL που παρέχεται από την ομάδα Aspose.Slides· διαφορετικά, χρησιμοποιήστε τη υπερφόρτωση **AsposeAIWebClient.#ctor** με το προεπιλεγμένο URL.

```python
def __init__(self, url):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| url | **str** | Endpoint URL του Aspose LLM, που παρέχεται από την ομάδα Aspose.Slides. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Το URL δεν μπορεί να είναι None ή κενό. |

### Δείτε επίσης
* κλάση [`AsposeAIWebClient`](/slides/python-net/el/aspose.slides.ai/asposeaiwebclient)
* μονάδα [`aspose.slides.ai`](/slides/python-net/el/aspose.slides.ai)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)