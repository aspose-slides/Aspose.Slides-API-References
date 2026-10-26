---
title: set_OperatorEmulator()
second_title: Aspose.Slides for C++ API 参考
description: "运算符仿真器。为 true 时，框及其内容表现为单个运算符并继承运算符的属性。这意味着，例如，该字符可以作为换行点，并且可以与其他运算符对齐。当一个或多个字符组合形成运算符（如 '=='）时，通常会使用运算符仿真器。默认值: false"
type: docs
weight: 27
url: /zh/aspose.slides.mathtext/imathbox/set_operatoremulator/
---
## IMathBox::set_OperatorEmulator(bool) 方法


运算符仿真器。为 true 时，框及其内容表现为单个运算符并继承运算符的属性。这意味着，例如，该字符可以作为换行点，并且可以与其他运算符对齐。当一个或多个字符组合形成运算符（如 '=='）时，通常会使用运算符仿真器。默认值: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_OperatorEmulator(bool value)=0
```

## 备注


示例: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_OperatorEmulator(true);
```

## 另见

* 类 [IMathBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)