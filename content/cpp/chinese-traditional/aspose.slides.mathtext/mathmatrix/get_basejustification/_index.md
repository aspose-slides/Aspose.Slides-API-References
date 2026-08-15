---
title: get_BaseJustification()
second_title: Aspose.Slides for C++ API 參考文件
description: "指定相對於周圍文字的垂直對齊方式。可能的值有 top、bottom 和 center。預設：Center"
type: docs
weight: 53
url: /zh-hant/aspose.slides.mathtext/mathmatrix/get_basejustification/
---
## MathMatrix::get_BaseJustification() 方法


指定相對於周圍文字的垂直對齊方式。可能的值有 top、bottom 和 center。預設：Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathMatrix::get_BaseJustification() override
```

## 備註


範例： 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## 另請參閱

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* 類別 [MathMatrix](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)