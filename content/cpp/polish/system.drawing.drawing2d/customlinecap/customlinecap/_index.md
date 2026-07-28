---
title: CustomLineCap()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy nową instancję klasy CustomLineCap, która reprezentuje definiowane przez użytkownika zakończenie linii o określonych właściwościach.
type: docs
weight: 1
url: /pl/system.drawing.drawing2d/customlinecap/customlinecap/
---
## CustomLineCap::CustomLineCap(const SharedPtr\<GraphicsPath\>\&, const SharedPtr\<GraphicsPath\>\&, LineCap, float) konstruktor

Tworzy nową instancję klasy [CustomLineCap](../), która reprezentuje definiowane przez użytkownika zakończenie linii o określonych właściwościach.

```cpp
System::Drawing::Drawing2D::CustomLineCap::CustomLineCap(const SharedPtr<GraphicsPath> &fillPath, const SharedPtr<GraphicsPath> &strokePath, LineCap baseCap=LineCap::Flat, float baseInset=0)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| fillPath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Określa wypełnienie dla niestandardowego zakończenia |
| strokePath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Określa obrys niestandardowego zakończenia |
| baseCap | [LineCap](../../linecap/) | Podstawowe zakończenie linii, z którego tworzone jest niestandardowe zakończenie |
| baseInset | **float** | Określa odległość między linią a zakończeniem |

## Zobacz także

* Wyliczenie [LineCap](../../linecap/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [GraphicsPath](../../graphicspath/)
* Klasa [CustomLineCap](../)
* Przestrzeń nazw [System::Drawing::Drawing2D](../../)
* Biblioteka [Aspose.Slides](../../../)