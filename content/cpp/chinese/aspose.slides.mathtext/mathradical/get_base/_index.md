---
title: get_Base()
second_title: Aspose.Slides for C++ API 参考
description: Base 参数
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/mathradical/get_base/
---
## MathRadical::get_Base() 方法


Base 参数

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Base() override
```

## 备注


示例: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto baseElem = radical->get_Base();
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathElement](../../imathelement/)
* 类 [MathRadical](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)