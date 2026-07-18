---
title: AddSmartArt()
second_title: Aspose.Slides για C++ API Reference
description: Δημιουργεί ένα διάγραμμα SmartArt και το προσθέτει στο τέλος της συλλογής σχημάτων.
type: docs
weight: 79
url: /el/aspose.slides/shapecollection/addsmartart/
---
## ShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) μέθοδος

Δημιουργεί ένα διάγραμμα [SmartArt](../../../aspose.slides.smartart/) και το προσθέτει στο τέλος της συλλογής σχημάτων.

```cpp
System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::ShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη x του πλαισίου του διαγράμματος, σε μονάδες points. |
| y | **float** | Η συντεταγμένη y του πλαισίου του διαγράμματος, σε μονάδες points. |
| width | **float** | Το πλάτος του πλαισίου του διαγράμματος, σε μονάδες points. |
| height | **float** | Το ύψος του πλαισίου του διαγράμματος, σε μονάδες points. |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | Ο τύπος διάταξης [SmartArt](../../../aspose.slides.smartart/). |

### Τιμή Επιστροφής

Το νεοδημιουργημένο [SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/).
## Παρατηρήσεις

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slide(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```

## Δείτε επίσης

* Enum [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* Κλάση [ShapeCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)