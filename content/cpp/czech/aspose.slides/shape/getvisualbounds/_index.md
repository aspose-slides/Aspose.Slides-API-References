---
title: GetVisualBounds()
second_title: Aspose.Slides pro C++ API Reference
description: Získá vizuální ohraničení tvaru vypočítané z jeho vykresleného obsahu.
type: docs
weight: 677
url: /cs/aspose.slides/shape/getvisualbounds/
---
## Shape::GetVisualBounds() metoda

Získá vizuální ohraničení tvaru vypočítané z jeho vykresleného obsahu.

```cpp
System::Drawing::RectangleF Aspose::Slides::Shape::GetVisualBounds()
```

### Návratová hodnota

[System::Drawing::RectangleF](../../../system.drawing/rectanglef/) představuje vizuální ohraničení tvaru v souřadnicích snímku.
## Poznámky

Vrácený obdélník představuje osově zarovnané ohraničení veškerého obsahu vytvořeného tvarem během vykreslování v souřadnicovém prostoru snímku.

Tato ohraničení se mohou lišit od modelových ohraničení tvaru ([Shape::X](../), [Shape::Y](../), [Shape::Width](../), [Shape::Height](../)) a mohou obsahovat záporné souřadnice, pokud se vykreslený obsah rozprostírá za počátek snímku.

Vizuální ohraničení zohledňuje aspekty související s vykreslováním, jako jsou transformace (například otáčení), šířka čáry a spoje, rozvržení a přetečení textu, [SmartArt](../../../aspose.slides.smartart/) geometrie a další efekty rozvržení, které ovlivňují konečný vzhled tvaru při vykreslení.

Vrácená ohraničení nejsou oříznuta na obdélník snímku.

## Viz také

* Třída [RectangleF](../../../system.drawing/rectanglef/)
* Třída [Shape](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)