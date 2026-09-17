---
title: SlidesAIAgent constructor
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.ai/slidesaiagent/__init__/
weight: 10
---
## __init__(self) {#}
Δημιουργεί μια νέα παρουσία του [`SlidesAIAgent`](/slides/python-net/el/aspose.slides.ai/slidesaiagent) χρησιμοποιώντας το ενσωματωμένο
            [`AsposeAIWebClient`](/slides/python-net/el/aspose.slides.ai/asposeaiwebclient) με την προεπιλεγμένη του διαμόρφωση. Ο πελάτης συνδέεται με
            το δικό του LLM της Aspose και δεν απαιτεί πρόσθετη διαμόρφωση.
            Για να χρησιμοποιήσετε διαφορετικό πελάτη AI, χρησιμοποιήστε την **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** υπερφόρτωση αντί αυτού.

```python
def __init__(self):
    ...
```



## __init__(self, ai_client) {#iaiwebclient}
Δημιουργεί μια νέα παρουσία του [`SlidesAIAgent`](/slides/python-net/el/aspose.slides.ai/slidesaiagent) με προσαρμοσμένο πελάτη AI.
            Χρησιμοποιήστε αυτήν την υπερφόρτωση για να καθορίσετε τον πάροχο AI, να παρέχετε το δικό σας LLM ή να προσαρμόσετε τη
            σύνδεση (για παράδειγμα, παρέχοντας το δικό σας `HttpClient`).
            Μπορεί να χρησιμοποιηθεί οποιαδήποτε υλοποίηση του [`IAIWebClient`](/slides/python-net/el/aspose.slides.ai/iaiwebclient), συμπεριλαμβανομένων:
            
* [`AsposeAIWebClient`](/slides/python-net/el/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/el/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/el/aspose.slides.ai/openaicompatiblewebclient)


            Για να χρησιμοποιήσετε το ενσωματωμένο [`AsposeAIWebClient`](/slides/python-net/el/aspose.slides.ai/asposeaiwebclient) με την προεπιλεγμένη του διαμόρφωση,
            χρησιμοποιήστε την **SlidesAIAgent.#ctor** υπερφόρτωση αντί αυτού.

```python
def __init__(self, ai_client):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ai_client | [`IAIWebClient`](/slides/python-net/el/aspose.slides.ai/iaiwebclient) | Αντικείμενο πελάτη AI. Μπορεί να χρησιμοποιηθεί οποιαδήποτε υλοποίηση του [`IAIWebClient`](/slides/python-net/el/aspose.slides.ai/iaiwebclient). |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Δεν παρέχεται αντικείμενο πελάτη AI. |



### Δείτε επίσης
* κλάση [`AsposeAIWebClient`](/slides/python-net/el/aspose.slides.ai/asposeaiwebclient)
* κλάση [`IAIWebClient`](/slides/python-net/el/aspose.slides.ai/iaiwebclient)
* κλάση [`OpenAICompatibleWebClient`](/slides/python-net/el/aspose.slides.ai/openaicompatiblewebclient)
* κλάση [`OpenAIWebClient`](/slides/python-net/el/aspose.slides.ai/openaiwebclient)
* κλάση [`SlidesAIAgent`](/slides/python-net/el/aspose.slides.ai/slidesaiagent)
* μονάδα [`aspose.slides.ai`](/slides/python-net/el/aspose.slides.ai)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)