---
title: Add()
second_title: Aspose.Slides για C++ Αναφορά API
description: Προσθέτει μια νέα διαφάνεια διάταξης στο τέλος της συλλογής.
type: docs
weight: 27
url: /el/aspose.slides/masterlayoutslidecollection/add/
---
## MasterLayoutSlideCollection::Add(SlideLayoutType, System::String) μέθοδος

Προσθέτει μια νέα layout slide στο τέλος της collection.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Τύπος διάταξης για μια νέα διάταξη. Υποστηριζόμενοι τύποι διάταξης: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Άλλοι τύποι διάταξης δεν υποστηρίζονται αυτή τη στιγμή: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Όνομα για μια νέα διάταξη. Εάν το δοσμένο όνομα χρησιμοποιείται ήδη, θα εξαπολυθεί η ArgumentException. Εάν δοθεί παράμετρος null, τότε το όνομα θα δημιουργηθεί αυτόματα με βάση τον δοσμένο τύπο διάταξης (για παράδειγμα \"Title Slide\" ή \"1_Title Slide\", \"2_..\", κλπ.). |

### Τιμή Επιστροφής

Προστέθηκε slide.

## Παρατηρήσεις

1) Προστέθηκε διάταξη για την τιμή [SlideLayoutType::Custom](../../slidelayouttype/) του *layoutType* που δεν περιέχει ούτε placeholders ούτε σχήματα. 2) Αντίστοιχο αυτής της μεθόδου είναι η μέθοδος [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/) η οποία προσπελαύνεται μέσω της ιδιότητας [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/).

## Δείτε επίσης

* Απαρίθμηση [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ILayoutSlide](../../ilayoutslide/)
* Κλάση [String](../../../system/string/)
* Κλάση [MasterLayoutSlideCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)