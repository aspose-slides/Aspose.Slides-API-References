---
title: add method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/imasterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
Προσθέτει μια νέα διαφάνεια διάταξης στο τέλος της συλλογής.

### Επιστρέφει

Προστιθέμενη διαφάνεια.



```python
def add(self, layout_type, layout_name):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/el/aspose.slides/slidelayouttype) | Τύπος διάταξης για μια νέα διάταξη.<br/><br/>            Υποστηριζόμενοι τύποι διάταξης: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Άλλοι τύποι διάταξης δεν υποστηρίζονται αυτή τη στιγμή: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Όνομα για μια νέα διάταξη. Εάν το δοσμένο όνομα είναι ήδη σε χρήση, θα εξαχθεί ArgumentException.<br/><br/>            Εάν περαστεί η παράμετρος None, το όνομα δημιουργείται αυτόματα με βάση τον δοσμένο τύπο διάταξης <br/><br/>            (για παράδειγμα "Title Slide" ή "1_Title Slide", "2_..", κ.λπ.). |

### Παρατηρήσεις

1) Η προστιθέμενη διάταξη για την τιμή SlideLayoutType.Custom του `layout_type` δεν περιέχει σύμβολα κράτησης θέσης ούτε σχήματα.
2) Αντίστοιχο αυτής της μεθόδου είναι η μέθοδος **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste** που προσπελαύνεται μέσω της ιδιότητας [`IPresentation.layout_slides`](/slides/python-net/el/aspose.slides/ipresentation/layout_slides).

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Εκδιώκεται εάν περαστεί μη υποστηριζόμενη τιμή της παραμέτρου `layout_type`. Τύποι διάταξης που δεν υποστηρίζονται αυτή τη στιγμή: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Εκδιώκεται εάν η τιμή του ονόματος διάταξης `layout_name` είναι ήδη σε χρήση σε <br/>            αυτή τη συλλογή των διατάξεων. |



### Δείτε επίσης
* κλάση [`ILayoutSlide`](/slides/python-net/el/aspose.slides/ilayoutslide)
* κλάση [`IMasterLayoutSlideCollection`](/slides/python-net/el/aspose.slides/imasterlayoutslidecollection)
* απαρίθμηση [`SlideLayoutType`](/slides/python-net/el/aspose.slides/slidelayouttype)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)