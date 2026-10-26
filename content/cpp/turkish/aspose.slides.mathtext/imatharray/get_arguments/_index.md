---
title: get_Arguments()
second_title: Aspose.Slides için C++ API Referansı
description: Dizinin öğeler kümesi
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/imatharray/get_arguments/
---
## IMMathArray::get_Arguments() metot


Dizinin öğe kümesi

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathArray::get_Arguments()=0
```

## Açıklamalar


Örnek: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## Diğer Bölümler

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElementCollection](../../imathelementcollection/)
* Sınıf [IMathArray](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)