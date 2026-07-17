---
title: GetImage()
second_title: Aspose.Slides C++ API 参考
description: "返回形状缩略图。默认使用 ShapeThumbnailBounds::Shape 形状缩略图边界类型。"
type: docs
weight: 651
url: /zh/aspose.slides/shape/getimage/
---
## Shape::GetImage() 方法


返回形状缩略图。 [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) 默认使用形状缩略图边界类型。

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage() override
```


### 返回值

[Shape](../) 缩略图。

## Shape::GetImage(ShapeThumbnailBounds, float, float) 方法


返回形状缩略图。

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../) 缩略图边界类型。 |
| scaleX | **float** | X 缩放 |
| scaleY | **float** | Y 缩放 |

### 返回值

[Shape](../) 缩略图或 null，在使用 [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) 且形状没有可见元素的情况下。

## 另见

* 枚举 [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IImage](../../iimage/)
* 类 [Shape](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)