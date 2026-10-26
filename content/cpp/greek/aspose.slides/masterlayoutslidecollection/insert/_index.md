---
title: Insert()
second_title: Aspose.Slides για C++ Αναφορά API
description: Εισάγει μια νέα διαφάνεια διάταξης στη συγκεκριμένη θέση της συλλογής.
type: docs
weight: 40
url: /el/aspose.slides/masterlayoutslidecollection/insert/
---
## MasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) method


Εισάγει μια νέα διαφάνεια διάταξης στη συγκεκριμένη θέση της συλλογής.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Δείκτης της νέας διαφάνειας. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Τύπος διάταξης για μια νέα διάταξη. Υποστηριζόμενοι τύποι διάταξης: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Άλλοι τύποι διάταξης δεν υποστηρίζονται αυτή τη στιγμή: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Όνομα για μια νέα διάταξη. Εάν το δοθέν όνομα χρησιμοποιείται ήδη, θα προκληθεί το ArgumentException. Εάν περαστεί παράμετρος null, τότε το όνομα παράγεται αυτόματα με βάση τον δοθέν τύπο διάταξης (για παράδειγμα "Title Slide" ή "1_Title Slide", "2_..", κ.λπ.). |

### Return Value

Η εισαχθείσα διαφάνεια.

## Remarks

Η εισαχθείσα διάταξη για την τιμή [SlideLayoutType::Custom](../../slidelayouttype/) του *layoutType* δεν περιέχει **κανένα** placeholder και **κανένα** shape.

## See Also

* Απαρίθμηση [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ILayoutSlide](../../ilayoutslide/)
* Κλάση [String](../../../system/string/)
* Κλάση [MasterLayoutSlideCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)