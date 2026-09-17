---
title: OpenAIWebClient constructor
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.ai/openaiwebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, organization_id) {#str-str-str}
Δημιουργεί μια παρουσία του πελάτη web του OpenAI.

```python
def __init__(self, model, api_key, organization_id):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| model | **str** | Γλωσσικό μοντέλο OpenAI. Πιθανές τιμές:<br/><br/>              - gpt-4o<br/><br/>              - gpt-4o-mini<br/><br/>              - o1<br/><br/>              - o1-mini<br/><br/>              - o3<br/><br/>              - o3-mini |
| api_key | **str** | Κλειδί API OpenAI. |
| organization_id | **str** | Αναγνωριστικό οργανισμού (προαιρετικό). |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Η τιμή του API key δεν μπορεί να είναι None ή κενή. |
| **RuntimeError(Proxy error(ArgumentException))** | Η τιμή του model δεν μπορεί να είναι None ή κενή. |

### Δείτε επίσης
* κλάση [`OpenAIWebClient`](/slides/python-net/el/aspose.slides.ai/openaiwebclient)
* μονάδα [`aspose.slides.ai`](/slides/python-net/el/aspose.slides.ai)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)