---
title: ToLatex()
second_title: Aspose.Slides for C++ API 参考
description: 获取 LaTeX 格式的数学方程
type: docs
weight: 183
url: /zh/aspose.slides.mathtext/mathparagraph/tolatex/
---
## MathParagraph::ToLatex() 方法


获取 LaTeX 格式的数学方程

```cpp
System::String Aspose::Slides::MathText::MathParagraph::ToLatex() override
```

## 备注


示例：
```cpp
System::SharedPtr<IAutoShape> shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
System::SharedPtr<IMathParagraph> mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraph(0)->get_Portion(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathematicalText>(u"a")->Join(u"+")->Join(System::MakeObject<MathematicalText>(u"b")->Join(u"=")->Join(System::MakeObject<MathematicalText>(u"c"))));
System::String mathLatex = mathParagraph->ToLatex();
```

## 另请参阅

* 类 [String](../../../system/string/)
* 类 [MathParagraph](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)