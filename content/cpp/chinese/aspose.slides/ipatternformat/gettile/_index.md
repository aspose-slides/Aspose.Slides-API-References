---
title: GetTile()
second_title: Aspose.Slides C++ API 参考
description: 使用指定颜色创建图案填充的瓦片图像。
type: docs
weight: 53
url: /zh/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) 方法

使用指定颜色创建图案填充的瓦片图像。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | 图案的背景[System::Drawing::Color](../../../system.drawing/color/)。 |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | 图案的前景[System::Drawing::Color](../../../system.drawing/color/)。 |

### 返回值

瓦片 [System::Drawing::Bitmap](../../../system.drawing/bitmap/)。

## IPatternFormat::GetTile(System::Drawing::Color) 方法

创建图案填充的瓦片图像。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | 默认的[System::Drawing::Color](../../../system.drawing/color/)，在 ShapeEx 的 StyleEx 对象中定义。填充的颜色可能取决于此。 |

### 返回值

瓦片 [System::Drawing::Bitmap](../../../system.drawing/bitmap/)。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IImage](../../iimage/)
* 类 [Color](../../../system.drawing/color/)
* 类 [IPatternFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)