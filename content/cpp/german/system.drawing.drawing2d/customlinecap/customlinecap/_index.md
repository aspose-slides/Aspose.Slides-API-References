---
title: CustomLineCap()
second_title: Aspose.Slides für C++ API-Referenz
description: Konstruiert eine neue Instanz der CustomLineCap-Klasse, die eine benutzerdefinierte Linienkappe mit den angegebenen Eigenschaften darstellt.
type: docs
weight: 1
url: /de/system.drawing.drawing2d/customlinecap/customlinecap/
---
## CustomLineCap::CustomLineCap(const SharedPtr\<GraphicsPath\>\&, const SharedPtr\<GraphicsPath\>\&, LineCap, float) Konstruktor


Konstruiert eine neue Instanz der [CustomLineCap](../) Klasse, die eine benutzerdefinierte Linienkappe mit den angegebenen Eigenschaften darstellt.

```cpp
System::Drawing::Drawing2D::CustomLineCap::CustomLineCap(const SharedPtr<GraphicsPath> &fillPath, const SharedPtr<GraphicsPath> &strokePath, LineCap baseCap=LineCap::Flat, float baseInset=0)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fillPath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Gibt eine Füllung für die benutzerdefinierte Kappe an |
| strokePath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Gibt eine Kontur der benutzerdefinierten Kappe an |
| baseCap | [LineCap](../../linecap/) | Die Basis-Liniekappe, aus der die benutzerdefinierte Kappe erstellt wird |
| baseInset | **float** | Gibt den Abstand zwischen der Linie und der Kappe an |

## Siehe auch

* Enum [LineCap](../../linecap/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsPath](../../graphicspath/)
* Class [CustomLineCap](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)