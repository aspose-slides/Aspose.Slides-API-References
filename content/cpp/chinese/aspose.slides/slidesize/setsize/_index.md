---
title: SetSize()
second_title: Aspose.Slides for C++ API 参考
description: 通过类型设置幻灯片大小并对现有内容进行缩放。
type: docs
weight: 53
url: /zh/aspose.slides/slidesize/setsize/
---
## SlideSize::SetSize(SlideSizeType, SlideSizeScaleType) 方法

通过类型设置幻灯片大小并对现有内容进行缩放。

```cpp
void Aspose::Slides::SlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | 要应用的预定义幻灯片大小。 |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | 要使用的内容缩放模式。 |
## 备注

将除 [SlideSizeType::Custom](../../slidesizetype/) 之外的任何值分配时，会根据所选类型调整 [SlideSize::get_Size](../get_size/)，同时保留 [SlideSize::get_Orientation](../get_orientation/)。

## SlideSize::SetSize(float, float, SlideSizeScaleType) 方法

显式设置幻灯片尺寸并对现有内容进行缩放。

```cpp
void Aspose::Slides::SlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| width | **float** | 新的幻灯片宽度（单位为点）。 |
| height | **float** | 新的幻灯片高度（单位为点）。 |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | 要使用的内容缩放模式。 |
## 备注

这会将 [SlideSize::get_Type](../get_type/) 属性重置为 [SlideSizeType::Custom](../../slidesizetype/) 并设置 [Orientation](../../orientation/)。

## 另请参阅

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* 类 [SlideSize](../)
* 命名空间 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)