---
title: get_MathParagraph()
second_title: Aspose.Slides for C++ API 參考文件
description: 數學段落
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/mathportion/get_mathparagraph/
---
## MathPortion::get_MathParagraph() 方法


數學段落

```cpp
System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::MathPortion::get_MathParagraph() override
```

## 備註


範例：
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x+y")));
```

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathParagraph](../../imathparagraph/)
* 類別 [MathPortion](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)