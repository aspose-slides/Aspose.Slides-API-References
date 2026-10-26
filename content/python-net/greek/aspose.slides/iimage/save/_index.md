---
title: save method
second_title: Aspose.Slides για Python μέσω .NET API
description: 
type: docs
url: /el/aspose.slides/iimage/save/
weight: 10
---
## save(self, filename) {#str}
Αποθηκεύει την εικόνα σε ένα αρχείο.


```python
def save(self, filename):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| filename | **str** | Η διαδρομή προς το αρχείο όπου θα αποθηκευτεί η εικόνα. |


## save(self, filename, format) {#str-imageformat}
Αποθηκεύει την εικόνα σε ένα αρχείο στη συγκεκριμένη μορφή.


```python
def save(self, filename, format):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| filename | **str** | Η διαδρομή προς το αρχείο όπου θα αποθηκευτεί η εικόνα. |
| format | [`ImageFormat`](/slides/python-net/el/aspose.slides/imageformat) | Η μορφή της εικόνας. |


## save(self, stream, format) {#iorawiobase-imageformat}
Αποθηκεύει την εικόνα σε μια ροή στη συγκεκριμένη μορφή.


```python
def save(self, stream, format):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | **io.RawIOBase** | Η ροή όπου θα αποθηκευτεί η εικόνα. |
| format | [`ImageFormat`](/slides/python-net/el/aspose.slides/imageformat) | Η μορφή της εικόνας. |


## save(self, filename, format, quality) {#str-imageformat-int}
Αποθηκεύει την εικόνα σε ένα αρχείο στη συγκεκριμένη μορφή και ποιότητα.


```python
def save(self, filename, format, quality):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| filename | **str** | Η διαδρομή προς το αρχείο όπου θα αποθηκευτεί η εικόνα. |
| format | [`ImageFormat`](/slides/python-net/el/aspose.slides/imageformat) | Η μορφή της εικόνας. |
| quality | **int** | Η ποιότητα της αποθηκευμένης εικόνας (0 έως 100).  <br/><br/>            Αυτή η παράμετρος επηρεάζει μόνο την αποθήκευση σε [`ImageFormat.JPEG`](/slides/python-net/el/aspose.slides/imageformat/JPEG)· για όλες τις άλλες μορφές, αγνοείται. |


## save(self, stream, format, quality) {#iorawiobase-imageformat-int}
Αποθηκεύει την εικόνα σε μια ροή στη συγκεκριμένη μορφή και ποιότητα.


```python
def save(self, stream, format, quality):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | **io.RawIOBase** | Η ροή όπου θα αποθηκευτεί η εικόνα. |
| format | [`ImageFormat`](/slides/python-net/el/aspose.slides/imageformat) | Η μορφή της εικόνας. |
| quality | **int** | Η ποιότητα της αποθηκευμένης εικόνας (0 έως 100).  <br/><br/>            Αυτή η παράμετρος επηρεάζει μόνο την αποθήκευση σε [`ImageFormat.JPEG`](/slides/python-net/el/aspose.slides/imageformat/JPEG)· για όλες τις άλλες μορφές, αγνοείται. |



### Δείτε επίσης
* κλάση [`IImage`](/slides/python-net/el/aspose.slides/iimage)
* αρίθμηση [`ImageFormat`](/slides/python-net/el/aspose.slides/imageformat)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)