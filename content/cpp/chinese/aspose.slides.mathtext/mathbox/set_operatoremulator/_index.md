---
title: set_OperatorEmulator()
second_title: Aspose.Slides for C++ API 参考
description: "运算符仿真器。为 true 时，框及其内容表现为单个运算符并继承运算符的属性。这意味着，例如，该字符可以作为换行点，并且可以与其他运算符对齐。运算符仿真器通常在一个或多个字形组合成运算符（如 '=='）时使用。默认值：false"
type: docs
weight: 27
url: /zh/aspose.slides.mathtext/mathbox/set_operatoremulator/
---
## MathBox::set_OperatorEmulator(bool) 方法

运算符仿真器。为 true 时，框及其内容表现为单个运算符并继承运算符的属性。这意味着，例如，该字符可以作为换行点，并且可以与其他运算符对齐。运算符仿真器通常在一个或多个字形组合成运算符（如 “==”）时使用。默认值：false

```cpp
void Aspose::Slides::MathText::MathBox::set_OperatorEmulator(bool value) override
```

## 备注

示例：
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## 另见

* 类 [MathBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)