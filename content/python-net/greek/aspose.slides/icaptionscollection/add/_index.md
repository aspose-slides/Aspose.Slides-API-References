---
title: add method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/icaptionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
Προσθέτει υπότιτλους WebVTT στο τέλος της συλλογής.

### Επιστρέφει

Το προστιθέμενο [`ICaptions`](/slides/python-net/el/aspose.slides/icaptions) αντικείμενο.



```python
def add(self, label, file_path):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| label | **str** | Η ετικέτα των υποτίτλων. |
| file_path | **str** | Η διαδρομή προς το αρχείο WebVTT. |

### Εξαιρέσεις

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Εκτρέπεται εάν το `file_path` είναι `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Εκτρέπεται εάν το `file_path` είναι κενό. |


## add(self, label, stream) {#str-iorawiobase}
Προσθέτει υπότιτλους WebVTT στο τέλος της συλλογής από μια ροή.

### Επιστρέφει

Το προστιθέμενο [`ICaptions`](/slides/python-net/el/aspose.slides/icaptions) αντικείμενο.



```python
def add(self, label, stream):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| label | **str** | Η ετικέτα των υποτίτλων. |
| stream | **io.RawIOBase** | Η ροή εισόδου που περιέχει δεδομένα σε μορφή WebVTT. |

### Εξαιρέσεις

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Εκτρέπεται εάν το `stream` είναι `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Εκτρέπεται εάν τα δεδομένα εισόδου δεν είναι σε μορφή WebVTT. |



### Δείτε επίσης
* κλάση [`ICaptions`](/slides/python-net/el/aspose.slides/icaptions)
* κλάση [`ICaptionsCollection`](/slides/python-net/el/aspose.slides/icaptionscollection)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)