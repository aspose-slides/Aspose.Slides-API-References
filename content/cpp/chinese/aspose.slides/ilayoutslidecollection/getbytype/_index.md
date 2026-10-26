---
title: GetByType()
second_title: Aspose.Slides C++ API 参考
description: 返回指定类型的第一张布局幻灯片。
type: docs
weight: 14
url: /zh/aspose.slides/ilayoutslidecollection/getbytype/
---
## ILayoutSlideCollection::GetByType(SlideLayoutType) 方法

返回指定类型的第一张布局幻灯片。

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::ILayoutSlideCollection::GetByType(SlideLayoutType type)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | [SlideLayoutType](../../slidelayouttype/) | 要查找的布局幻灯片类型。 |

### 返回值

[ILayoutSlide](../../ilayoutslide/) 带有指定类型的布局幻灯片，如果未找到布局则为 null。

## 参见

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [ILayoutSlide](../../ilayoutslide/)
* 类 [ILayoutSlideCollection](../)
* 命名空间 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)