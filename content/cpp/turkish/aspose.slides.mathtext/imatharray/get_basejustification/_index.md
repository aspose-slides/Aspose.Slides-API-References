---
title: get_BaseJustification()
second_title: Aspose.Slides için C++ API Referansı
description: "Dizinin çevresindeki metne göre hizalamasını belirtir. Dizinin dışındaki metin, bir dizi nesnesinin altı, üstü veya ortası ile hizalanabilir. Varsayılan değer: Center"
type: docs
weight: 14
url: /tr/aspose.slides.mathtext/imatharray/get_basejustification/
---
## IMathArray::get_BaseJustification() metodu

Array'in çevresindeki metne göre hizalamasını belirtir. Array dışındaki metin, bir array nesnesinin alt kısmı, üst kısmı veya ortası ile hizalanabilir. Varsayılan değer: Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathArray::get_BaseJustification()=0
```

## Açıklamalar

Örnek:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Ayrıca Bakınız

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Sınıf [IMathArray](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)