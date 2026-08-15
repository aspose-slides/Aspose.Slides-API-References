---
title: get_Base()
second_title: Aspose.Slides for C++ API 參考文件
description: 函式參數
type: docs
weight: 14
url: /zh-hant/aspose.slides.mathtext/imathfunction/get_base/
---
## IMathFunction::get_Base() 方法

函式參數

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Base()=0
```

## 備註

範例：
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## 參見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [IMathFunction](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)