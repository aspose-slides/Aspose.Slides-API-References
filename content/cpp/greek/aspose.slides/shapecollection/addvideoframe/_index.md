---
title: AddVideoFrame()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί ένα νέο πλαίσιο βίντεο και το προσθέτει στο τέλος της συλλογής σχήματος.
type: docs
weight: 209
url: /el/aspose.slides/shapecollection/addvideoframe/
---
## ShapeCollection::AddVideoFrame(float, float, float, float, System::String) μέθοδος

Δημιουργεί ένα νέο πλαίσιο βίντεο και το προσθέτει στο τέλος της συλλογής σχήματος.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου βίντεο, σε σημεία. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου βίντεο, σε σημεία. |
| width | **float** | Το πλάτος του νέου πλαισίου βίντεο, σε σημεία. |
| height | **float** | Το ύψος του νέου πλαισίου βίντεο, σε σημεία. |
| fname | [System::String](../../../system/string/) | Η διαδρομή ή το όνομα του αρχείου βίντεο για ενσωμάτωση. |

### Τιμή επιστροφής

Το νεοδημιουργημένο [IVideoFrame](../../ivideoframe/).

## ShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) μέθοδος

Δημιουργεί ένα νέο πλαίσιο βίντεο και το προσθέτει στο τέλος της συλλογής σχήματος.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου βίντεο, σε σημεία. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου βίντεο, σε σημεία. |
| width | **float** | Το πλάτος του νέου πλαισίου βίντεο, σε σημεία. |
| height | **float** | Το ύψος του νέου πλαισίου βίντεο, σε σημεία. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Το [IVideo](../../ivideo/) για ενσωμάτωση στο πλαίσιο βίντεο. |

### Τιμή επιστροφής

Το νεοδημιουργημένο [IVideoFrame](../../ivideoframe/).

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IVideoFrame](../../ivideoframe/)
* Κλάση [String](../../../system/string/)
* Κλάση [ShapeCollection](../)
* Κλάση [IVideo](../../ivideo/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)