---
title: InsertSummaryZoomFrame()
second_title: Αναφορά API Aspose.Slides για C++
description: Δημιουργεί ένα νέο πλαίσιο Summary Zoom και το εισάγει στη συλλογή σχήματος στη συγκεκριμένη θέση.
type: docs
weight: 157
url: /el/aspose.slides/ishapecollection/insertsummaryzoomframe/
---
## IShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) μέθοδος


Δημιουργεί ένα νέο πλαίσιο Summary Zoom και το εισάγει στη συλλογή σχήματος στη συγκεκριμένη θέση.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το πλαίσιο Summary Zoom. |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου Summary Zoom, σε points. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου Summary Zoom, σε points. |
| width | **float** | Το πλάτος του νέου πλαισίου Summary Zoom, σε points. |
| height | **float** | Το ύψος του νέου πλαισίου Summary Zoom, σε points. |

### Τιμή Επιστροφής

Το νεοδημιουργημένο [ISummaryZoomFrame](../../isummaryzoomframe/).

## Παρατηρήσεις


Αυτή η μέθοδος δημιουργεί ένα πλαίσιο Summary Zoom που συγκεντρώνει συνδέσεις περίληψης για όλες τις ενότητες στην παρουσίαση. 

Αυτό το παράδειγμα δείχνει τη δημιουργία και την εισαγωγή ενός αντικειμένου Summary Zoom στη συγκεκριμένη θέση μιας συλλογής (υποθέστε ότι υπάρχουν τουλάχιστον δύο ενότητες στην παρουσίαση "Presentation.pptx"): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```


## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISummaryZoomFrame](../../isummaryzoomframe/)
* Κλάση [IShapeCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)