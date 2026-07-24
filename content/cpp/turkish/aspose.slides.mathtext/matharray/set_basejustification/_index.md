---
title: set_BaseJustification()
second_title: Aspose.Slides for C++ API Referansı
description: "Dizinin çevresindeki metne göre hizalamasını belirtir. Dizi dışındaki metin, bir dizi nesnesinin alt, üst veya orta kısmına hizalanabilir. Varsayılan değer: Center"
type: docs
weight: 27
url: /tr/aspose.slides.mathtext/matharray/set_basejustification/
---
## MathArray::set_BaseJustification(MathVerticalAlignment) metot


Dizinin çevresindeki metne göre hizalamasını belirtir. Dizi dışındaki metin, bir dizi nesnesinin alt, üst veya orta kısmına hizalanabilir. Varsayılan değer: Center

```cpp
void Aspose::Slides::MathText::MathArray::set_BaseJustification(MathVerticalAlignment value) override
```

## Açıklamalar


Örnek: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Ayrıca Bakınız

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Sınıf [MathArray](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)