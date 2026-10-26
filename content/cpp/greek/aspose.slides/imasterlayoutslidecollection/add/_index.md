---
title: Add()
second_title: Αναφορά API του Aspose.Slides για C++
description: Προσθέτει μια νέα διαφάνεια διάταξης στο τέλος της συλλογής.
type: docs
weight: 27
url: /el/aspose.slides/imasterlayoutslidecollection/add/
---
## IMasterLayoutSlideCollection::Add(SlideLayoutType, System::String) μέθοδος


Προσθέτει μια νέα διαφάνεια διάταξης στο τέλος της συλλογής.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName)=0
```


### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Τύπος διάταξης για μια νέα διάταξη. Υποστηριζόμενοι τύποι διάταξης: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Άλλοι τύποι διάταξης δεν υποστηρίζονται αυτή τη στιγμή: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Όνομα για μια νέα διάταξη. Εάν το παρεχόμενο όνομα είναι ήδη σε χρήση θα ρριχθεί η ArgumentException. Εάν περαστεί παράμετρος null, τότε το όνομα παράγεται αυτόματα σύμφωνα με τον τύπο διάταξης που έχει δοθεί (για παράδειγμα \"Title Slide\" ή \"1_Title Slide\", \"2_..\", κλπ.). |

### Return Value

Προστέθηκε διαφάνεια.

## Remarks



1) Η προστιθέμενη διάταξη για την τιμή [SlideLayoutType::Custom](../../slidelayouttype/) του *layoutType* δεν περιέχει placeholders και δεν έχει σχήματα. 2) Η αναλογική αυτής της μεθόδου είναι η μέθοδος [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/) η οποία προσπελαύται μέσω της ιδιότητας [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/). 

## See Also

* Απαρίθμηση [SlideLayoutType](../../slidelayouttype/)
* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [ILayoutSlide](../../ilayoutslide/)
* Κλάση [String](../../../system/string/)
* Κλάση [IMasterLayoutSlideCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)