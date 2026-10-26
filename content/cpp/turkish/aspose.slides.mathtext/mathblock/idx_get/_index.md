---
title: idx_get()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen indeksteki IMathElement öğesini alır.
type: docs
weight: 27
url: /tr/aspose.slides.mathtext/mathblock/idx_get/
---
## MathBlock::idx_get(int32_t) yöntemi


Belirtilen indeksteki [IMathElement](../../imathelement/) öğesini alır.

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBlock::idx_get(int32_t index) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Öğenin sıfır tabanlı indeksi |

### Dönüş Değeri

Matematiksel öğe.
## Açıklamalar



Örnek: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = mathBlock->idx_get(0);
```

## Ayrıca Bakınız

* Tip tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathBlock](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)