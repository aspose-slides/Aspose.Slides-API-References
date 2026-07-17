---
title: FindShapesByPlaceholderType()
second_title: Aspose.Slides C++ API 参考
description: 在指定的幻灯片上搜索所有匹配给定占位符类型的形状。
type: docs
weight: 14
url: /zh/aspose.slides.util/slideutil/findshapesbyplaceholdertype/
---
## SlideUtil::FindShapesByPlaceholderType(System::SharedPtr\<IBaseSlide\>, PlaceholderType) method

在指定的幻灯片上搜索所有匹配给定占位符类型的形状。

```cpp
static System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::Util::SlideUtil::FindShapesByPlaceholderType(System::SharedPtr<IBaseSlide> slide, PlaceholderType placeholderType)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | 用于搜索形状的幻灯片。 |
| placeholderType | [PlaceholderType](../../../aspose.slides/placeholdertype/) | 用于过滤形状的占位符类型。 |

### 返回值

一个符合指定占位符类型的 [IShape](../../../aspose.slides/ishape/) 对象数组。

## 参见

* Enum [PlaceholderType](../../../aspose.slides/placeholdertype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IShape](../../../aspose.slides/ishape/)
* 类 [IBaseSlide](../../../aspose.slides/ibaseslide/)
* 类 [SlideUtil](../)
* 命名空间 [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)