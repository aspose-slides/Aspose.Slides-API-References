---
title: Add()
second_title: Aspose.Slides for C++ API Referansı
description: IMathBlock'u koleksiyonun sonuna ekler.
type: docs
weight: 92
url: /tr/aspose.slides.mathtext/mathparagraph/add/
---
## MathParagraph::Add(System::SharedPtr\<IMathBlock\>) metot

Koleksiyonun sonuna [IMathBlock](../../imathblock/) ekler.

```cpp
void Aspose::Slides::MathText::MathParagraph::Add(System::SharedPtr<IMathBlock> mathBlock) override
```

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Koleksiyonun sonuna eklenecek bir matematiksel blok |

## Açıklamalar



Örnek: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathBlock](../../imathblock/)
* Sınıf [MathParagraph](../)
* AdAlanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)