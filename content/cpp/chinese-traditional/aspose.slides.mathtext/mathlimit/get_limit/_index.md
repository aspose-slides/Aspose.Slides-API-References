---
title: get_Limit()
second_title: Aspose.Slides for C++ API 參考文件
description: 限制參數
type: docs
weight: 14
url: /zh-hant/aspose.slides.mathtext/mathlimit/get_limit/
---
## MathLimit::get_Limit() 方法


限制參數

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Limit() override
```

## 備註


範例：
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathLimit](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)