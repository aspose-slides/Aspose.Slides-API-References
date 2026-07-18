---
title: Add()
second_title: Aspose.Slides για C++ API Αναφορά
description: Προσθέτει μια νέα διαφάνεια διάταξης στην παρουσίαση.
type: docs
weight: 14
url: /el/aspose.slides/globallayoutslidecollection/add/
---
## GlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) μέθοδος

Προσθέτει μια νέα διαφάνεια διάταξης στην παρουσίαση.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Διαφάνεια Master για μια νέα διάταξη. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Τύπος διάταξης για μια νέα διάταξη. Υποστηριζόμενοι τύποι διάταξης: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Άλλοι τύποι διάταξης δεν υποστηρίζονται αυτή τη στιγμή: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Όνομα για μια νέα διάταξη. Εάν το δοσμένο όνομα είναι ήδη σε χρήση, θα προκληθεί ArgumentException. Εάν περαστεί παράμετρος null, τότε το όνομα δημιουργείται αυτόματα ανάλογα με τον δοσμένο τύπο διάταξης (για παράδειγμα “Title Slide” ή “1_Title Slide”, “2_..”, κ.λπ.). |

### Τιμή Επιστροφής

Διαφάνεια που προστέθηκε.

## Παρατηρήσεις

1) Προστέθηκε διάταξη για την τιμή [SlideLayoutType::Custom](../../slidelayouttype/) του *layoutType* που δεν περιέχει placeholders και δεν έχει σχήματα. 2) Αναλογικά, αυτή η μέθοδος είναι η μέθοδος [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/) προσπελαζόμενη μέσω της ιδιότητας [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/).

## Δείτε επίσης

* Απαρίθμηση [SlideLayoutType](../../slidelayouttype/)
* Δήλωση τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [ILayoutSlide](../../ilayoutslide/)
* Κλάση [IMasterSlide](../../imasterslide/)
* Κλάση [String](../../../system/string/)
* Κλάση [GlobalLayoutSlideCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)