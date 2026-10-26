---
title: SetSize()
second_title: Aspose.Slides C++ API 参考
description: "通过类型设置幻灯片大小并缩放现有内容。将任何非 SlideSizeType::Custom 的值分配会根据所选类型调整 ISlideSize::get_Size，同时保留 ISlideSize::get_Orientation。"
type: docs
weight: 53
url: /zh/aspose.slides/islidesize/setsize/
---
## ISlideSize::SetSize(SlideSizeType, SlideSizeScaleType) 方法

通过类型设置幻灯片大小并缩放现有内容。将任何非 [SlideSizeType::Custom](../../slidesizetype/) 的值分配给该属性会根据所选类型调整 [ISlideSize::get_Size](../get_size/)，同时保留 [ISlideSize::get_Orientation](../get_orientation/)。

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | 要应用的预定义幻灯片大小。 |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | 要使用的内容缩放模式。 |

## 备注

将任何非 [SlideSizeType::Custom](../../slidesizetype/) 的值分配给该属性会根据所选类型调整 [System::Drawing::Size](../../../system.drawing/size/)，同时保留 [Orientation](../../orientation/)。

## ISlideSize::SetSize(float, float, SlideSizeScaleType) 方法

显式设置幻灯片尺寸并缩放现有内容。这会将 [ISlideSize::get_Type](../get_type/) 值重置为 [SlideSizeType::Custom](../../slidesizetype/) 并设置 [ISlideSize::get_Orientation](../get_orientation/)。

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| width | **float** | 新的幻灯片宽度（单位：磅）。 |
| height | **float** | 新的幻灯片高度（单位：磅）。 |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | 要使用的内容缩放模式。 |

## 备注

这会将 [ISlideSize::get_Type](../get_type/) 属性重置为 [SlideSizeType::Custom](../../slidesizetype/) 并设置 [Orientation](../../orientation/)。

## 另请参见

* 枚举 [SlideSizeType](../../slidesizetype/)
* 枚举 [SlideSizeScaleType](../../slidesizescaletype/)
* 类 [ISlideSize](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)