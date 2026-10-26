---
title: set_UpperLimit()
second_title: Aspose.Slides for C++ API 參考文件
description: 指定上限或下限
type: docs
weight: 40
url: /zh-hant/aspose.slides.mathtext/mathlimit/set_upperlimit/
---
## MathLimit::set_UpperLimit(bool) 方法


指定上限或下限

```cpp
void Aspose::Slides::MathText::MathLimit::set_UpperLimit(bool value) override
```

## 備註


範例:
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## 另請參閱

* 類別 [MathLimit](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)