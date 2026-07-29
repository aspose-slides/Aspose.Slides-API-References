---
title: CustomLineCap()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny instans av CustomLineCap-klassen som representerar en användardefinierad linjekap med de angivna egenskaperna.
type: docs
weight: 1
url: /sv/system.drawing.drawing2d/customlinecap/customlinecap/
---
## CustomLineCap::CustomLineCap(const SharedPtr\<GraphicsPath\>\&, const SharedPtr\<GraphicsPath\>\&, LineCap, float) constructor


Skapar en ny instans av [CustomLineCap](../)-klassen som representerar en användardefinierad linjekap med de angivna egenskaperna.

```cpp
System::Drawing::Drawing2D::CustomLineCap::CustomLineCap(const SharedPtr<GraphicsPath> &fillPath, const SharedPtr<GraphicsPath> &strokePath, LineCap baseCap=LineCap::Flat, float baseInset=0)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fillPath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Anger en fyllning för den anpassade kapen |
| strokePath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Anger en kontur för den anpassade kapen |
| baseCap | [LineCap](../../linecap/) | Baslinjekapen som den anpassade kapen skapas från |
| baseInset | **float** | Anger avståndet mellan linjen och kapen |

## Se även

* Enum [LineCap](../../linecap/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [GraphicsPath](../../graphicspath/)
* Klass [CustomLineCap](../)
* Namnrymd [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)