---
title: set_BaseJustification()
second_title: Aspose.Slides for C++ API Referansı
description: "Dizinin çevre metne göre hizalamasını belirtir. Dizinin dışındaki metin, bir dizi nesnesinin alt, üst veya orta konumuyla hizalanabilir. Varsayılan değer: Center"
type: docs
weight: 27
url: /tr/aspose.slides.mathtext/imatharray/set_basejustification/
---
## IMathArray::set_BaseJustification(MathVerticalAlignment) yöntemi

Dizinin çevre metne göre hizalamasını belirtir. Dizinin dışındaki metin, dizi nesnesinin alt, üst veya orta konumuyla hizalanabilir. Varsayılan değer: Center

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_BaseJustification(MathVerticalAlignment value)=0
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
* AdAlanı [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)