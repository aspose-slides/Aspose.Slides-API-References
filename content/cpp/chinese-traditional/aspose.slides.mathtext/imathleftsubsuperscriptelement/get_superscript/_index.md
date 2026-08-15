---
title: get_Superscript()
second_title: Aspose.Slides for C++ API 參考
description: 上標
type: docs
weight: 27
url: /zh-hant/aspose.slides.mathtext/imathleftsubsuperscriptelement/get_superscript/
---
## IMathLeftSubSuperscriptElement::get_Superscript() 方法


上標

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLeftSubSuperscriptElement::get_Superscript()=0
```

## 備註


範例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
auto sup = leftSubSuperscript->get_Superscript();
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [IMathLeftSubSuperscriptElement](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)