---
title: get_RotationAngle()
second_title: Aspose.Slides for C++ API 參考文件
description: 指定套用於邊框內文字的自訂旋轉角度。若未指定，則使用伴隨圖形的旋轉角度。若已指定，則此旋轉會獨立於圖形而套用。也就是說，圖形本身可以有旋轉，同時文字也可以單獨旋轉。最終的視覺文字旋轉值由此屬性與屬性 TextVerticalType 中的預定義垂直類型綜合得出。Read float.
type: docs
weight: 339
url: /zh-hant/aspose.slides/itextframeformat/get_rotationangle/
---
## ITextFrameFormat::get_RotationAngle() 方法


指定套用於邊框內文字的自訂旋轉角度。若未指定，則使用伴隨圖形的旋轉角度。若已指定，則此旋轉會獨立於圖形而套用。也就是說，圖形本身可以有旋轉，同時文字也可以單獨旋轉。最終的視覺文字旋轉值由此屬性與屬性 TextVerticalType 中的預定義垂直類型綜合得出。讀取 **float**。

```cpp
virtual float Aspose::Slides::ITextFrameFormat::get_RotationAngle()=0
```

## 備註


考慮一個圖形已套用順時針 90 度的旋轉。同時，文字本身又套用逆時針 -90 度的旋轉。此時最終的圖形看起來仍保持旋轉，但其中的文字看起來彷彿根本沒有被旋轉。

## 參見

* 類別 [ITextFrameFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)