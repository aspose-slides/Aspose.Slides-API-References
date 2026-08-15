---
title: get_Subscript()
second_title: Aspose.Slides C++ API 參考
description: 下標
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/mathleftsubsuperscriptelement/get_subscript/
---
## MathLeftSubSuperscriptElement::get_Subscript() 方法

下標

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLeftSubSuperscriptElement::get_Subscript() override
```

## 備註

範例：
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
auto sub = leftSubSuperscript->get_Subscript();
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathLeftSubSuperscriptElement](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)