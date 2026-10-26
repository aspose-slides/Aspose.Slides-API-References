---
title: ToLatex()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得 LaTeX 格式的數學方程式
type: docs
weight: 40
url: /zh-hant/aspose.slides.mathtext/imathparagraph/tolatex/
---
## IMathParagraph::ToLatex() 方法

取得 LaTeX 格式的數學方程式

```cpp
virtual System::String Aspose::Slides::MathText::IMathParagraph::ToLatex()=0
```
## 備註

範例:
```cpp
System::SharedPtr<IAutoShape> shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
System::SharedPtr<IMathParagraph> mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraph(0)->get_Portion(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathematicalText>(u"a")->Join(u"+")->Join(System::MakeObject<MathematicalText>(u"b")->Join(u"=")->Join(System::MakeObject<MathematicalText>(u"c"))));
System::String mathLatex = mathParagraph->ToLatex();
```
## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [IMathParagraph](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)