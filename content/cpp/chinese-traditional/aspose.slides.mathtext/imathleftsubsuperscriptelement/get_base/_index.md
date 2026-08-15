---
title: get_Base()
second_title: Aspose.Slides for C++ API 參考
description: Base 參數
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/imathleftsubsuperscriptelement/get_base/
---
## IMathLeftSubSuperscriptElement::get_Base() 方法


Base 參數

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLeftSubSuperscriptElement::get_Base()=0
```

## 備註


範例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
auto baseElem = leftSubSuperscript->get_Base();
```

## 參見

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [IMathLeftSubSuperscriptElement](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)