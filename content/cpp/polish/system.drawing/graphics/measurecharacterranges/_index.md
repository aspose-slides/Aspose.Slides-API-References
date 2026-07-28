---
title: MeasureCharacterRanges()
second_title: Aspose.Slides dla C++ Referencja API
description: Zwraca tablicę regionów, z których każdy ogranicza pozycje znaków w określonym ciągu znaków.
type: docs
weight: 508
url: /pl/system.drawing/graphics/measurecharacterranges/
---
## Graphics::MeasureCharacterRanges(const System::String\&, const SharedPtr\<Font\>\&, RectangleF, const SharedPtr\<StringFormat\>\&) metoda

Zwraca tablicę regionów, z których każdy ogranicza pozycje znaków w określonym ciągu.

```cpp
ArrayPtr<SharedPtr<Region>> System::Drawing::Graphics::MeasureCharacterRanges(const System::String &text, const SharedPtr<Font> &font, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | Ciąg znaków do zmierzenia |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Czcionka używana podczas pomiaru ciągu znaków |
| layoutRect | [RectangleF](../../rectanglef/) | Prostokąt układu używany podczas pomiaru ciągu znaków |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\>\& | Format ciągu, zawierający zakresy znaków do zmierzenia |

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Region](../../region/)
* Klasa [String](../../../system/string/)
* Klasa [Font](../../font/)
* Klasa [RectangleF](../../rectanglef/)
* Klasa [StringFormat](../../stringformat/)
* Klasa [Graphics](../)
* Przestrzeń nazw [System::Drawing](../../)
* Biblioteka [Aspose.Slides](../../../)