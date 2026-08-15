---
title: get_UpperLimit()
second_title: Aspose.Slides for C++ API 參考
description: 指定上限或下限
type: docs
weight: 27
url: /zh-hant/aspose.slides.mathtext/mathlimit/get_upperlimit/
---
## MathLimit::get_UpperLimit() 方法


指定上限或下限

```cpp
bool Aspose::Slides::MathText::MathLimit::get_UpperLimit() override
```

## 備註


範例：
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## 另見

* 類別 [MathLimit](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)