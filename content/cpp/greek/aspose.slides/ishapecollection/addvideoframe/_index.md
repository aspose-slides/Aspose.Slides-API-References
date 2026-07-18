---
title: AddVideoFrame()
second_title: Αναφορά API για Aspose.Slides για C++ 
description: Δημιουργεί ένα νέο πλαίσιο βίντεο και το προσθέτει στο τέλος της συλλογής σχημάτων.
type: docs
weight: 170
url: /el/aspose.slides/ishapecollection/addvideoframe/
---
## IShapeCollection::AddVideoFrame(float, float, float, float, System::String) μέθοδος


Δημιουργεί ένα νέο πλαίσιο βίντεο και το προσθέτει στο τέλος της συλλογής σχημάτων.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου βίντεο, σε μονάδες σημείου. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου βίντεο, σε μονάδες σημείου. |
| width | **float** | Το πλάτος του νέου πλαισίου βίντεο, σε μονάδες σημείου. |
| height | **float** | Το ύψος του νέου πλαισίου βίντεο, σε μονάδες σημείου. |
| fname | [System::String](../../../system/string/) | Η διαδρομή ή το όνομα του αρχείου βίντεο προς ενσωμάτωση. |

### Τιμή Επιστροφής

Το νέο δημιουργημένο [IVideoFrame](../../ivideoframe/).

## IShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) μέθοδος


Δημιουργεί ένα νέο πλαίσιο βίντεο και το προσθέτει στο τέλος της συλλογής σχημάτων.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου βίντεο, σε μονάδες σημείου. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου βίντεο, σε μονάδες σημείου. |
| width | **float** | Το πλάτος του νέου πλαισίου βίντεο, σε μονάδες σημείου. |
| height | **float** | Το ύψος του νέου πλαισίου βίντεο, σε μονάδες σημείου. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Το [IVideo](../../ivideo/) προς ενσωμάτωση στο πλαίσιο βίντεο. |

### Τιμή Επιστροφής

Το νέο δημιουργημένο [IVideoFrame](../../ivideoframe/).

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IVideoFrame](../../ivideoframe/)
* Κλάση [String](../../../system/string/)
* Κλάση [IShapeCollection](../)
* Κλάση [IVideo](../../ivideo/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)