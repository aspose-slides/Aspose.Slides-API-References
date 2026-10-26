---
title: Contains()
second_title: Aspose.Slides için C++ API Referansı
description: Koleksiyonun belirli bir değeri içerip içermediğini belirler.
type: docs
weight: 66
url: /tr/aspose.slides.mathtext/imathblockcollection/contains/
---
## IMathBlockCollection::Contains(System::SharedPtr\<IMathBlock\>) metot

Koleksiyonun belirli bir değeri içerip içermediğini belirler.

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Contains(System::SharedPtr<IMathBlock> item)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Koleksiyonda bulunacak nesne. |

### Dönüş Değeri

true if *item*  is found in the collection; otherwise, false.

## Açıklamalar



Örnek: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
bool contains = blockCollection->Contains(block);
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathBlock](../../imathblock/)
* Sınıf [IMathBlockCollection](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)