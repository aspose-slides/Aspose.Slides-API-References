---
title: Remove()
second_title: Aspose.Slides for C++ API Referansı
description: Koleksiyondan belirli bir nesnenin ilk oluşumunu kaldırır.
type: docs
weight: 92
url: /tr/aspose.slides.mathtext/imathelementcollection/remove/
---
## IMathElementCollection::Remove(System::SharedPtr\<IMathElement\>) yöntemi


Koleksiyondan belirli bir nesnenin ilk oluşumunu kaldırır.

```cpp
virtual bool Aspose::Slides::MathText::IMathElementCollection::Remove(System::SharedPtr<IMathElement> item)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Koleksiyondan kaldırılacak nesne. |

### Dönüş Değeri

eğer *item* koleksiyondan başarıyla kaldırıldıysa true; aksi takdirde false. Bu yöntem ayrıca *item* orijinal koleksiyonda bulunamazsa false döndürür.
## Açıklamalar



Örnek: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
collection->Remove(plusElement);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [IMathElementCollection](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)