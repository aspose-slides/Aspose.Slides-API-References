---
title: Clear()
second_title: Aspose.Slides for C++ API Referansı
description: Koleksiyondaki tüm öğeleri kaldırır.
type: docs
weight: 118
url: /tr/aspose.slides.mathtext/imathblockcollection/clear/
---
## IMathBlockCollection::Clear() metod


Koleksiyondaki tüm öğeleri kaldırır.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Clear()=0
```

## Açıklamalar


Örnek: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
blockCollection->Clear();
```

## Ayrıca Bak

* Sınıf [IMathBlockCollection](../)
* AdAlanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)