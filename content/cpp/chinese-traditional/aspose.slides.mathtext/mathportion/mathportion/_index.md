---
title: MathPortion()
second_title: Aspose.Slides for C++ API 參考文件
description: 初始化 MathPortion 類別的新實例。
type: docs
weight: 14
url: /zh-hant/aspose.slides.mathtext/mathportion/mathportion/
---
## MathPortion::MathPortion() 建構子

初始化 [MathPortion](../) 類別的新執行個體。

```cpp
Aspose::Slides::MathText::MathPortion::MathPortion()
```

## 備註

範例：
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto paragraph = shape->get_TextFrame()->get_Paragraphs()->idx_get(0);
auto mathPortion = System::MakeObject<MathPortion>();
paragraph->get_Portions()->Add(mathPortion);
```

## 另請參閱

* 類別 [MathPortion](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)