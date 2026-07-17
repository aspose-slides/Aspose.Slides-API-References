---
title: RemoveSummaryZoomSection()
second_title: Aspose.Slides for C++ API 参考
description: 从集合中移除 Summary Zoom Section 对象。
type: docs
weight: 40
url: /zh/aspose.slides/isummaryzoomsectioncollection/removesummaryzoomsection/
---
## ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) 方法

从集合中移除 Summary Zoom [Section](../../section/) 对象。

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) 用于移除 Summary Zoom [Section](../../section/) 元素的 [ISection](../../isection/)。 |

## 备注

示例演示通过索引获取 Summary Zoom [Section](../../section/) 元素：

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->RemoveSummaryZoomSection(pres->get_Sections()->idx_get(1));
```

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [ISection](../../isection/)
* 类 [ISummaryZoomSectionCollection](../)
* 命名空间 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)