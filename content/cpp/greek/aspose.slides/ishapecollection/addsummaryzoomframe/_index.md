---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί ένα νέο πλαίσιο Summary Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων.
type: docs
weight: 144
url: /el/aspose.slides/ishapecollection/addsummaryzoomframe/
---
## IShapeCollection::AddSummaryZoomFrame(float, float, float, float) μέθοδος

Δημιουργεί ένα νέο πλαίσιο Summary Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Η x-συντεταγμένη του νέου πλαισίου Summary Zoom, σε μονάδες σημείου. |
| y | **float** | Η y-συντεταγμένη του νέου πλαισίου Summary Zoom, σε μονάδες σημείου. |
| width | **float** | Το πλάτος του νέου πλαισίου Summary Zoom, σε μονάδες σημείου. |
| height | **float** | Το ύψος του νέου πλαισίου Summary Zoom, σε μονάδες σημείου. |

### Return Value

Το νεοδημιουργημένο [ISummaryZoomFrame](../../isummaryzoomframe/).

## Remarks

Αυτή η μέθοδος δημιουργεί ένα πλαίσιο Summary Zoom που συγκεντρώνει συνδέσμους περίληψης για όλες τις ενότητες στην παρουσίαση.

Αυτό το παράδειγμα δείχνει πώς να προσθέσετε ένα αντικείμενο Summary Zoom στο τέλος μιας συλλογής (υποθέτουμε ότι υπάρχουν τουλάχιστον δύο ενότητες στην παρουσίαση "Presentation.pptx"):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomFrame](../../isummaryzoomframe/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)