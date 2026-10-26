---
title: OpenAICompatibleWebClient constructor
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.ai/openaicompatiblewebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, base_url) {#str-str-str}
Δημιουργεί ένα στιγμιότυπο του web client συμβατού με OpenAI.

```python
def __init__(self, model, api_key, base_url):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| model | **str** | Όνομα μοντέλου που υποστηρίζεται από τον πάροχο LLM. |
| api_key | **str** | Κλειδί API (διακριτικό). |
| base_url | **str** | Βασική διεύθυνση URL του LLM συμβατού με OpenAI. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Η τιμή του κλειδιού API δεν μπορεί να είναι None ή κενή. |
| **RuntimeError(Proxy error(ArgumentException))** | Η τιμή του μοντέλου κειμένου δεν μπορεί να είναι None ή κενή. |
| **RuntimeError(Proxy error(ArgumentException))** | Η τιμή της Βασικής URL δεν μπορεί να είναι None ή κενή. |

### Δείτε επίσης
* κλάση [`OpenAICompatibleWebClient`](/slides/python-net/el/aspose.slides.ai/openaicompatiblewebclient)
* μονάδα [`aspose.slides.ai`](/slides/python-net/el/aspose.slides.ai)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)