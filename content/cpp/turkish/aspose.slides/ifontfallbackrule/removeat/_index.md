---
title: RemoveAt()
second_title: Aspose.Slides için C++ API Referansı
description: Listede belirtilen indeksteki FallBack yazı tipini kaldırır.
type: docs
weight: 92
url: /tr/aspose.slides/ifontfallbackrule/removeat/
---
## IFontFallBackRule::RemoveAt(int32_t) yöntemi

Listede belirtilen indeksteki FallBack yazı tipini kaldırır.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::RemoveAt(int32_t index)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Kaldırılacak yazı tipinin sıfır tabanlı indeksi. |
## Açıklamalar



```cpp
// Yazı tiplerinden oluşan bir liste içeren bir kural oluşturur.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Listeden Tahoma'yı kaldırma
newRule->RemoveAt(2);
```

## Diğer Bilgiler

* Sınıf [IFontFallBackRule](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)