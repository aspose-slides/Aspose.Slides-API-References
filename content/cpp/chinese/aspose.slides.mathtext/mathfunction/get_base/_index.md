---
title: get_Base()
second_title: Aspose.Slides for C++ API 参考
description: 函数参数
type: docs
weight: 14
url: /zh/aspose.slides.mathtext/mathfunction/get_base/
---
## MathFunction::get_Base() 方法

函数参数

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Base() override
```

## 备注

示例：
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathElement](../../imathelement/)
* 类 [MathFunction](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)