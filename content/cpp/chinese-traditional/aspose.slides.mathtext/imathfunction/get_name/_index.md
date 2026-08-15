---
title: get_Name()
second_title: Aspose.Slides for C++ API 參考
description: 函式名稱 例如，函式名稱為 sin 和 cos
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/imathfunction/get_name/
---
## IMathFunction::get_Name() 方法

函數名稱 例如，函數名稱為 sin 和 cos

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Name()=0
```

## 備註

範例：
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [IMathFunction](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)