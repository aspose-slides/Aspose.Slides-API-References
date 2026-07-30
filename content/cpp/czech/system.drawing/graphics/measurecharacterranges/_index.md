---
title: MeasureCharacterRanges()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vrací pole oblastí, z nichž každá ohraničuje pozice znaků ve zadaném řetězci.
type: docs
weight: 508
url: /cs/system.drawing/graphics/measurecharacterranges/
---
## Graphics::MeasureCharacterRanges(const System::String\&, const SharedPtr\<Font\>\&, RectangleF, const SharedPtr\<StringFormat\>\&) metoda

Vrací pole oblastí, z nichž každá ohraničuje pozice znaků ve zadaném řetězci.

```cpp
ArrayPtr<SharedPtr<Region>> System::Drawing::Graphics::MeasureCharacterRanges(const System::String &text, const SharedPtr<Font> &font, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | Řetězec, který se má měřit |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Písmo použité během měření řetězce |
| layoutRect | [RectangleF](../../rectanglef/) | Obdélník rozvržení použitý během měření řetězce |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\>\& | Formát řetězce, který obsahuje rozsahy znaků k měření |

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Region](../../region/)
* Třída [String](../../../system/string/)
* Třída [Font](../../font/)
* Třída [RectangleF](../../rectanglef/)
* Třída [StringFormat](../../stringformat/)
* Třída [Graphics](../)
* Jmenný prostor [System::Drawing](../../)
* Knihovna [Aspose.Slides](../../../)