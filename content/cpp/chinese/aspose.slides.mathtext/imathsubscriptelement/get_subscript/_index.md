---
title: get_Subscript()
second_title: Aspose.Slides for C++ API 参考
description: 下标
type: docs
weight: 14
url: /zh/aspose.slides.mathtext/imathsubscriptelement/get_subscript/
---
## IMMathSubscriptElement::get_Subscript() method


下标

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathSubscriptElement::get_Subscript()=0
```

## 备注


示例: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto subscriptElement = System::MakeObject<MathSubscriptElement>(baseElement, subscript);
auto sub = subscriptElement->get_Subscript();
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathElement](../../imathelement/)
* 类 [IMathSubscriptElement](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)