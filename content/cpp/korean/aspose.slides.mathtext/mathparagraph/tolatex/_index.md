---
title: ToLatex()
second_title: Aspose.Slides for C++ API 참조
description: LaTeX 형식의 수학 방정식을 가져옵니다
type: docs
weight: 183
url: /ko/aspose.slides.mathtext/mathparagraph/tolatex/
---
## MathParagraph::ToLatex() 메서드


LaTeX 형식의 수학 방정식을 가져옵니다

```cpp
System::String Aspose::Slides::MathText::MathParagraph::ToLatex() override
```

## 비고


예제: 
```cpp
System::SharedPtr<IAutoShape> shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
System::SharedPtr<IMathParagraph> mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraph(0)->get_Portion(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathematicalText>(u"a")->Join(u"+")->Join(System::MakeObject<MathematicalText>(u"b")->Join(u"=")->Join(System::MakeObject<MathematicalText>(u"c"))));
System::String mathLatex = mathParagraph->ToLatex();
```

## 또 보기

* 클래스 [String](../../../system/string/)
* 클래스 [MathParagraph](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)