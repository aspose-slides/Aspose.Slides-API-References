---
title: set_embedded_data method
second_title: Aspose.Slides για Python μέσω .NET API Reference
description: 
type: docs
url: /el/aspose.slides/ioleobjectframe/set_embedded_data/
weight: 50
---
## set_embedded_data(self, embedded_data) {#ioleembeddeddatainfo}
Ορίζει πληροφορίες για τα ενσωματωμένα δεδομένα OLE.


```python
def set_embedded_data(self, embedded_data):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| embedded_data | [`IOleEmbeddedDataInfo`](/slides/python-net/el/aspose.slides/ioleembeddeddatainfo) | Ενσωματωμένα δεδομένα [`IOleEmbeddedDataInfo`](/slides/python-net/el/aspose.slides/ioleembeddeddatainfo) |

### Remarks

Αυτή η μέθοδος αλλάζει τις ιδιότητες του αντικειμένου ώστε να αντικατοπτρίζει τα νέα δεδομένα και 
            ορίζει τη σημαία IsObjectLink σε false, υποδεικνύοντας ότι το αντικείμενο OLE είναι ενσωματωμένο.

### Exceptions

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Όταν η παράμετρος embeddedData είναι None. |



### See Also
* κλάση [`IOleEmbeddedDataInfo`](/slides/python-net/el/aspose.slides/ioleembeddeddatainfo)
* κλάση [`IOleObjectFrame`](/slides/python-net/el/aspose.slides/ioleobjectframe)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)