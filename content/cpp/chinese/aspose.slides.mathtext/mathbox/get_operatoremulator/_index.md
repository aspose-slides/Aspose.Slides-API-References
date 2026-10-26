---
title: get_OperatorEmulator()
second_title: Aspose.Slides for C++ API 参考
description: "Operator Emulator。当为 true 时，框及其内容表现为单个运算符并继承运算符的属性。这意味着，例如，该字符可以作为换行点并且可以与其他运算符对齐。当一个或多个字形组合形成运算符（例如 '=='）时，通常使用运算符仿真器。默认值：false"
type: docs
weight: 14
url: /zh/aspose.slides.mathtext/mathbox/get_operatoremulator/
---
## MathBox::get_OperatorEmulator() 方法


Operator Emulator. 当为 true 时，框及其内容表现为单个运算符并继承运算符的属性。这意味着，例如，该字符可以作为换行点，并且可以与其他运算符对齐。当多个字形组合形成运算符（例如 '=='）时，通常使用运算符仿真器。默认值：false

```cpp
bool Aspose::Slides::MathText::MathBox::get_OperatorEmulator() override
```

## 备注


示例： 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## 另请参见

* 类 [MathBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)