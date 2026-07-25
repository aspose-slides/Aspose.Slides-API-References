---
title: ToLatex()
second_title: Aspose.Slides for C++ API リファレンス
description: LaTeX 形式の数式を取得します
type: docs
weight: 183
url: /ja/aspose.slides.mathtext/mathparagraph/tolatex/
---
## MathParagraph::ToLatex() メソッド


LaTeX 形式の数式を取得します

```cpp
System::String Aspose::Slides::MathText::MathParagraph::ToLatex() override
```

## 備考


例: 
```cpp
System::SharedPtr<IAutoShape> shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
System::SharedPtr<IMathParagraph> mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraph(0)->get_Portion(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathematicalText>(u"a")->Join(u"+")->Join(System::MakeObject<MathematicalText>(u"b")->Join(u"=")->Join(System::MakeObject<MathematicalText>(u"c"))));
System::String mathLatex = mathParagraph->ToLatex();
```

## 参照

* クラス [String](../../../system/string/)
* クラス [MathParagraph](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)