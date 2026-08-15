---
title: get_Limit()
second_title: Aspose.Slides for C++ API 參考
description: 限制參數
type: docs
weight: 14
url: /zh-hant/aspose.slides.mathtext/imathlimit/get_limit/
---
## IMathLimit::get_Limit() 方法

限制參數

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Limit()=0
```

## 備註

範例： 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## 參見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [IMathLimit](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)