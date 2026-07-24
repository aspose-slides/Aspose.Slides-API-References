---
title: RemoveAt()
second_title: Aspose.Slides for C++ API Referansı
description: Koleksiyonun belirtilen dizinindeki bir öğeyi kaldırır.
type: docs
weight: 53
url: /tr/aspose.slides.mathtext/imathblockcollection/removeat/
---
## IMathBlockCollection::RemoveAt(int32_t) metodu

Koleksiyonun belirtilen dizinindeki bir öğeyi kaldırır.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::RemoveAt(int32_t index)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Kaldırılacak öğenin sıfır tabanlı dizini. |
## Açıklamalar



Örnek:
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->RemoveAt(0);
```

## Ayrıca Bakınız

* Sınıf [IMathBlockCollection](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)