---
title: Contains()
second_title: Aspose.Slides for C++ API Referansı
description: Koleksiyonun belirli bir değeri içerip içermediğini belirler.
type: docs
weight: 79
url: /tr/aspose.slides.mathtext/imathelementcollection/contains/
---
## IMathElementCollection::Contains(System::SharedPtr\<IMathElement\>) yöntemi


Koleksiyonun belirli bir değeri içerip içermediğini belirler.

```cpp
virtual bool Aspose::Slides::MathText::IMathElementCollection::Contains(System::SharedPtr<IMathElement> item)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Koleksiyonda bulunacak nesne. |

### Dönüş Değeri

koleksiyonda *item* bulunursa true; aksi takdirde false.
## Notlar



Örnek: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
bool contains = collection->Contains(plusElement);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [IMathElementCollection](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)