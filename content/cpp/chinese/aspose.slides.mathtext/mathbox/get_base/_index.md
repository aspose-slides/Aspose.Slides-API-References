---
title: get_Base()
second_title: Aspose.Slides for C++ API 参考
description: Base 参数
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/mathbox/get_base/
---
## MathBox::get_Base() 方法


Base 参数

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBox::get_Base() override
```

## 备注


示例：
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
auto baseArg = box->get_Base();
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathElement](../../imathelement/)
* 类 [MathBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)