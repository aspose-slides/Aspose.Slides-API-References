---
title: get_BaseJustification()
second_title: Aspose.Slides C++ API Referansı
description: "Dizinin çevredeki metne göre hizalamasını belirtir. Dizinin dışındaki metin bir dizi nesnesinin alt, üst veya ortasıyla hizalanabilir. Varsayılan değer: Center"
type: docs
weight: 14
url: /tr/aspose.slides.mathtext/matharray/get_basejustification/
---
## MathArray::get_BaseJustification() metodu

Dizinin çevredeki metne göre hizalamasını belirtir. Dizinin dışındaki metin, bir dizi nesnesinin alt, üst veya ortasıyla hizalanabilir. Varsayılan değer: Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathArray::get_BaseJustification() override
```

## Açıklamalar

Örnek: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Ayrıca bakınız

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Sınıf [MathArray](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)