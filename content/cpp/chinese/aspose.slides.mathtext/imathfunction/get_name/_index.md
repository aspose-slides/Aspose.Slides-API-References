---
title: get_Name()
second_title: Aspose.Slides for C++ API 参考
description: 函数名称 例如，函数名称为 sin 和 cos
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/imathfunction/get_name/
---
## IMathFunction::get_Name() 方法


函数名称 例如，函数名称为 sin 和 cos

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Name()=0
```

## 备注


示例：
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathElement](../../imathelement/)
* 类 [IMathFunction](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)