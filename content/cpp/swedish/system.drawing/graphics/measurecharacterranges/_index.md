---
title: MeasureCharacterRanges()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en array av regioner där varje region avgränsar teckenpositioner i den angivna strängen.
type: docs
weight: 508
url: /sv/system.drawing/graphics/measurecharacterranges/
---
## Graphics::MeasureCharacterRanges(const System::String\&, const SharedPtr\<Font\>\&, RectangleF, const SharedPtr\<StringFormat\>\&) metod


Returnerar en matris av regioner där varje region avgränsar teckenpositioner i den angivna strängen.

```cpp
ArrayPtr<SharedPtr<Region>> System::Drawing::Graphics::MeasureCharacterRanges(const System::String &text, const SharedPtr<Font> &font, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | Strängen att mäta |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Typsnittet som används under mätning av strängen |
| layoutRect | [RectangleF](../../rectanglef/) | Layoutrektangeln som används under mätning av strängen |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\>\& | Strängformatet, som innehåller teckenområdena att mäta |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Region](../../region/)
* Klass [String](../../../system/string/)
* Klass [Font](../../font/)
* Klass [RectangleF](../../rectanglef/)
* Klass [StringFormat](../../stringformat/)
* Klass [Graphics](../)
* Namnrymd [System::Drawing](../../)
* Bibliotek [Aspose.Slides](../../../)