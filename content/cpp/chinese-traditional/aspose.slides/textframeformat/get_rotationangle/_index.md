---
title: get_RotationAngle()
second_title: Aspose.Slides for C++ API 參考
description: 指定套用於邊界框內文字的自訂旋轉。如果未指定，則使用伴隨形狀的旋轉。如果已指定，則此旋轉會獨立於形狀應用。也就是說，形狀可以有旋轉，同時文字本身也可以有旋轉。此屬性與屬性 TextVerticalType 中的預定義垂直類型共同彙總得到的視覺文字旋轉值。讀取 float.
type: docs
weight: 300
url: /zh-hant/aspose.slides/textframeformat/get_rotationangle/
---
## TextFrameFormat::get_RotationAngle() 方法

指定套用於邊界框內文字的自訂旋轉。如果未指定，則使用伴隨形狀的旋轉。如果已指定，則此旋轉會獨立於形狀應用。也就是說，形狀可以有旋轉，同時文字本身也可以有旋轉。此屬性與屬性 TextVerticalType 中的預定義垂直類型共同彙總得到的視覺文字旋轉值。讀取 **float**。

```cpp
float Aspose::Slides::TextFrameFormat::get_RotationAngle() override
```

## 備註

考慮一個形狀被套用 90 度順時針旋轉的情況。除此之外，文字本身又被套用 -90 度逆時針旋轉。如此一來，最終的形狀看起來已旋轉，但其中的文字看起來彷彿根本沒有被旋轉。

## 另見

* 類別 [TextFrameFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)