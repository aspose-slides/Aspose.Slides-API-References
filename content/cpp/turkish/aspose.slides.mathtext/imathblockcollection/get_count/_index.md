---
title: get_Count()
second_title: Aspose.Slides için C++ API Referansı
description: Koleksiyonda gerçekte bulunan öğelerin sayısını alır. Yalnızca okuma int32_t.
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/imathblockcollection/get_count/
---
## IMathBlockCollection::get_Count() yöntemi

Koleksiyonda gerçekte bulunan öğelerin sayısını alır. Yalnızca okuma **int32_t**.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::get_Count()=0
```

## Açıklamalar

Örnek:
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
int32_t blocksCount = blockCollection->get_Count();
```

## Ayrıca Bakınız

* Sınıf [IMathBlockCollection](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)