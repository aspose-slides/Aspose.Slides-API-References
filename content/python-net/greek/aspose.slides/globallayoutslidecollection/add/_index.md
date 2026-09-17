---
title: add method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/globallayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
Προσθέτει μια νέα διαφάνεια διάταξης στην παρουσίαση.

### Επιστρέφει

Η προστεθείσα διαφάνεια.



```python
def add(self, master, layout_type, layout_name):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/el/aspose.slides/imasterslide) | Κύρια (master) διαφάνεια για μια νέα διάταξη. |
| layout_type | [`SlideLayoutType`](/slides/python-net/el/aspose.slides/slidelayouttype) | Τύπος διάταξης για μια νέα διάταξη.<br/><br/>            Υποστηριζόμενοι τύποι διάταξης: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Άλλοι τύποι διάταξης δεν υποστηρίζονται αυτή τη στιγμή: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Όνομα για μια νέα διάταξη. Εάν το δοθέν όνομα χρησιμοποιείται ήδη, θα εξαχθεί ArgumentException.<br/><br/>            Εάν περάσει η παράμετρος None, τότε το όνομα δημιουργείται αυτόματα με βάση τον δοθέν τύπο διάταξης <br/><br/>            (π.χ. "Title Slide" ή "1_Title Slide", "2_..", κλπ.). |

### Σχόλια

1) Η προστιθέμενη διάταξη για την τιμή SlideLayoutType.Custom του `layout_type` δεν περιέχει εμφανίσεις κράτησης θέσης και δεν έχει σχήματα.  
2) Η αναλογική μέθοδος είναι η μέθοδος **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste** που προσπελάζεται μέσω της ιδιότητας [`IMasterSlide.layout_slides`](/slides/python-net/el/aspose.slides/imasterslide/layout_slides).

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Εκτοξεύεται εάν περαστεί μη υποστηριζόμενη τιμή της παραμέτρου `layout_type`. Τύποι διάταξης που δεν υποστηρίζονται αυτή τη στιγμή: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | Εκτοξεύεται εάν το `master` είναι None. |
| **RuntimeError(Proxy error(ArgumentException))** | Εκτοξεύεται εάν το `master` ανήκει σε άλλη παρουσίαση. |
| **RuntimeError(Proxy error(ArgumentException))** | Εκτοξεύεται εάν η τιμή του ονόματος διάταξης `layout_name` χρησιμοποιείται ήδη στη <br/>            συλλογή των διατάξεων του `master`. |

### Δείτε επίσης
* κλάση [`GlobalLayoutSlideCollection`](/slides/python-net/el/aspose.slides/globallayoutslidecollection)
* κλάση [`ILayoutSlide`](/slides/python-net/el/aspose.slides/ilayoutslide)
* κλάση [`IMasterSlide`](/slides/python-net/el/aspose.slides/imasterslide)
* απαρίθμηση [`SlideLayoutType`](/slides/python-net/el/aspose.slides/slidelayouttype)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)