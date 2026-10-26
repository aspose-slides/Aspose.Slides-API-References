---
title: MathBox()
second_title: Aspose.Slides for C++ API Referansı
description: MathBox'ı belirtilen öğeyle bir argüman olarak başlatır
type: docs
weight: 144
url: /tr/aspose.slides.mathtext/mathbox/mathbox/
---
## MathBox::MathBox(System::SharedPtr\<IMathElement\>) yapıcı

[MathBox](../) nesnesini belirtilen öğe ile bir argüman olarak başlatır

```cpp
Aspose::Slides::MathText::MathBox::MathBox(System::SharedPtr<IMathElement> element)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Kutunun uygulandığı temel öğe. Null olabilir. |

## Açıklamalar

Örnek:
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
```

## Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathBox](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)