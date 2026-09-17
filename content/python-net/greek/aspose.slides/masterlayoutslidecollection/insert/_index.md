---
title: insert method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/masterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
Εισάγει μια νέα διαφάνεια διατάξεων στη συγκεκριμένη θέση της συλλογής.

### Επιστρέφει

Η εισαχθείσα διαφάνεια.



```python
def insert(self, index, layout_type, layout_name):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | **int** | Δείκτης της νέας διαφάνειας. |
| layout_type | [`SlideLayoutType`](/slides/python-net/el/aspose.slides/slidelayouttype) | Τύπος διάταξης για μια νέα διάταξη.<br/><br/> Υποστηριζόμενοι τύποι διάταξης: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/> Άλλοι τύποι διάταξης δεν υποστηρίζονται επί του παρόντος: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Όνομα για μια νέα διάταξη. Εάν το δοσμένο όνομα είναι ήδη σε χρήση, θα προκληθεί ArgumentException.<br/><br/> Εάν περάσει η παράμετρος None, τότε το όνομα δημιουργείται αυτόματα σύμφωνα με τον δοσμένο τύπο διάταξης <br/><br/> (για παράδειγμα "Title Slide" ή "1_Title Slide", "2_..", κλπ.). |

### Παρατηρήσεις

Η εισαχθείσα διάταξη για την τιμή SlideLayoutType.Custom του `layout_type` δεν περιέχει σύμβολα κράτησης θέσης και δεν περιέχει σχήματα.

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Πυροδοτείται εάν περαστεί μη υποστηριζόμενη τιμή της παραμέτρου `layout_type`. Τύποι διάταξης που δεν υποστηρίζονται επί του παρόντος: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Πυροδοτείται εάν η τιμή του ονόματος διάταξης `layout_name` είναι ήδη σε χρήση σε αυτή τη συλλογή των διατάξεων. |



### Δείτε επίσης
* κλάση [`ILayoutSlide`](/slides/python-net/el/aspose.slides/ilayoutslide)
* κλάση [`MasterLayoutSlideCollection`](/slides/python-net/el/aspose.slides/masterlayoutslidecollection)
* απαρίθμηση [`SlideLayoutType`](/slides/python-net/el/aspose.slides/slidelayouttype)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)