---
title: IndexOf()
second_title: Aspose.Slides C++ API 参考
description: 返回指定 SummaryZoomSection 对象的索引。
type: docs
weight: 66
url: /zh/aspose.slides/summaryzoomsectioncollection/indexof/
---
## SummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) 方法

返回指定 [SummaryZoomSection](../../summaryzoomsection/) 对象的索引。

```cpp
int32_t Aspose::Slides::SummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/) 对象用于查找 [ISummaryZoomSection](../../isummaryzoomsection/)。 |

### 返回值

[SummaryZoomSection](../../summaryzoomsection/) 对象的索引，如果 [SummaryZoomSection](../../summaryzoomsection/) 对象不属于此集合则返回 -1。

## 备注

以下示例演示了如何通过索引获取 Summary Zoom [Section](../../section/) 元素：
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
int32_t idx = collection->IndexOf(selectedObject);
```

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ISummaryZoomSection](../../isummaryzoomsection/)
* 类 [SummaryZoomSectionCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)