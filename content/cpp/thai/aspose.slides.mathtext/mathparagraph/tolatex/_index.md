---
title: ToLatex()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ดึงสมการคณิตศาสตร์ในรูปแบบ LaTeX
type: docs
weight: 183
url: /th/aspose.slides.mathtext/mathparagraph/tolatex/
---
## MathParagraph::ToLatex() เมธอด


ดึงสมการคณิตศาสตร์ในรูปแบบ LaTeX

```cpp
System::String Aspose::Slides::MathText::MathParagraph::ToLatex() override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<IAutoShape> shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
System::SharedPtr<IMathParagraph> mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraph(0)->get_Portion(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathematicalText>(u"a")->Join(u"+")->Join(System::MakeObject<MathematicalText>(u"b")->Join(u"=")->Join(System::MakeObject<MathematicalText>(u"c"))));
System::String mathLatex = mathParagraph->ToLatex();
```

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [MathParagraph](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)