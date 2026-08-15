---
title: set_RotationAngle()
second_title: Aspose.Slides for C++ API 參考文件
description: 指定套用於邊框內文字的自訂旋轉角度。如果未指定，則使用伴隨形狀的旋轉角度。如果已指定，則此旋轉會獨立於形狀應用。也就是說，形狀可以有自己的旋轉，同時文字本身也可以有旋轉。最終的視覺文字旋轉值是由此屬性與屬性 TextVerticalType 中預定義的垂直類型綜合得出。寫入 float。
type: docs
weight: 313
url: /zh-hant/aspose.slides/textframeformat/set_rotationangle/
---
## TextFrameFormat::set_RotationAngle(float) 方法


指定套用於邊框內文字的自訂旋轉角度。如果未指定，則使用伴隨形狀的旋轉角度。如果已指定，則此旋轉會獨立於形狀應用。也就是說，形狀可以有自己的旋轉，同時文字本身也可以有旋轉。最終的視覺文字旋轉值是由此屬性與屬性 TextVerticalType 中預定義的垂直類型綜合得出。寫入 **float**。

```cpp
void Aspose::Slides::TextFrameFormat::set_RotationAngle(float value) override
```

## 備註


考慮這種情況：形狀被套用 90 度順時針旋轉。另外，文字本身被套用 -90 度逆時針旋轉。此時最終的形狀看起來仍有旋轉，但其中的文字則看起來彷彿根本沒有旋轉。

## 另請參閱

* 類別 [TextFrameFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)