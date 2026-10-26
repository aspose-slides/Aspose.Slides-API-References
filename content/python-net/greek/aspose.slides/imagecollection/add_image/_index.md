---
title: add_image method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/imagecollection/add_image/
weight: 10
---
## add_image(self, image_source) {#ippimage}
Προσθέτει ένα αντίγραφο μιας εικόνας από μια άλλη παρουσίαση.

### Επιστρέφει
Η εικόνα προστέθηκε.



```python
def add_image(self, image_source):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/el/aspose.slides/ippimage) | Πηγή εικόνας. |


## add_image(self, image) {#iimage}
Προσθέτει μια εικόνα σε μια παρουσίαση.

### Επιστρέφει
Η εικόνα προστέθηκε.



```python
def add_image(self, image):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/el/aspose.slides/iimage) | Εικόνα προς προσθήκη. |

### Παρατηρήσεις
Αυτή η μέθοδος μετατρέπει τα μετααρχεία WMF/EMF σε raster εικόνα PNG πριν την εισαγωγή σε μια παρουσίαση.


## add_image(self, stream) {#iorawiobase}
Προσθέτει μια εικόνα σε μια παρουσίαση από ροή.

### Επιστρέφει
Η εικόνα προστέθηκε.



```python
def add_image(self, stream):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | **io.RawIOBase** | Ροή από την οποία θα προστεθεί η εικόνα. |

### Παρατηρήσεις
Αυτή η μέθοδος μπορεί να προσθέσει μετααρχεία WMF/EMF σε μια παρουσίαση χωρίς να τα μετατρέπει σε raster εικόνα PNG.


## add_image(self, buffer) {#bytes}
Προσθέτει μια εικόνα σε μια παρουσίαση από καθορισμένο buffer.

### Επιστρέφει
Η εικόνα προστέθηκε.



```python
def add_image(self, buffer):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| buffer | **bytes** | Buffer. |


## add_image(self, svg_image) {#isvgimage}
Προσθέτει μια εικόνα σε μια παρουσίαση από αντικείμενο Svg.

### Επιστρέφει
Η εικόνα προστέθηκε.



```python
def add_image(self, svg_image):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/el/aspose.slides/isvgimage) | Αντικείμενο εικόνας Svg [`ISvgImage`](/slides/python-net/el/aspose.slides/isvgimage) |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Όταν η παράμετρος svgImage είναι None. |


## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Δημιουργεί και προσθέτει μια εικόνα σε μια παρουσίαση από ροή.

### Επιστρέφει
Προστέθηκε [`IPPImage`](/slides/python-net/el/aspose.slides/ippimage).



```python
def add_image(self, stream, loading_stream_behavior):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | **io.RawIOBase** | Ροή από την οποία θα προστεθεί το αρχείο εικόνας. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/el/aspose.slides/loadingstreambehavior) | Η συμπεριφορά που θα εφαρμοστεί στη ροή. |



### Δείτε επίσης
* class [`IImage`](/slides/python-net/el/aspose.slides/iimage)
* class [`ImageCollection`](/slides/python-net/el/aspose.slides/imagecollection)
* class [`IPPImage`](/slides/python-net/el/aspose.slides/ippimage)
* class [`ISvgImage`](/slides/python-net/el/aspose.slides/isvgimage)
* enumeration [`LoadingStreamBehavior`](/slides/python-net/el/aspose.slides/loadingstreambehavior)
* module [`aspose.slides`](/slides/python-net/el/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)