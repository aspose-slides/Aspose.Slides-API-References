---
title: get_MathParagraph()
second_title: Aspose.Slides için C++ API Referansı
description: Matematik paragrafı
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/imathportion/get_mathparagraph/
---
## IMathPortion::get_MathParagraph() metot


Matematik paragrafı

```cpp
virtual System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::IMathPortion::get_MathParagraph()=0
```

## Açıklamalar


Örnek: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x+y")));
```

## Ayrıca bakınız

* Tip tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathParagraph](../../imathparagraph/)
* Sınıf [IMathPortion](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)