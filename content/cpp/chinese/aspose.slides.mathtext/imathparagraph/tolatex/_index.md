---
title: ToLatex()
second_title: Aspose.Slides for C++ API 参考
description: 获取 LaTeX 格式的数学公式
type: docs
weight: 40
url: /zh/aspose.slides.mathtext/imathparagraph/tolatex/
---
## IMathParagraph::ToLatex() 方法

获取 LaTeX 格式的数学公式

```cpp
virtual System::String Aspose::Slides::MathText::IMathParagraph::ToLatex()=0
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
* 类 [IMathParagraph](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)