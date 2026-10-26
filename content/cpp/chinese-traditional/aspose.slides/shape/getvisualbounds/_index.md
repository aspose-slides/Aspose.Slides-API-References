---
title: GetVisualBounds()
second_title: Aspose.Slides for C++ API 參考
description: 取得依據已呈現內容計算出的圖形視覺邊界。
type: docs
weight: 677
url: /zh-hant/aspose.slides/shape/getvisualbounds/
---
## Shape::GetVisualBounds() 方法


取得依據已呈現內容計算出的圖形視覺邊界。

```cpp
System::Drawing::RectangleF Aspose::Slides::Shape::GetVisualBounds()
```


### Return Value

一個 [System::Drawing::RectangleF](../../../system.drawing/rectanglef/)，表示以投影片座標表示的圖形視覺邊界。

## Remarks


返回的矩形表示在投影片座標空間中，圖形在呈現過程中產生的所有內容之軸對齊邊界。

這些邊界可能與圖形的模型邊界 ([Shape::X](../), [Shape::Y](../), [Shape::Width](../), [Shape::Height](../)) 不同，且若已呈現的內容超出投影片原點，則可能包含負座標。

視覺邊界會考慮與呈現相關的因素，例如變換（例如旋轉）、筆劃寬度與接合、文字版面配置與溢位、[SmartArt](../../../aspose.slides.smartart/) 幾何形狀，以及其他影響圖形最終呈現外觀的版面效果。

返回的邊界不會被裁剪至投影片矩形。 

## See Also

* 類別 [RectangleF](../../../system.drawing/rectanglef/)
* 類別 [Shape](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)