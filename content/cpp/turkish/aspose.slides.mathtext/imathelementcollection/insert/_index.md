---
title: Insert()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen dizinde koleksiyona bir matematik öğesi ekler.
type: docs
weight: 53
url: /tr/aspose.slides.mathtext/imathelementcollection/insert/
---
## IMathElementCollection::Insert(int32_t, System::SharedPtr\<IMathElement\>) metot


Belirtilen dizinde koleksiyona bir matematik öğesi ekler.

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::Insert(int32_t index, System::SharedPtr<IMathElement> item)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Sıfır tabanlı indeks, [IMathElement](../../imathelement/) öğesinin eklenmesi gereken konum. |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Eklenecek [IMathElement](../../imathelement/). |
## Açıklamalar



Örnek: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [IMathElementCollection](../)
* AdAlanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)