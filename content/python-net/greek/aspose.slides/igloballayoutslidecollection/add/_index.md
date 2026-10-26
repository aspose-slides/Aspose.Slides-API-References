---
title: add method
second_title: Aspose.Slides για Python μέσω .NET αναφορά API
description: 
type: docs
url: /el/aspose.slides/igloballayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
Προσθέτει μια νέα διαφάνεια διάταξης στην παρουσίαση.

### Returns

Added slide.



```python
def add(self, master, layout_type, layout_name):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/el/aspose.slides/imasterslide) | Διφάνεια προτύπου για μια νέα διάταξη. |
| layout_type | [`SlideLayoutType`](/slides/python-net/el/aspose.slides/slidelayouttype) | Τύπος διάταξης για μια νέα διάταξη.<br/><br/>            Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Όνομα για μια νέα διάταξη. Εάν το δοσμένο όνομα είναι ήδη σε χρήση θα ριχτεί η ArgumentException.<br/><br/>            Εάν περάσει παράμετρος None, τότε το όνομα δημιουργείται αυτόματα με βάση τον τύπο διάταξης που δόθηκε <br/><br/>            (για παράδειγμα "Title Slide" ή "1_Title Slide", "2_..", κ.λπ.). |

### Remarks

1) Η προσαρμοσμένη διάταξη για την τιμή SlideLayoutType.Custom του `layout_type` δεν περιέχει placeholders και δεν έχει σχήματα.  
2) Αντίστοιχη της μεθόδου αυτής είναι η μέθοδος **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste** που προσπελάζεται με την ιδιότητα [`IMasterSlide.layout_slides`](/slides/python-net/el/aspose.slides/imasterslide/layout_slides).

### Exceptions

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Ρίχνεται εάν περαστεί μη υποστηριζόμενη τιμή για την παράμετρο `layout_type`. Τύποι διάταξης που δεν υποστηρίζονται αυτήν τη στιγμή: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | Ρίχνεται εάν `master` είναι None. |
| **RuntimeError(Proxy error(ArgumentException))** | Ρίχνεται εάν `master` ανήκει σε διαφορετική παρουσίαση. |
| **RuntimeError(Proxy error(ArgumentException))** | Ρίχνεται εάν η τιμή του ονόματος διάταξης `layout_name` είναι ήδη σε χρήση στη συλλογή των διατάξεων του `master`. |



### See Also
* κλάση [`IGlobalLayoutSlideCollection`](/slides/python-net/el/aspose.slides/igloballayoutslidecollection)
* κλάση [`ILayoutSlide`](/slides/python-net/el/aspose.slides/ilayoutslide)
* κλάση [`IMasterSlide`](/slides/python-net/el/aspose.slides/imasterslide)
* απαρίθμηση [`SlideLayoutType`](/slides/python-net/el/aspose.slides/slidelayouttype)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)