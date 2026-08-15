---
title: set_RotationAngle()
second_title: Aspose.Slides for C++ API 參考文件
description: 指定套用於邊界框內文字的自訂旋轉。如果未指定，則使用伴隨形狀的旋轉。如果已指定，則此旋轉獨立於形狀。也就是說，形狀可以有旋轉，同時文字本身也可以有旋轉。從此屬性與屬性 TextVerticalType 中的預定義垂直類型彙總得到的視覺文字旋轉值。寫入 float。
type: docs
weight: 248
url: /zh-hant/aspose.slides.charts/icharttextblockformat/set_rotationangle/
---
## IChartTextBlockFormat::set_RotationAngle(float) 方法

指定套用於邊界框內文字的自訂旋轉。如果未指定，則使用伴隨形狀的旋轉。如果已指定，則此旋轉獨立於形狀。也就是說，形狀可以有旋轉，同時文字本身也可以有旋轉。從此屬性與屬性 TextVerticalType 中的預定義垂直類型彙總得到的視覺文字旋轉值。寫入 **float**。

```cpp
virtual void Aspose::Slides::Charts::IChartTextBlockFormat::set_RotationAngle(float value)=0
```

## 備註

考慮一個形狀已套用 90 度順時針旋轉的情況。除此之外，文字本身還套用 -90 度逆時針旋轉。如此一來，最終的形狀看起來仍是旋轉的，但其中的文字則彷彿根本未被旋轉。

## 另請參閱

* Class [IChartTextBlockFormat](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)