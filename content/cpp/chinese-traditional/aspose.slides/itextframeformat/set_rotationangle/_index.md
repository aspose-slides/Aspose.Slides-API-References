---
title: set_RotationAngle()
second_title: Aspose.Slides for C++ API 參考
description: 指定套用在邊框內文字的自訂旋轉角度。如果未指定，則使用伴隨形狀的旋轉。如果已指定，則此旋轉會獨立於形狀而應用。也就是說，形狀可以有旋轉，同時文字本身也會有旋轉。此屬性與屬性 TextVerticalType 中的預定義垂直類型共同匯總形成視覺文字旋轉的最終值。寫入 float.
type: docs
weight: 352
url: /zh-hant/aspose.slides/itextframeformat/set_rotationangle/
---
## ITextFrameFormat::set_RotationAngle(float) 方法

指定套用於邊框內文字的自訂旋轉角度。如果未指定，則使用伴隨形狀的旋轉。如果已指定，則此旋轉會獨立於形狀而應用。也就是說，形狀可以有其旋轉，同時文字本身也會有旋轉。此屬性與屬性 TextVerticalType 中的預定義垂直類型共同匯總形成視覺文字旋轉的最終值。寫入 **float**。

```cpp
virtual void Aspose::Slides::ITextFrameFormat::set_RotationAngle(float value)=0
```

## 備註

考慮一個情況，形狀被套用 90 度順時針旋轉。此外，文字本身被套用 -90 度逆時針旋轉。如此一來，最終的形狀看起來已旋轉，但其中的文字卻彷彿完全未被旋轉。

## 另請參閱

* 類別 [ITextFrameFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)