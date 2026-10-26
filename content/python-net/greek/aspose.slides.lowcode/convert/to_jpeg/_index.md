---
title: to_jpeg method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.lowcode/convert/to_jpeg/
weight: 20
---
## to_jpeg(pres, output_file_name) {#presentation-str}
Μετατρέπει την εισαγόμενη παρουσίαση σε ένα σύνολο εικόνων μορφής JPEG.  
            Εάν το όνομα του αρχείου εξόδου δοθεί ως "myPath/myFilename.jpeg", 
            το αποτέλεσμα θα αποθηκευτεί ως ένα σύνολο αρχείων "myPath/myFilename_N.jpeg", όπου N είναι αριθμός της διαφάνειας.


```python
@staticmethod
def to_jpeg(pres, output_file_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/el/aspose.slides/presentation) | Η εισαγόμενη παρουσίαση. |
| output_file_name | **str** | Το όνομα του αρχείου εξόδου. |

### Εξαιρέσεις

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, image_size) {#presentation-str-asposeslidessize}
Μετατρέπει την εισαγόμενη παρουσίαση σε ένα σύνολο εικόνων μορφής JPEG.  
            Εάν το όνομα του αρχείου εξόδου δοθεί ως "myPath/myFilename.jpeg", 
            το αποτέλεσμα θα αποθηκευτεί ως ένα σύνολο αρχείων "myPath/myFilename_N.jpeg", όπου N είναι αριθμός της διαφάνειας.


```python
@staticmethod
def to_jpeg(pres, output_file_name, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/el/aspose.slides/presentation) | Η εισαγόμενη παρουσίαση |
| output_file_name | **str** | Το όνομα του αρχείου εξόδου. |
| image_size | [`Size`](/slides/python-net/el/aspose.slides/size) | Το μέγεθος κάθε παραγόμενης εικόνας. |

### Εξαιρέσεις

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Μετατρέπει την εισαγόμενη παρουσίαση σε ένα σύνολο εικόνων μορφής JPEG.  
            Εάν το όνομα του αρχείου εξόδου δοθεί ως "myPath/myFilename.jpeg", 
            το αποτέλεσμα θα αποθηκευτεί ως ένα σύνολο αρχείων "myPath/myFilename_N.jpeg", όπου N είναι αριθμός της διαφάνειας.


```python
@staticmethod
def to_jpeg(pres, output_file_name, scale, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/el/aspose.slides/presentation) | Η εισαγόμενη παρουσίαση. |
| output_file_name | **str** | Το όνομα του αρχείου εξόδου. |
| scale | **float** | Ο συντελεστής κλίμακας που εφαρμόζεται στις εικόνες εξόδου σε σχέση με το αρχικό μέγεθος της διαφάνειας. |
| options | [`IRenderingOptions`](/slides/python-net/el/aspose.slides.export/irenderingoptions) | Οι επιλογές απόδοσης. |

### Εξαιρέσεις

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### Δείτε επίσης
* κλάση [`Convert`](/slides/python-net/el/aspose.slides.lowcode/convert)
* κλάση [`IRenderingOptions`](/slides/python-net/el/aspose.slides.export/irenderingoptions)
* κλάση [`Presentation`](/slides/python-net/el/aspose.slides/presentation)
* κλάση [`Size`](/slides/python-net/el/aspose.slides/size)
* μονάδα [`aspose.slides.lowcode`](/slides/python-net/el/aspose.slides.lowcode)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)