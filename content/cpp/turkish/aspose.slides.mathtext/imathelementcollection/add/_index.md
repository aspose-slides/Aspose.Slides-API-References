---
title: Add()
second_title: Aspose.Slides for C++ API Referansı
description: Bir matematik öğesini koleksiyonun sonuna ekler.
type: docs
weight: 27
url: /tr/aspose.slides.mathtext/imathelementcollection/add/
---
## IMathElementCollection::Add(System::SharedPtr\<IMathElement\>) metot

Bir matematik öğesini koleksiyonun sonuna ekler.

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::Add(System::SharedPtr<IMathElement> item)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Koleksiyonun sonuna eklenecek [IMathElement](../../imathelement/). |
## Açıklamalar



Örnek: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
collection->Add(System::MakeObject<MathematicalText>(u"+"));
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [IMathElementCollection](../)
* İsim Uzayı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)