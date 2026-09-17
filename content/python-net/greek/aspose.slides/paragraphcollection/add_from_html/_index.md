---
title: add_from_html method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/paragraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
Προσθέτει κείμενο από τη συγκεκριμένη συμβολοσειρά html στη συλλογή.


```python
def add_from_html(self, text):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| text | **str** | κείμενο HTML. |


## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Προσθέτει κείμενο από τη συγκεκριμένη συμβολοσειρά html στη συλλογή.


```python
def add_from_html(self, text, resolver, uri):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| text | **str** | κείμενο HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/el/aspose.slides.importing/iexternalresourceresolver) | Αντικείμενο callback resolver που επιλύει URIs και ανακτά τα αναφερθέντα αντικείμενα. |
| uri | **str** | URI για την προσθήκη εγγράφου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

### Σχόλια

Η καθορισμός του resolver μπορεί ενδεχομένως να εισάγει τρωτότητα. Χρησιμοποιήστε με προσοχή.



### Δείτε επίσης
* κλάση [`IExternalResourceResolver`](/slides/python-net/el/aspose.slides.importing/iexternalresourceresolver)
* κλάση [`ParagraphCollection`](/slides/python-net/el/aspose.slides/paragraphcollection)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)