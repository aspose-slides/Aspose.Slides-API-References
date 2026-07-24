---
title: Clear()
second_title: Aspose.Slides for C++ API Referansı
description: Koleksiyondaki tüm öğeleri kaldırır.
type: docs
weight: 79
url: /tr/aspose.slides.mathtext/mathparagraph/clear/
---
## MathParagraph::Clear() metodu


Koleksiyondaki tüm öğeleri kaldırır.

```cpp
void Aspose::Slides::MathText::MathParagraph::Clear() override
```

## Açıklamalar


Örnek: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
mathParagraph->Clear();
```

## Diğer Bağlantılar

* Sınıf [MathParagraph](../)
* İsim Uzayı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)