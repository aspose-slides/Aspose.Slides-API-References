---
title: add method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/masterlayoutslidecollection/add/
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
| layout_name | **str** | Όνομα για μια νέα διάταξη. Εάν το δοσμένο όνομα είναι ήδη σε χρήση θα ριχτεί το ArgumentException.<br/><br/>            Εάν δοθεί παράμετρος None, τότε το όνομα παραγέγεται αυτόματα σύμφωνα με τον δοσμένο τύπο διάταξης <br/><br/>            (π.χ. "Title Slide" ή "1_Title Slide", "2_..", κλπ.). |

### Παρατηρήσεις

1) Η προστιθέμενη διάταξη για την τιμή SlideLayoutType.Custom του `layout_type` δεν περιέχει placeholder και κανένα σχήμα.  
2) Ανάλογη αυτής της μεθόδου είναι η μέθοδος **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste** που προσπελάζεται με την ιδιότητα [`IPresentation.layout_slides`](/slides/python-net/el/aspose.slides/ipresentation/layout_slides).

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Εκτοπίζεται εάν δοθεί μη υποστηριζόμενη τιμή για την παράμετρο `layout_type`. Τύποι διάταξης που δεν υποστηρίζονται αυτή τη στιγμή: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Εκτοπίζεται εάν η τιμή του ονόματος διάταξης `layout_name` είναι ήδη σε χρήση σε <br/>            αυτή τη συλλογή των διατάξεων. |

### Δείτε επίσης
* κλάση [`ILayoutSlide`](/slides/python-net/el/aspose.slides/ilayoutslide)
* κλάση [`MasterLayoutSlideCollection`](/slides/python-net/el/aspose.slides/masterlayoutslidecollection)
* απαρίθμηση [`SlideLayoutType`](/slides/python-net/el/aspose.slides/slidelayouttype)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)