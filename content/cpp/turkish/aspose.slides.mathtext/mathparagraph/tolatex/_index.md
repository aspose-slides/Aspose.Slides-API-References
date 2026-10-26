---
title: ToLatex()
second_title: Aspose.Slides for C++ API Referansı
description: LaTeX biçiminde matematiksel denklemi alır
type: docs
weight: 183
url: /tr/aspose.slides.mathtext/mathparagraph/tolatex/
---
## MathParagraph::ToLatex() metodu


LaTeX biçiminde matematiksel denklemi alır

```cpp
System::String Aspose::Slides::MathText::MathParagraph::ToLatex() override
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<IAutoShape> shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
System::SharedPtr<IMathParagraph> mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraph(0)->get_Portion(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathematicalText>(u"a")->Join(u"+")->Join(System::MakeObject<MathematicalText>(u"b")->Join(u"=")->Join(System::MakeObject<MathematicalText>(u"c"))));
System::String mathLatex = mathParagraph->ToLatex();
```

## Ayrıca bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [MathParagraph](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)