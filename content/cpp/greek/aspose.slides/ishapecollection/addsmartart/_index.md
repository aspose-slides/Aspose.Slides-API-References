---
title: AddSmartArt()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα διάγραμμα SmartArt και το προσθέτει στο τέλος της συλλογής σχημάτων.
type: docs
weight: 40
url: /el/aspose.slides/ishapecollection/addsmartart/
---
## IShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) μέθοδος

Δημιουργεί ένα διάγραμμα [SmartArt](../../../aspose.slides.smartart/) και το προσθέτει στο τέλος της συλλογής σχημάτων.

```cpp
virtual System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::IShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη x του πλαισίου του διαγράμματος, σε σημεία. |
| y | **float** | Η συντεταγμένη y του πλαισίου του διαγράμματος, σε σημεία. |
| width | **float** | Το πλάτος του πλαισίου του διαγράμματος, σε σημεία. |
| height | **float** | Το ύψος του πλαισίου του διαγράμματος, σε σημεία. |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | Ο τύπος διάταξης [SmartArt](../../../aspose.slides.smartart/). |

### Τιμή επιστροφής

Το νέο δημιουργημένο [SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/).

## Παρατηρήσεις

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slide(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```

## Δείτε επίσης

* Απαρίθμηση [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* Τύπος ορισμού [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* Κλάση [IShapeCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)