---
title: GetTile()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立具有指定顏色的圖樣填充瓦片影像。
type: docs
weight: 53
url: /zh-hant/aspose.slides/patternformat/gettile/
---
## PatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) 方法

建立具有指定顏色的圖樣填充磚塊影像。

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | 圖案的背景 [System::Drawing::Color](../../../system.drawing/color/) |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | 圖案的前景 [System::Drawing::Color](../../../system.drawing/color/) |

### 回傳值

圖塊 [IImage](../../iimage/)。

## PatternFormat::GetTile(System::Drawing::Color) 方法

建立圖樣填充的磚塊影像。

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color styleColor) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | 預設的 [System::Drawing::Color](../../../system.drawing/color/) |

### 回傳值

圖塊 [IImage](../../iimage/)。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [Color](../../../system.drawing/color/)
* Class [PatternFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)