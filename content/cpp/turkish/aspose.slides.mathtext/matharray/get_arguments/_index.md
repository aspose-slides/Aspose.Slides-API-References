---
title: get_Arguments()
second_title: Aspose.Slides for C++ API Referansı
description: Dizinin öğeler kümesi
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/matharray/get_arguments/
---
## MathArray::get_Arguments() yöntemi

Dizinin öğeler kümesi

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathArray::get_Arguments() override
```

## Açıklamalar

Örnek: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElementCollection](../../imathelementcollection/)
* Sınıf [MathArray](../)
* AdAlanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)