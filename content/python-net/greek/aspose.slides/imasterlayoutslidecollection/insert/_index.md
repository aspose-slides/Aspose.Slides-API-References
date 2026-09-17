---
title: insert method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/imasterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
Εισάγει μια νέα διαφάνεια διάταξης στη συγκεκριμένη θέση της συλλογής.

### Επιστρέφει

Εισαχθείσα διαφάνεια.



```python
def insert(self, index, layout_type, layout_name):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | **int** | Index της νέας διαφάνειας. |
| layout_type | [`SlideLayoutType`](/slides/python-net/el/aspose.slides/slidelayouttype) | Τύπος διάταξης για μια νέα διάταξη.<br/><br/>            Υποστηριζόμενοι τύποι διάταξης: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Άλλοι τύποι διάταξης δεν υποστηρίζονται προς το παρόν: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Όνομα για μια νέα διάταξη. Εάν το δοσμένο όνομα είναι ήδη σε χρήση, θα ρίχνεται ArgumentException.<br/><br/>            Εάν παρασχεθεί παράμετρος None, τότε το όνομα δημιουργείται αυτόματα με βάση τον δοσμένο τύπο διάταξης <br/><br/>            (για παράδειγμα "Title Slide" ή "1_Title Slide", "2_..", κ.λπ.). |

### Παρατηρήσεις

Η εισαχθείσα διάταξη για την τιμή SlideLayoutType.Custom του `layout_type` δεν περιέχει σύμβολα κράτησης θέσης και κανένα σχήμα.

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Ρίχνεται εάν δοθεί μη υποστηριζόμενη τιμή της παραμέτρου `layout_type`. Τύποι διάταξης που δεν υποστηρίζονται προς το παρόν: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Ρίχνεται εάν η τιμή ονόματος διάταξης `layout_name` είναι ήδη σε χρήση στη <br/>            συλλογή των διατάξεων. |



### Δείτε επίσης
* κλάση [`ILayoutSlide`](/slides/python-net/el/aspose.slides/ilayoutslide)
* κλάση [`IMasterLayoutSlideCollection`](/slides/python-net/el/aspose.slides/imasterlayoutslidecollection)
* απαρίθμηση [`SlideLayoutType`](/slides/python-net/el/aspose.slides/slidelayouttype)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)