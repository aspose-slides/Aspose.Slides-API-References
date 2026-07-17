---
title: GetImage()
second_title: Aspose.Slides C++ API 参考
description: "返回形状缩略图。默认使用 ShapeThumbnailBounds::Shape 形状缩略图边界类型。"
type: docs
weight: 547
url: /zh/aspose.slides/ishape/getimage/
---
## IShape::GetImage() 方法


返回形状缩略图。[ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) 形状缩略图边界类型默认使用。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage()=0
```


### 返回值

[Shape](../../shape/) 缩略图。

## IShape::GetImage(ShapeThumbnailBounds, float, float) 方法


返回形状缩略图。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../../shape/) 缩略图边界类型。 |
| scaleX | **float** | X 缩放 |
| scaleY | **float** | Y 缩放 |

### 返回值

[Shape](../../shape/) 缩略图，或者在使用 [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) 且形状没有可见元素的情况下为 null。

## 另请参阅

* 枚举 [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IImage](../../iimage/)
* 类 [IShape](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)