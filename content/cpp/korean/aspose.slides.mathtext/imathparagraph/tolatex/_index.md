---
title: ToLatex()
second_title: Aspose.Slides for C++ API 레퍼런스
description: LaTeX 형식의 수학 방정식을 가져옵니다
type: docs
weight: 40
url: /ko/aspose.slides.mathtext/imathparagraph/tolatex/
---
## IMathParagraph::ToLatex() 메서드


LaTeX 형식의 수학 방정식을 가져옵니다

```cpp
virtual System::String Aspose::Slides::MathText::IMathParagraph::ToLatex()=0
```

## 비고


예:
```cpp
System::SharedPtr<IAutoShape> shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
System::SharedPtr<IMathParagraph> mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraph(0)->get_Portion(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathematicalText>(u"a")->Join(u"+")->Join(System::MakeObject<MathematicalText>(u"b")->Join(u"=")->Join(System::MakeObject<MathematicalText>(u"c"))));
System::String mathLatex = mathParagraph->ToLatex();
```

## 관련 항목

* 클래스 [String](../../../system/string/)
* 클래스 [IMathParagraph](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)