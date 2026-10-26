---
title: get_Name()
second_title: Aspose.Slides for C++ API 參考文件
description: 函式名稱 例如，函式名稱為 sin 和 cos
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/mathfunction/get_name/
---
## MathFunction::get_Name() 方法


函式名稱 例如，函式名稱有 sin 和 cos

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Name() override
```

## 備註


範例： 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathFunction](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)