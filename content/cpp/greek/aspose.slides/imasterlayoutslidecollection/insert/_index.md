---
title: Insert()
second_title: Aspose.Slides για C++ Αναφορά API
description: Εισάγει μια νέα διαφάνεια διάταξης στη συγκεκριμένη θέση της συλλογής.
type: docs
weight: 40
url: /el/aspose.slides/imasterlayoutslidecollection/insert/
---
## IMasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) μέθοδος

Εισάγει μια νέα διαφάνεια διάταξης στη συγκεκριμένη θέση της συλλογής.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Δείκτης της νέας διαφάνειας. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Τύπος διάταξης για μια νέα διάταξη. Υποστηριζόμενοι τύποι διάταξης: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Άλλοι τύποι διάταξης δεν υποστηρίζονται αυτή τη στιγμή: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Όνομα για μια νέα διάταξη. Εάν το δοθέν όνομα είναι ήδη σε χρήση, θα ριχτεί η ArgumentException. Εάν περαστεί null παράμετρος, τότε το όνομα θα δημιουργηθεί αυτόματα με βάση τον δοσμένο τύπο διάταξης (για παράδειγμα "Title Slide" ή "1_Title Slide", "2_..", κλπ.). |

### Τιμή Επιστροφής

Η εισαχθείσα διαφάνεια.

## Σχόλια

Η εισαχθείσα διάταξη για την τιμή [SlideLayoutType::Custom](../../slidelayouttype/) του *layoutType* δεν περιέχει δεσμευτικά σημεία και δεν περιέχει σχήματα. 

## Δείτε Επίσης

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ILayoutSlide](../../ilayoutslide/)
* Κλάση [String](../../../system/string/)
* Κλάση [IMasterLayoutSlideCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)