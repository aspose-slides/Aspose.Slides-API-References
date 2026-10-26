---
title: MeasureCharacterRanges()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen dizedeki karakter konumlarını sınırlayan bölgelerden oluşan bir dizi döndürür.
type: docs
weight: 508
url: /tr/system.drawing/graphics/measurecharacterranges/
---
## Graphics::MeasureCharacterRanges(const System::String\&, const SharedPtr\<Font\>\&, RectangleF, const SharedPtr\<StringFormat\>\&) metodu


Belirtilen dizedeki karakter konumlarını sınırlayan bölgelerden oluşan bir dizi döndürür.

```cpp
ArrayPtr<SharedPtr<Region>> System::Drawing::Graphics::MeasureCharacterRanges(const System::String &text, const SharedPtr<Font> &font, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | Ölçülecek dize |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Dizenin ölçümü sırasında kullanılan yazı tipi |
| layoutRect | [RectangleF](../../rectanglef/) | Dizenin ölçümü sırasında kullanılan yerleşim dikdörtgeni |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\>\& | Dize biçimi, ölçülecek karakter aralıklarını içerir |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../../region/)
* Class [String](../../../system/string/)
* Class [Font](../../font/)
* Class [RectangleF](../../rectanglef/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)