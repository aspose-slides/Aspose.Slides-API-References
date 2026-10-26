---
title: MeasureString()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen formatta, belirtilen fontla çizildiğinde belirtilen dizeyin boyutunu döndürür.
type: docs
weight: 521
url: /tr/system.drawing/graphics/measurestring/
---
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, PointF const\&, System::SharedPtr\<StringFormat\> const\&) const metod

Belirtilen dizeyi belirtilen formatta, belirtilen fontta çizildiğinde boyutunu döndürür.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, PointF const &origin=PointF(0, 0), System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | Boyutu hesaplanacak dize |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | Dizeyi çizmek için kullanılan font |
| origin | [PointF](../../pointf/) const\& | Dizenin sol üst köşesinin konumunu belirtir |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Dize formatını belirtir |

### Dönüş Değeri

Mevcut Graphics nesnesinin PageUnit özelliği tarafından belirtilen ölçüm birimlerinde dize boyutunu temsil eden bir [SizeF](../../sizef/) nesnesi.

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, int, System::SharedPtr\<StringFormat\> const\&) const metod

Belirtilen dizeyi belirtilen formatta, belirtilen fontta çizildiğinde boyutunu döndürür.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, int width, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | Boyutu hesaplanacak dize |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | Dizeyi çizmek için kullanılan font |
| width | int | Dizenin maksimum genişliği |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Dize formatını belirtir |

### Dönüş Değeri

Mevcut Graphics nesnesinin PageUnit özelliği tarafından belirtilen ölçüm birimlerinde dize boyutunu temsil eden bir [SizeF](../../sizef/) nesnesi.

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&, int\&, int\&) const metod

UYGULANMADI.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat, int &charactersFitted, int &linesFilled) const
```

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&) const metod

Belirtilen dizeyi belirtilen formatta, belirtilen fontta çizildiğinde boyutunu döndürür.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | Boyutu hesaplanacak dize |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | Dizeyi çizmek için kullanılan font |
| layoutArea | [SizeF](../../sizef/) const\& | Dizenin maksimum yerleşim alanı |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Dize formatını belirtir |

### Dönüş Değeri

Mevcut Graphics nesnesinin PageUnit özelliği tarafından belirtilen ölçüm birimlerinde dize boyutunu temsil eden bir [SizeF](../../sizef/) nesnesi.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [SizeF](../../sizef/)
* Sınıf [String](../../../system/string/)
* Sınıf [Font](../../font/)
* Sınıf [PointF](../../pointf/)
* Sınıf [StringFormat](../../stringformat/)
* Sınıf [Graphics](../)
* Ad alanı [System::Drawing](../../)
* Library [Aspose.Slides](../../../)