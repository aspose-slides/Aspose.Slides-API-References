---
title: get_Base()
second_title: Aspose.Slides for C++ API 參考
description: 基礎參數
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/imathlimit/get_base/
---
## IMathLimit::get_Base() 方法

基礎參數

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Base()=0
```

## 備註

範例:
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto baseArg = limitElement->get_Base();
```

## 另請參閱

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [IMathLimit](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)