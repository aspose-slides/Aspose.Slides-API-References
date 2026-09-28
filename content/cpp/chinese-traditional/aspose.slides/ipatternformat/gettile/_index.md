---
title: GetTile()
second_title: Aspose.Slides for C++ API 參考
description: 建立具有指定顏色的圖案填充平鋪圖像。
type: docs
weight: 53
url: /zh-hant/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) method

建立具有指定顏色的圖案填充平鋪圖像。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | 圖案的背景 [System::Drawing::Color](../../../system.drawing/color/)。 |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | 圖案的前景 [System::Drawing::Color](../../../system.drawing/color/)。 |

### Return Value

圖塊 [IImage](../../iimage/).

## IPatternFormat::GetTile(System::Drawing::Color) method

建立圖案填充的平鋪圖像。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | 在 ShapeEx 的 StyleEx 物件中定義的預設 [System::Drawing::Color](../../../system.drawing/color/)。填充的顏色可能取決於此。 |

### Return Value

圖塊 [IImage](../../iimage/)。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [Color](../../../system.drawing/color/)
* Class [IPatternFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)