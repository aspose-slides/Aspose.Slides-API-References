---
title: ToLatex()
second_title: Aspose.Slides for C++ API Referansı
description: Matematiksel denklemi LaTeX formatında alır
type: docs
weight: 40
url: /tr/aspose.slides.mathtext/imathparagraph/tolatex/
---
## IMathParagraph::ToLatex() metodu

Matematiksel denklemi LaTeX formatında alır

```cpp
virtual System::String Aspose::Slides::MathText::IMathParagraph::ToLatex()=0
```

## Açıklamalar

Örnek: 
```cpp
System::SharedPtr<IAutoShape> shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
System::SharedPtr<IMathParagraph> mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraph(0)->get_Portion(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathematicalText>(u"a")->Join(u"+")->Join(System::MakeObject<MathematicalText>(u"b")->Join(u"=")->Join(System::MakeObject<MathematicalText>(u"c"))));
System::String mathLatex = mathParagraph->ToLatex();
```

## İlgili

* Sınıf [String](../../../system/string/)
* Sınıf [IMathParagraph](../)
* İsim Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)