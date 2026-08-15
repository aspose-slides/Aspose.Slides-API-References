---
title: get_RotationAngle()
second_title: Aspose.Slides for C++ API 參考文件
description: 指定套用於邊框內文字的自訂旋轉角度。如果未指定，則使用隨附圖形的旋轉。如果已指定，則會獨立於圖形套用。也就是說，圖形可以有旋轉，同時文字本身也可以有旋轉。此屬性與屬性 TextVerticalType 中的預定義垂直類型共同彙總出視覺文字旋轉的最終值。讀取 float.
type: docs
weight: 235
url: /zh-hant/aspose.slides.charts/icharttextblockformat/get_rotationangle/
---
## IChartTextBlockFormat::get_RotationAngle() 方法


指定套用於邊框內文字的自訂旋轉角度。如果未指定，則使用隨附圖形的旋轉。如果已指定，則會獨立於圖形套用。也就是說，圖形可以有旋轉，同時文字本身也可以有旋轉。此屬性與屬性 TextVerticalType 中的預定義垂直類型共同彙總出視覺文字旋轉的最終值。讀取 **float**。

```cpp
virtual float Aspose::Slides::Charts::IChartTextBlockFormat::get_RotationAngle()=0
```

## 備註


考慮一個情況：圖形被套用 90 度順時針旋轉。除此之外，文字本身又被套用 -90 度逆時針旋轉。如此一來，圖形看起來仍然是旋轉的，但其中的文字看起來彷彿根本沒有被旋轉。

## 另請參閱

* 類別 [IChartTextBlockFormat](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)