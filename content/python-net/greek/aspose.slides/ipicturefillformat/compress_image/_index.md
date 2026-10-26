---
title: compress_image method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/ipicturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
Συμπιέζει την εικόνα μειώνοντας το μέγεθός της με βάση το μέγεθος του σχήματος και την καθορισμένη ανάλυση. Προαιρετικά, διαγράφει επίσης τις κομμένες περιοχές.

### Επιστρέφει

Ένα **bool** που υποδεικνύει εάν η εικόνα συμπιέστηκε επιτυχώς. Επιστρέφει **True** εάν η εικόνα μετασχηματίστηκε ή περικόπηκε, διαφορετικά **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Εάν true, η μέθοδος θα αφαιρέσει τις κομμένες περιοχές της εικόνας, πιθανώς μειώνοντας περαιτέρω το μέγεθός της. |
| resolution | [`PicturesCompression`](/slides/python-net/el/aspose.slides.export/picturescompression) | Η στοχευόμενη ανάλυση για τη συμπίεση, καθορίζεται ως τιμή του [`PicturesCompression`](/slides/python-net/el/aspose.slides.export/picturescompression) enum. |

### Παρατηρήσεις

Αυτή η μέθοδος αλλάζει το μέγεθος και την ανάλυση της εικόνας παρόμοια με τη λειτουργία "Picture Format -> Compress Pictures" του PowerPoint.

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Εμφανίζεται όταν η ανάλυση δεν είναι έγκυρη τιμή. |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
Συμπιέζει την εικόνα μειώνοντας το μέγεθός της με βάση το μέγεθος του σχήματος και την καθορισμένη ανάλυση. Προαιρετικά, διαγράφει επίσης τις κομμένες περιοχές.

### Επιστρέφει

Ένα **bool** που υποδεικνύει εάν η εικόνα συμπιέστηκε επιτυχώς. Επιστρέφει **True** εάν η εικόνα μετασχηματίστηκε ή περικόπηκε, διαφορετικά **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Εάν true, η μέθοδος θα αφαιρέσει τις κομμένες περιοχές της εικόνας, πιθανώς μειώνοντας περαιτέρω το μέγεθός της. |
| resolution | **float** | Η στοχευόμενη ανάλυση σε DPI. Η τιμή αυτή πρέπει να είναι θετική και ορίζει πώς θα μετασχηματιστεί η εικόνα. |

### Παρατηρήσεις

Αυτή η μέθοδος αλλάζει το μέγεθος και την ανάλυση της εικόνας παρόμοια με τη λειτουργία "Picture Format -> Compress Pictures" του PowerPoint.

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Εμφανίζεται όταν η ανάλυση δεν είναι θετική τιμή. |



### Δείτε επίσης
* κλάση [`IPictureFillFormat`](/slides/python-net/el/aspose.slides/ipicturefillformat)
* απαρίθμηση [`PicturesCompression`](/slides/python-net/el/aspose.slides.export/picturescompression)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)