---
title: CustomLineCap()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří novou instanci třídy CustomLineCap, která představuje uživatelsky definovaný koncový bod čáry se zadanými vlastnostmi.
type: docs
weight: 1
url: /cs/system.drawing.drawing2d/customlinecap/customlinecap/
---
## CustomLineCap::CustomLineCap(const SharedPtr\<GraphicsPath\>\&, const SharedPtr\<GraphicsPath\>\&, LineCap, float) konstruktor

Vytvoří novou instanci třídy [CustomLineCap](../), která představuje uživatelem definovaný koncový bod čáry se zadanými vlastnostmi.

```cpp
System::Drawing::Drawing2D::CustomLineCap::CustomLineCap(const SharedPtr<GraphicsPath> &fillPath, const SharedPtr<GraphicsPath> &strokePath, LineCap baseCap=LineCap::Flat, float baseInset=0)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| fillPath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Určuje výplň pro vlastní koncový bod |
| strokePath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Určuje obrys vlastní koncového bodu |
| baseCap | [LineCap](../../linecap/) | Základní koncový bod čáry, ze kterého je vytvořen vlastní koncový bod |
| baseInset | **float** | Určuje vzdálenost mezi čarou a koncovým bodem |

## Viz také

* Enum [LineCap](../../linecap/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [GraphicsPath](../../graphicspath/)
* Třída [CustomLineCap](../)
* Jmenný prostor [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)