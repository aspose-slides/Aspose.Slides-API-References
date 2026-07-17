---
title: get_Subscript()
second_title: Aspose.Slides C++ API 参考
description: 下标
type: docs
weight: 14
url: /zh/aspose.slides.mathtext/imathleftsubsuperscriptelement/get_subscript/
---
## IMathLeftSubSuperscriptElement::get_Subscript() 方法

下标

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLeftSubSuperscriptElement::get_Subscript()=0
```

## 备注

示例：
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
auto sub = leftSubSuperscript->get_Subscript();
```

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathElement](../../imathelement/)
* 类 [IMathLeftSubSuperscriptElement](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)