---
title: CustomLineCap()
second_title: Aspose.Slides a C++ API hivatkozás
description: Létrehoz egy új példányt a CustomLineCap osztályból, amely felhasználó által definiált vonal sapkát reprezentál a megadott tulajdonságokkal.
type: docs
weight: 1
url: /hu/system.drawing.drawing2d/customlinecap/customlinecap/
---
## CustomLineCap::CustomLineCap(const SharedPtr\<GraphicsPath\>\&, const SharedPtr\<GraphicsPath\>\&, LineCap, float) konstruktor

Létrehoz egy új példányt a(z) [CustomLineCap](../) osztályból, amely felhasználó által definiált vonal sapkát reprezentál a megadott tulajdonságokkal.

```cpp
System::Drawing::Drawing2D::CustomLineCap::CustomLineCap(const SharedPtr<GraphicsPath> &fillPath, const SharedPtr<GraphicsPath> &strokePath, LineCap baseCap=LineCap::Flat, float baseInset=0)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fillPath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Megadja az egyedi sapka kitöltését |
| strokePath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Megadja az egyedi sapka körvonalát |
| baseCap | [LineCap](../../linecap/) | Az alap vonal sapka, amelyből az egyedi sapka létrejön |
| baseInset | **float** | Megadja a vonal és a sapka közötti távolságot |

## Lásd még

* Enum [LineCap](../../linecap/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [GraphicsPath](../../graphicspath/)
* Osztály [CustomLineCap](../)
* Névtér [System::Drawing::Drawing2D](../../)
* Könyvtár [Aspose.Slides](../../../)