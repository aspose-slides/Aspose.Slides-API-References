---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί ένα νέο πλαίσιο Summary Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων.
type: docs
weight: 157
url: /el/aspose.slides/shapecollection/addsummaryzoomframe/
---
## ShapeCollection::AddSummaryZoomFrame(float, float, float, float) μέθοδος


Δημιουργεί ένα νέο πλαίσιο Summary Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η x-συντεταγμένη του νέου πλαισίου Summary Zoom, σε points. |
| y | **float** | Η y-συντεταγμένη του νέου πλαισίου Summary Zoom, σε points. |
| width | **float** | Το πλάτος του νέου πλαισίου Summary Zoom, σε points. |
| height | **float** | Το ύψος του νέου πλαισίου Summary Zoom, σε points. |

### Return Value

Η νεοδημιουργημένη [ISummaryZoomFrame](../../isummaryzoomframe/).
## Σχόλια


Αυτή η μέθοδος δημιουργεί ένα νέο Summary Zoom και τοποθετεί μια συλλογή αντικειμένων σε αυτό για όλα τα τμήματα σε αυτήν την παρουσίαση. 

Αυτό το παράδειγμα επιδεικνύει την προσθήκη ενός αντικειμένου Summary Zoom στο τέλος μιας συλλογής (υποθέστε ότι υπάρχουν τουλάχιστον δύο τμήματα στην παρουσίαση \"Presentation.pptx\"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```


## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISummaryZoomFrame](../../isummaryzoomframe/)
* Κλάση [ShapeCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)