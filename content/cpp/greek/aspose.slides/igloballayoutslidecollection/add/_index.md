---
title: Add()
second_title: Aspose.Slides για C++ API Αναφορά
description: Προσθέτει μια νέα διαφάνεια διάταξης στην παρουσίαση.
type: docs
weight: 14
url: /el/aspose.slides/igloballayoutslidecollection/add/
---
## IGlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) method


Προσθέτει μια νέα διαφάνεια διάταξης στην παρουσίαση.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Διαφάνεια κύρια για μια νέα διάταξη. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Τύπος διάταξης για μια νέα διάταξη. Υποστηριζόμενοι τύποι διάταξης: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Όνομα για μια νέα διάταξη. Εάν το δοσμένο όνομα είναι ήδη σε χρήση, θα ριχθεί η ArgumentException. Εάν περάσει παράμετρος null, τότε το όνομα θα δημιουργηθεί αυτόματα με βάση τον δοσμένο τύπο διάταξης (για παράδειγμα \"Title Slide\" ή \"1_Title Slide\", \"2_..\", κλπ.). |

### Τιμή Επιστροφής

Διαφάνεια που προστέθηκε.
## Σημειώσεις



1) Η προστιθέμενη διάταξη για τιμή [SlideLayoutType::Custom](../../slidelayouttype/) του *layoutType* δεν περιέχει placeholders και σχήματα. 2) Η αναλογική μέθοδος είναι η μέθοδος [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/) που προσπελαύνεται μέσω της ιδιότητας [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/). 

## Δείτε Επίσης

* Απαρίθμηση [SlideLayoutType](../../slidelayouttype/)
* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [ILayoutSlide](../../ilayoutslide/)
* Κλάση [IMasterSlide](../../imasterslide/)
* Κλάση [String](../../../system/string/)
* Κλάση [IGlobalLayoutSlideCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)