---
title: ToLatex()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: รับสมการคณิตศาสตร์ในรูปแบบ LaTeX
type: docs
weight: 40
url: /th/aspose.slides.mathtext/imathparagraph/tolatex/
---
## IMathParagraph::ToLatex() เมธอด


รับสมการคณิตศาสตร์ในรูปแบบ LaTeX

```cpp
virtual System::String Aspose::Slides::MathText::IMathParagraph::ToLatex()=0
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
* คลาส [IMathParagraph](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)