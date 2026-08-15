---
title: get_Base()
second_title: Aspose.Slides for C++ API 參考
description: Base 參數
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/mathlimit/get_base/
---
## MathLimit::get_Base() 方法


Base 參數

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Base() override
```

## 備註


範例： 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto baseArg = limitElement->get_Base();
```

## 另見

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathLimit](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)