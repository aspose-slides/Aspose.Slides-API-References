---
title: Remove()
second_title: Aspose.Slides for C++ API Referansı
description: Belirli bir nesnenin koleksiyondaki ilk örneğini kaldırır.
type: docs
weight: 131
url: /tr/aspose.slides.mathtext/mathblock/remove/
---
## MathBlock::Remove(System::SharedPtr\<IMathElement\>) yöntemi


Koleksiyondan belirli bir nesnenin ilk örneğini kaldırır.

```cpp
bool Aspose::Slides::MathText::MathBlock::Remove(System::SharedPtr<IMathElement> item) override
```


### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Koleksiyondan kaldırılacak nesne. |

### Dönüş Değeri

true, *item* koleksiyondan başarıyla kaldırıldıysa; aksi takdirde false. Bu yöntem ayrıca *item* orijinal koleksiyonda bulunamazsa false döndürür.

## Notlar



Örnek: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->Remove(plusElement);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathBlock](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)