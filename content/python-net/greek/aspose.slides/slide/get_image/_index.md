---
title: get_image method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
Επιστρέφει ένα αντικείμενο Thumbnail Image (20 % του πραγματικού μεγέθους).


```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposepydrawingsize}
Επιστρέφει ένα αντικείμενο Thumbnail Image με το καθορισμένο μέγεθος.

### Επιστρέφει

Αντικείμενο εικόνας.



```python
def get_image(self, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| image_size | **aspose.slides.Size** | Μέγεθος της εικόνας προς δημιουργία. |


## get_image(self, options) {#asposeslidesexportitiffoptions}
Επιστρέφει ένα αντικείμενο Thumbnail tiff εικόνας με τα καθορισμένα παραμέτρους.

### Επιστρέφει

Αντικείμενο εικόνας.



```python
def get_image(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/el/aspose.slides.export/itiffoptions) | Επιλογές tiff. |

### Εξαιρέσεις

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Ρίχνεται όταν options.SlideLayoutOption είναι NotesCommentsLayoutingOptions και η ιδιότητά του NotesPosition λαμβάνει την τιμή NotesPositions.BottomFull. |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
Επιστρέφει ένα αντικείμενο Thumbnail Image.

### Επιστρέφει

Αντικείμενο εικόνας.



```python
def get_image(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/el/aspose.slides.export/irenderingoptions) | Επιλογές απόδοσης. |

### Εξαιρέσεις

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Ρίχνεται όταν notesCommentsLayouting.NotesPosition λαμβάνει την τιμή NotesPositions.BottomFull. |


## get_image(self, scale_x, scale_y) {#float-float}
Επιστρέφει ένα αντικείμενο Thumbnail Image με προσαρμοσμένη κλίμακα.

### Επιστέφει

Αντικείμενο IImage.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| scale_x | **float** | Η τιμή με την οποία κλιμακώνεται αυτό το Thumbnail στην κατεύθυνση του άξονα x. |
| scale_y | **float** | Η τιμή με την οποία κλιμακώνεται αυτό το Thumbnail στην κατεύθυνση του άξονα y. |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Επιστρέφει ένα αντικείμενο Thumbnail Image με το καθορισμένο μέγεθος.

### Επιστέφει

Αντικείμενο εικόνας.



```python
def get_image(self, options, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/el/aspose.slides.export/irenderingoptions) | Επιλογές απόδοσης. |
| image_size | **aspose.slides.Size** | Μέγεθος της εικόνας προς δημιουργία. |

### Εξαιρέσεις

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Ρίχνεται όταν options.SlideLayoutOption είναι NotesCommentsLayoutingOptions και η ιδιότητά του NotesPosition λαμβάνει την τιμή NotesPositions.BottomFull. |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Επιστρέφει ένα αντικείμενο Thumbnail Image με προσαρμοσμένη κλίμακα.

### Επιστέφει

Αντικείμενα Bitmap.



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/el/aspose.slides.export/irenderingoptions) | Επιλογές απόδοσης. |
| scale_x | **float** | Η τιμή με την οποία κλιμακώνεται αυτό το Thumbnail στην κατεύθυνση του άξονα x. |
| scale_y | **float** | Η τιμή με την οποία κλιμακώνεται αυτό το Thumbnail στην κατεύθυνση του άξονα y. |

### Εξαιρέσεις

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Ρίχνεται όταν notesCommentsLayouting.NotesPosition λαμβάνει την τιμή NotesPositions.BottomFull. |



### Δείτε επίσης
* κλάση [`IImage`](/slides/python-net/el/aspose.slides/iimage)
* κλάση [`IRenderingOptions`](/slides/python-net/el/aspose.slides.export/irenderingoptions)
* κλάση [`ITiffOptions`](/slides/python-net/el/aspose.slides.export/itiffoptions)
* κλάση [`Slide`](/slides/python-net/el/aspose.slides/slide)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)