---
title: MathPortion()
second_title: Aspose.Slides for C++ API 参考
description: 初始化 MathPortion 类的新实例。
type: docs
weight: 14
url: /zh/aspose.slides.mathtext/mathportion/mathportion/
---
## MathPortion::MathPortion() 构造函数

初始化 [MathPortion](../) 类的新实例。

```cpp
Aspose::Slides::MathText::MathPortion::MathPortion()
```

## 备注

示例：
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto paragraph = shape->get_TextFrame()->get_Paragraphs()->idx_get(0);
auto mathPortion = System::MakeObject<MathPortion>();
paragraph->get_Portions()->Add(mathPortion);
```

## 另请参见

* 类 [MathPortion](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)