---
title: get_Limit()
second_title: Aspose.Slides C++ API 参考
description: 限制参数
type: docs
weight: 14
url: /zh/aspose.slides.mathtext/mathlimit/get_limit/
---
## MathLimit::get_Limit() 方法

限制参数

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Limit() override
```

## 备注

示例：
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathElement](../../imathelement/)
* 类 [MathLimit](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)