---
title: add method
second_title: Αναφορά API Aspose.Slides για Python μέσω .NET
description: 
type: docs
url: /el/aspose.slides/captionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
Προσθέτει υπότιτλους WebVTT στο τέλος της συλλογής.

### Επιστροφή

Το προσαρτημένο [`ICaptions`](/slides/python-net/el/aspose.slides/icaptions) αντικείμενο.



```python
def add(self, label, file_path):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| label | **str** | Η ετικέτα των υπότιτλων. |
| file_path | **str** | Η διαδρομή προς το αρχείο WebVTT. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Εγείρεται εάν `file_path` είναι `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Εγείρεται εάν `file_path` είναι κενό. |


## add(self, label, stream) {#str-iorawiobase}
Προσθέτει υπότιτλους WebVTT στο τέλος της συλλογής από μια ροή.

### Επιστροφή

Το προσαρτημένο [`ICaptions`](/slides/python-net/el/aspose.slides/icaptions) αντικείμενο.



```python
def add(self, label, stream):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| label | **str** | Η ετικέτα των υπότιτλων. |
| stream | **io.RawIOBase** | Η ροή εισόδου που περιέχει δεδομένα σε μορφή WebVTT. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Εγείρεται εάν `stream` είναι `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Εγείρεται εάν τα δεδομένα εισόδου δεν είναι σε μορφή WebVTT. |



### Δείτε επίσης
* κλάση [`CaptionsCollection`](/slides/python-net/el/aspose.slides/captionscollection)
* κλάση [`ICaptions`](/slides/python-net/el/aspose.slides/icaptions)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)