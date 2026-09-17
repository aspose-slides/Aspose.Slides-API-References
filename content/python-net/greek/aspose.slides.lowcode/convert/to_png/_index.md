---
title: to_png method
second_title: Aspose.Slides για Python μέσω .NET API Reference
description: 
type: docs
url: /el/aspose.slides.lowcode/convert/to_png/
weight: 40
---
## to_png(pres, output_file_name) {#presentation-str}
Μετατρέπει την παρουσίαση εισόδου σε μια συλλογή εικόνων μορφής PNG.  
            Εάν το όνομα του αρχείου εξόδου δοθεί ως "myPath/myFilename.png", 
            το αποτέλεσμα θα αποθηκευτεί ως μια σειρά αρχείων "myPath/myFilename_N.png", όπου N είναι αριθμός διαφάνειας.


```python
@staticmethod
def to_png(pres, output_file_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/el/aspose.slides/presentation) | Η παρουσίαση εισόδου. |
| output_file_name | **str** | Το όνομα του αρχείου εξόδου. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, image_size) {#presentation-str-asposepydrawingsize}
Μετατρέπει την παρουσίαση εισόδου σε μια συλλογή εικόνων μορφής PNG.  
            Εάν το όνομα του αρχείου εξόδου δοθεί ως "myPath/myFilename.png", 
            το αποτέλεσμα θα αποθηκευτεί ως μια σειρά αρχείων "myPath/myFilename_N.png", όπου N είναι αριθμός διαφάνειας.


```python
@staticmethod
def to_png(pres, output_file_name, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/el/aspose.slides/presentation) | Η παρουσίαση εισόδου |
| output_file_name | **str** | Το όνομα του αρχείου εξόδου. |
| image_size | **aspose.slides.Size** | Το μέγεθος κάθε παραγόμενης εικόνας. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Μετατρέπει την παρουσίαση εισόδου σε μια συλλογή εικόνων μορφής PNG.  
            Εάν το όνομα του αρχείου εξόδου δοθεί ως "myPath/myFilename.png", 
            το αποτέλεσμα θα αποθηκευτεί ως μια σειρά αρχείων "myPath/myFilename_N.png", όπου N είναι αριθμός διαφάνειας.


```python
@staticmethod
def to_png(pres, output_file_name, scale, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/el/aspose.slides/presentation) | Η παρουσίαση εισόδου. |
| output_file_name | **str** | Το όνομα του αρχείου εξόδου. |
| scale | **float** | Ο συντελεστής κλίμακας που εφαρμόζεται στις εικόνες εξόδου σε σχέση με το αρχικό μέγεθος της διαφάνειας. |
| options | [`IRenderingOptions`](/slides/python-net/el/aspose.slides.export/irenderingoptions) | Οι επιλογές απόδοσης. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### See Also
* κλάση [`Convert`](/slides/python-net/el/aspose.slides.lowcode/convert)
* κλάση [`IRenderingOptions`](/slides/python-net/el/aspose.slides.export/irenderingoptions)
* κλάση [`Presentation`](/slides/python-net/el/aspose.slides/presentation)
* μονάδα [`aspose.slides.lowcode`](/slides/python-net/el/aspose.slides.lowcode)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)