---
title: set_BaseJustification()
second_title: Aspose.Slides for C++ API 參考
description: "指定相對於周圍文字的垂直對齊方式。可能的值有 top、bottom 和 center。預設值：Center"
type: docs
weight: 66
url: /zh-hant/aspose.slides.mathtext/mathmatrix/set_basejustification/
---
## MathMatrix::set_BaseJustification(MathVerticalAlignment) 方法

指定相對於周圍文字的垂直對齊方式。可能的值有 top、bottom 和 center。預設值：Center

```cpp
void Aspose::Slides::MathText::MathMatrix::set_BaseJustification(MathVerticalAlignment value) override
```

## 備註

範例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## 另請參閱

* 列舉 [MathVerticalAlignment](../../mathverticalalignment/)
* 類別 [MathMatrix](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)