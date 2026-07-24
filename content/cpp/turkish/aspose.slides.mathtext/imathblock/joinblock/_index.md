---
title: JoinBlock()
second_title: Aspose.Slides for C++ API Referansı
description: Başka bir matematik bloğunu bu blokla birleştirir
type: docs
weight: 27
url: /tr/aspose.slides.mathtext/imathblock/joinblock/
---
## IMathBlock::JoinBlock(System::SharedPtr\<IMathBlock\>) metot

Başka bir matematik bloğunu bu blokla birleştirir

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlock::JoinBlock(System::SharedPtr<IMathBlock> other)=0
```

### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| other | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../)\> | Birleştirilen blok |

### Dönüş Değeri

Birleştirme işleminden sonra bu matematik bloğu

## Açıklama



Örnek: 
```cpp
auto block1 = System::MakeObject<MathSuperscriptElement>(
    System::MakeObject<MathematicalText>(u"c"),
    System::MakeObject<MathematicalText>(u"2")
)->Join(System::MakeObject<MathematicalText>(u"="));
auto block2 = System::MakeObject<MathSuperscriptElement>(
    System::MakeObject<MathematicalText>(u"a"),
    System::MakeObject<MathematicalText>(u"2")
)->Join(System::MakeObject<MathematicalText>(u"+"))->Join(System::MakeObject<MathSuperscriptElement>(System::MakeObject<MathematicalText>(u"b"), System::MakeObject<MathematicalText>(u"2")));
auto block3 = block1->JoinBlock(block2);
```

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathBlock](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)