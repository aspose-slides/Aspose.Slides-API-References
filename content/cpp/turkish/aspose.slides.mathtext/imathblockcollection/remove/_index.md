---
title: Remove()
second_title: Aspose.Slides for C++ API Referansı
description: Koleksiyondan belirli bir nesnenin ilk oluşumunu kaldırır/>.
type: docs
weight: 40
url: /tr/aspose.slides.mathtext/imathblockcollection/remove/
---
## IMathBlockCollection::Remove(System::SharedPtr\<IMathBlock\>) metod


Koleksiyondan belirli bir nesnenin ilk oluşumunu kaldırır/>.


```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Remove(System::SharedPtr<IMathBlock> item)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Koleksiyondan kaldırılacak nesne. |

### Dönüş Değeri

true if *item* koleksiyondan başarıyla kaldırıldıysa; otherwise, false. Bu metod ayrıca *item* orijinal koleksiyonda bulunamazsa false döndürür/>

## Açıklamalar



Örnek: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->Remove(block);
```

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathBlock](../../imathblock/)
* Sınıf [IMathBlockCollection](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)