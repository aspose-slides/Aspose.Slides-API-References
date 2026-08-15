---
title: GetTile()
second_title: Aspose.Slides C++ API 參考
description: 使用指定的顏色建立圖案填充的磚塊影像。
type: docs
weight: 53
url: /zh-hant/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) 方法

建立一個使用指定顏色的圖案填充磚塊影像。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | 圖案的背景 [System::Drawing::Color](../../../system.drawing/color/)。 |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | 圖案的前景 [System::Drawing::Color](../../../system.drawing/color/)。 |

### 返回值

磚塊 [System::Drawing::Bitmap](../../../system.drawing/bitmap/)。

## IPatternFormat::GetTile(System::Drawing::Color) 方法

建立圖案填充的磚塊影像。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | 在 ShapeEx 的 StyleEx 物件中定義的預設 [System::Drawing::Color](../../../system.drawing/color/)。填充的顏色可能取決於此。 |

### 返回值

磚塊 [System::Drawing::Bitmap](../../../system.drawing/bitmap/)。

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IImage](../../iimage/)
* 類別 [Color](../../../system.drawing/color/)
* 類別 [IPatternFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)