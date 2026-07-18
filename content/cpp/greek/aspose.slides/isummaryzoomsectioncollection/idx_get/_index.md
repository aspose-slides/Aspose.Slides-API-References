---
title: idx_get()
second_title: Aspose.Slides για την Αναφορά API C++
description: Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. Μόνο για ανάγνωση ISummaryZoomSection.
type: docs
weight: 1
url: /el/aspose.slides/isummaryzoomsectioncollection/idx_get/
---
## ISummaryZoomSectionCollection::idx_get(int32_t) μέθοδος


Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. Μόνο για ανάγνωση [ISummaryZoomSection](../../isummaryzoomsection/).

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::idx_get(int32_t index)=0
```

## Σχόλια


Το παράδειγμα δείχνει πώς να λαμβάνετε το στοιχείο Summary Zoom [Section](../../section/) με δείκτη: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto zoomSection = collection->idx_get(1);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISummaryZoomSection](../../isummaryzoomsection/)
* Κλάση [ISummaryZoomSectionCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)