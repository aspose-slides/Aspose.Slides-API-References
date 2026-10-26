---
title: FindShape()
second_title: Aspose.Slides for C++ API 参考
description: 在 PPTX 演示文稿中通过替代文本查找形状。
type: docs
weight: 1
url: /zh/aspose.slides.util/slideutil/findshape/
---
## SlideUtil::FindShape(System::SharedPtr\<IPresentation\>, System::String) 方法

在 PPTX 演示文稿中通过替代文本查找形状。

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IPresentation> pres, System::String altText)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | 扫描的演示文稿。 |
| altText | [System::String](../../../system/string/) | 形状的替代文本。 |

### 返回值

[Shape](../../../aspose.slides/shape/) 或 null。

## SlideUtil::FindShape(System::SharedPtr\<IBaseSlide\>, System::String) 方法

在 PPTX 演示文稿的幻灯片上通过替代文本查找形状。

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IBaseSlide> slide, System::String altText)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | 扫描的幻灯片。 |
| altText | [System::String](../../../system/string/) | 形状的替代文本。 |

### 返回值

[Shape](../../../aspose.slides/shape/) 或 null。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IShape](../../../aspose.slides/ishape/)
* 类 [IPresentation](../../../aspose.slides/ipresentation/)
* 类 [String](../../../system/string/)
* 类 [SlideUtil](../)
* 类 [IBaseSlide](../../../aspose.slides/ibaseslide/)
* 命名空间 [Aspose::Slides::Util](../../)
* 库 [Aspose.Slides](../../../)