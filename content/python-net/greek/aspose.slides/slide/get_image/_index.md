---
title: get_image method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
Επιστρέφει ένα αντικείμενο Thumbnail Image (20% του πραγματικού μεγέθους).


```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposeslidessize}
Επιστρέφει ένα αντικείμενο Thumbnail Image με καθορισμένο μέγεθος.

### Returns

αντικείμενο Image.



```python
def get_image(self, image_size):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image_size | [`Size`](/slides/python-net/el/aspose.slides/size) | Μέγεθος της εικόνας που θα δημιουργηθεί. |


## get_image(self, options) {#asposeslidesexportitiffoptions}
Επιστρέφει ένα αντικείμενο Thumbnail tiff image με καθορισμένες παραμέτρους.

### Returns

αντικείμενο Image.



```python
def get_image(self, options):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/el/aspose.slides.export/itiffoptions) | Tiff options. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Thrown when options.SlideLayoutOption is NotesCommentsLayoutingOptions and its property NotesPosition takes the value NotesPositions.BottomFull. |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
Επιστρέφει ένα αντικείμενο Thumbnail Image.

### Returns

αντικείμενο Image.



```python
def get_image(self, options):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/el/aspose.slides.export/irenderingoptions) | Rendering options. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


## get_image(self, scale_x, scale_y) {#float-float}
Επιστρέφει ένα αντικείμενο Thumbnail Image με προσαρμοσμένη κλιμάκωση.

### Returns

αντικείμενο IImage.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| scale_x | **float** | Η τιμή με την οποία θα κλιμακώσετε αυτό το Thumbnail στην κατεύθυνση του άξονα x. |
| scale_y | **float** | Η τιμή με την οποία θα κλιμακώσετε αυτό το Thumbnail στην κατεύθυνση του άξονα y. |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Επιστρέφει ένα αντικείμενο Thumbnail Image με καθορισμένο μέγεθος.

### Returns

αντικείμενο Image.



```python
def get_image(self, options, image_size):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/el/aspose.slides.export/irenderingoptions) | Rendering options. |
| image_size | [`Size`](/slides/python-net/el/aspose.slides/size) | Μέγεθος της εικόνας που θα δημιουργηθεί. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Thrown when options.SlideLayoutOption is NotesCommentsLayoutingOptions and its property NotesPosition takes the value NotesPositions.BottomFull. |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Επιστρέφει ένα αντικείμενο Thumbnail Image με προσαρμοσμένη κλιμάκωση.

### Returns

αντικείμενα Bitmap.



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/el/aspose.slides.export/irenderingoptions) | Rendering options. |
| scale_x | **float** | Η τιμή με την οποία θα κλιμακώσετε αυτό το Thumbnail στην κατεύθυνση του άξονα x. |
| scale_y | **float** | Η τιμή με την οποία θα κλιμακώσετε αυτό το Thumbnail στην κατεύθυνση του άξονα y. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |



### Δείτε επίσης
* κλάση [`IImage`](/slides/python-net/el/aspose.slides/iimage)
* κλάση [`IRenderingOptions`](/slides/python-net/el/aspose.slides.export/irenderingoptions)
* κλάση [`ITiffOptions`](/slides/python-net/el/aspose.slides.export/itiffoptions)
* κλάση [`Slide`](/slides/python-net/el/aspose.slides/slide)
* κλάση [`Size`](/slides/python-net/el/aspose.slides/size)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)