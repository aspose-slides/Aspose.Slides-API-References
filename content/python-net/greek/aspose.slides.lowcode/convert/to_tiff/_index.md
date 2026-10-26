---
title: to_tiff method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.lowcode/convert/to_tiff/
weight: 60
---
## to_tiff(pres, output_file_name) {#presentation-str}
Μετατρέπει την εισαγόμενη παρουσίαση σε ένα σύνολο εικόνων μορφής TIFF.  
Αν το όνομα αρχείου εξόδου δοθεί ως "myPath/myFilename.tiff", το αποτέλεσμα θα αποθηκευτεί ως ένα σύνολο αρχείων "myPath/myFilename_N.tiff", όπου N είναι ο αριθμός της διαφάνειας.


```python
@staticmethod
def to_tiff(pres, output_file_name):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/el/aspose.slides/presentation) | Η εισαγόμενη παρουσίαση. |
| output_file_name | **str** | Το όνομα αρχείου εξόδου. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_tiff(pres, output_file_name, options, multipage) {#presentation-str-asposeslidesexportitiffoptions-bool}
Μετατρέπει την εισαγόμενη παρουσίαση σε μορφή TIFF με προσαρμοσμένες επιλογές.  
Αν το όνομα αρχείου εξόδου δοθεί ως "myPath/myFilename.tiff" και `multipage` είναι `false`, το αποτέλεσμα θα αποθηκευτεί ως ένα σύνολο αρχείων "myPath/myFilename_N.tiff", όπου N είναι ο αριθμός της διαφάνειας.  
Διαφορετικά, αν το `multipage` είναι `true`, το αποτέλεσμα θα είναι ένα πολυσέλιδο έγγραφο "myPath/myFilename.tiff".


```python
@staticmethod
def to_tiff(pres, output_file_name, options, multipage):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/el/aspose.slides/presentation) | Η εισαγόμενη παρουσίαση. |
| output_file_name | **str** | Το όνομα αρχείου εξόδου. |
| options | [`ITiffOptions`](/slides/python-net/el/aspose.slides.export/itiffoptions) | Οι επιλογές αποθήκευσης TIFF. |
| multipage | **bool** | Καθορίζει αν το δημιουργημένο έγγραφο TIFF θα είναι πολυσέλιδο. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### Δείτε επίσης
* κλάση [`Convert`](/slides/python-net/el/aspose.slides.lowcode/convert)
* κλάση [`ITiffOptions`](/slides/python-net/el/aspose.slides.export/itiffoptions)
* κλάση [`Presentation`](/slides/python-net/el/aspose.slides/presentation)
* μονάδα [`aspose.slides.lowcode`](/slides/python-net/el/aspose.slides.lowcode)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)