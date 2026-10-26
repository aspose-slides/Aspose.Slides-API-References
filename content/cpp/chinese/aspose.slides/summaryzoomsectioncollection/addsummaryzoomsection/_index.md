---
title: AddSummaryZoomSection()
second_title: Aspose.Slides C++ API 参考
description: 创建新的 Summary Zoom Section 对象并将其添加到集合中
type: docs
weight: 53
url: /zh/aspose.slides/summaryzoomsectioncollection/addsummaryzoomsection/
---
## SummaryZoomCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) 方法

创建新的 Summary Zoom [Section](../../section/) 对象并将其添加到集合中

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) 用于新的 Summary Zoom [Section](../../section/) 元素 [ISection](../../isection/) |

### 返回值

已添加 [ISummaryZoomFrame](../../isummaryzoomframe/) 元素

## 备注

如果集合中已经存在此章节的元素，则返回现有元素。

示例演示如何通过索引获取 Summary Zoom [Section](../../section/) 元素：

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ISummaryZoomSection](../../isummaryzoomsection/)
* 类 [ISection](../../isection/)
* 类 [SummaryZoomSectionCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)