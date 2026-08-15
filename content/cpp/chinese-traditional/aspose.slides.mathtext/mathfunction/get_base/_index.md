---
title: get_Base()
second_title: Aspose.Slides for C++ API 參考
description: 函式參數
type: docs
weight: 14
url: /zh-hant/aspose.slides.mathtext/mathfunction/get_base/
---
## MathFunction::get_Base() 方法


函式參數

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Base() override
```

## 備註


範例:
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathFunction](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)