---
title: add_from_html method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/iparagraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
Προσθέτει κείμενο από την καθορισμένη συμβολοσειρά html στη συλλογή.


```python
def add_from_html(self, text):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| text | **str** | HTML κείμενο. |


## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Προσθέτει κείμενο από την καθορισμένη συμβολοσειρά html στη συλλογή.


```python
def add_from_html(self, text, resolver, uri):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| text | **str** | HTML κείμενο. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/el/aspose.slides.importing/iexternalresourceresolver) | Αντικείμενο callback resolver που επιλύει URIs και φέρνει τα αναφορικά αντικείμενα. |
| uri | **str** | URI για προσθήκη εγγράφου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

### Σχόλια

Η καθορισμός του resolver μπορεί ενδεχομένως να εισάγει μια ευπάθεια. Χρησιμοποιήστε το με προσοχή.



### Δείτε επίσης
* κλάση [`IExternalResourceResolver`](/slides/python-net/el/aspose.slides.importing/iexternalresourceresolver)
* κλάση [`IParagraphCollection`](/slides/python-net/el/aspose.slides/iparagraphcollection)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)