---
title: RemoveAt()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen listedeki indeksdeki FallBack yazı tipini kaldırır.
type: docs
weight: 131
url: /tr/aspose.slides/fontfallbackrule/removeat/
---
## FontFallBackRule::RemoveAt(int32_t) yöntemi

Belirtilen listedeki indeksdeki FallBack yazı tipini kaldırır.

```cpp
void Aspose::Slides::FontFallBackRule::RemoveAt(int32_t index) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Kaldırılacak yazı tipinin sıfır tabanlı indeksi. |
## Açıklamalar

```cpp
// Yazı tiplerinin bir listesini içeren bir kural oluşturur.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Listeden Tahoma'yı kaldırıyor.
newRule->RemoveAt(2);
```

## İlgili

* Sınıf [FontFallBackRule](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)