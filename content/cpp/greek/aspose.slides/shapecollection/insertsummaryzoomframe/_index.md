---
title: InsertSummaryZoomFrame()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί ένα νέο Summary Zoom frame και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη.
type: docs
weight: 170
url: /el/aspose.slides/shapecollection/insertsummaryzoomframe/
---
## ShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) μέθοδος


Δημιουργεί ένα νέο Summary Zoom frame και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το Summary Zoom frame. |
| x | **float** | Η συντεταγμένη x του νέου Summary Zoom frame, σε σημεία. |
| y | **float** | Η συντεταγμένη y του νέου Summary Zoom frame, σε σημεία. |
| width | **float** | Το πλάτος του νέου Summary Zoom frame, σε σημεία. |
| height | **float** | Το ύψος του νέου Summary Zoom frame, σε σημεία. |

### Τιμή Επιστροφής

Το πρόσφατα δημιουργημένο [ISummaryZoomFrame](../../isummaryzoomframe/).

## Παρατηρήσεις

Αυτή η μέθοδος δημιουργεί ένα Summary Zoom frame που συγκεντρώνει συνδέσμους σύνοψης για όλες τις ενότητες στην παρουσίαση. 

Αυτό το παράδειγμα δείχνει τη δημιουργία και την εισαγωγή ενός Summary Zoom αντικειμένου στον καθορισμένο δείκτη μιας συλλογής (υποθέστε ότι υπάρχουν τουλάχιστον δύο ενότητες στην παρουσίαση "Presentation.pptx"): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```


## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISummaryZoomFrame](../../isummaryzoomframe/)
* Κλάση [ShapeCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)