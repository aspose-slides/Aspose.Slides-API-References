---
title: MeasureCharacterRanges()
second_title: Aspose.Slides a C++ API referencia
description: Visszaad egy tömböt a régiókból, amelyek mindegyike határolja a karakterpozíciókat a megadott karakterláncban.
type: docs
weight: 508
url: /hu/system.drawing/graphics/measurecharacterranges/
---
## Graphics::MeasureCharacterRanges(const System::String&, const SharedPtr<Font>&, RectangleF, const SharedPtr<StringFormat>&) metódus


Visszaad egy tömböt a régiókból, amelyek mindegyike határolja a karakterpozíciókat a megadott karakterláncban.

```cpp
ArrayPtr<SharedPtr<Region>> System::Drawing::Graphics::MeasureCharacterRanges(const System::String &text, const SharedPtr<Font> &font, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)& | A mérendő karakterlánc |
| font | const [SharedPtr](../../../system/sharedptr/)<[Font](../../font/)>& | A karakterlánc méréséhez használt betűkészlet |
| layoutRect | [RectangleF](../../rectanglef/) | A mérés során használt elrendezési téglalap |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)<[StringFormat](../../stringformat/)>& | A karakterlánc formátuma, amely tartalmazza a mérendő karaktertartományokat |

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Region](../../region/)
* Osztály [String](../../../system/string/)
* Osztály [Font](../../font/)
* Osztály [RectangleF](../../rectanglef/)
* Osztály [StringFormat](../../stringformat/)
* Osztály [Graphics](../)
* Névtér [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)