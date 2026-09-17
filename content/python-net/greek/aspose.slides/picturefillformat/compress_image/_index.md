---
title: compress_image method
second_title: Αναφορά API Aspose.Slides για Python μέσω .NET
description: 
type: docs
url: /el/aspose.slides/picturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
Συμπιέζει την εικόνα μειώνοντας το μέγεθός της με βάση το μέγεθος του σχήματος και την καθορισμένη ανάλυση. Προαιρετικά, διαγράφει επίσης τις κομμένες περιοχές.

### Επιστρέφει

Μια **bool** που υποδεικνύει εάν η εικόνα συμπιέστηκε με επιτυχία. Επιστρέφει **True** αν η εικόνα επαναμετρήθηκε ή κοψήθηκε, διαφορετικά **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Εάν είναι αληθές, η μέθοδος θα αφαιρέσει τις κομμένες περιοχές της εικόνας, μειώνοντας ενδεχομένως περαιτέρω το μέγεθός της. |
| resolution | [`PicturesCompression`](/slides/python-net/el/aspose.slides.export/picturescompression) | Η επιθυμητή ανάλυση για συμπίεση, καθορισμένη ως τιμή του enum [`PicturesCompression`](/slides/python-net/el/aspose.slides.export/picturescompression). |

### Παρατηρήσεις

Αυτή η μέθοδος αλλάζει το μέγεθος και την ανάλυση της εικόνας παρόμοια με τη λειτουργία «Picture Format -> Compress Pictures» του PowerPoint.

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Εμφανίζεται όταν η ανάλυση δεν είναι έγκυρη τιμή. |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
Συμπιέζει την εικόνα μειώνοντας το μέγεθός της με βάση το μέγεθος του σχήματος και την καθορισμένη ανάλυση. Προαιρετικά, διαγράφει επίσης τις κομμένες περιοχές.

### Επιστρέφει

Μια **bool** που υποδεικνύει εάν η εικόνα συμπιέστηκε με επιτυχία. Επιστρέφει **True** αν η εικόνα επαναμετρήθηκε ή κοψήθηκε, διαφορετικά **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Εάν είναι αληθές, η μέθοδος θα αφαιρέσει τις κομμένες περιοχές της εικόνας, μειώνοντας ενδεχομένως περαιτέρω το μέγεθός της. |
| resolution | **float** | Η επιθυμητή ανάλυση σε DPI. Η τιμή πρέπει να είναι θετική και καθορίζει πώς θα αλλάξει το μέγεθος της εικόνας. |

### Παρατηρήσεις

Αυτή η μέθοδος αλλάζει το μέγεθος και την ανάλυση της εικόνας παρόμοια με τη λειτουργία «Picture Format -> Compress Pictures» του PowerPoint.

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Εμφανίζεται όταν η ανάλυση δεν είναι θετική τιμή. |



### Δείτε επίσης
* κλάση [`PictureFillFormat`](/slides/python-net/el/aspose.slides/picturefillformat)
* απαρίθμηση [`PicturesCompression`](/slides/python-net/el/aspose.slides.export/picturescompression)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)