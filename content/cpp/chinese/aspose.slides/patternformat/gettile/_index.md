---
title: GetTile()
second_title: Aspose.Slides C++ API 参考
description: 使用指定的颜色创建图案填充的平铺图像。
type: docs
weight: 53
url: /zh/aspose.slides/patternformat/gettile/
---
## PatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) 方法

使用指定颜色创建图案填充的平铺图像。

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground) override
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | 图案的背景 [System::Drawing::Color](../../../system.drawing/color/)。 |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | 图案的前景 [System::Drawing::Color](../../../system.drawing/color/)。 |

### 返回值

平铺 [IImage](../../iimage/)。

## PatternFormat::GetTile(System::Drawing::Color) 方法

创建图案填充的平铺图像。

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color styleColor) override
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | 默认的 [System::Drawing::Color](../../../system.drawing/color/)。 |

### 返回值

平铺 [IImage](../../iimage/)。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IImage](../../iimage/)
* 类 [Color](../../../system.drawing/color/)
* 类 [PatternFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)