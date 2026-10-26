---
title: get_Base()
second_title: Aspose.Slides for C++ API 参考
description: 函数参数
type: docs
weight: 14
url: /zh/aspose.slides.mathtext/imathfunction/get_base/
---
## IMathFunction::get_Base() 方法

函数参数

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Base()=0
```

## 备注

示例：
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathElement](../../imathelement/)
* 类 [IMathFunction](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)