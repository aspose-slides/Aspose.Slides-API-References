---
title: AddPath()
second_title: Aspose.Slides C++ API Referenciája
description: Hozzáadja a megadott útvonalat a jelenlegi objektum által képviselt útvonalhoz.
type: docs
weight: 222
url: /hu/system.drawing.drawing2d/graphicspath/addpath/
---
## GraphicsPath::AddPath(const SharedPtr\<GraphicsPath\>\&, bool) metódus


Adds the specified path to the path represented by the current object.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPath(const SharedPtr<GraphicsPath> &path, bool connect)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../)\>\& | A hozzáadandó útvonal |
| connect | **bool** | A true érték azt jelzi, hogy a **path** utolsó első alakja a jelenlegi objektum által képviselt útvonal utolsó alakjának része; a false érték azt jelzi, hogy a **path** első alakja és a jelenlegi objektum által képviselt útvonal utolsó alakja különálló alakok |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [GraphicsPath](../)
* Névtér [System::Drawing::Drawing2D](../../)
* Könyvtár [Aspose.Slides](../../../)