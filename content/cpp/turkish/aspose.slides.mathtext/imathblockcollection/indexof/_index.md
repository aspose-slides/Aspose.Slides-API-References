---
title: IndexOf()
second_title: Aspose.Slides for C++ API Referansı
description: Koleksiyondaki belirli bir IMathBlock öğesinin dizinini belirler.
type: docs
weight: 79
url: /tr/aspose.slides.mathtext/imathblockcollection/indexof/
---
## IMathBlockCollection::IndexOf(System::SharedPtr\<IMathBlock\>) metodu


Koleksiyondaki belirli bir [IMathBlock](../../imathblock/) öğesinin dizinini belirler.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::IndexOf(System::SharedPtr<IMathBlock> item)=0
```


### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Koleksiyonda bulunacak öğe. |

### Dönüş Değeri

Koleksiyonda bulunursa *item* öğesinin indeksi; aksi takdirde -1.

## Açıklamalar



Örnek: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
int32_t index = blockCollection->IndexOf(block);
```

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [IMathBlockCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)