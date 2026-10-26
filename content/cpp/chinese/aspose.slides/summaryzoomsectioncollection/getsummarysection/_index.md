---
title: GetSummarySection()
second_title: Aspose.Slides C++ API 参考
description: 返回 给定章节的 Summary Zoom Section 元素。
type: docs
weight: 92
url: /zh/aspose.slides/summaryzoomsectioncollection/getsummarysection/
---
## SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) 方法


返回 给定章节的 Summary Zoom [Section](../../section/) 元素。

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) 以查找 [ISection](../../isection/) |

### 返回值

[ISummaryZoomSection](../../isummaryzoomsection/) 或 null 如果集合不包含该章节的元素。

## 备注



此示例演示通过索引获取 Summary Zoom [Section](../../section/) 元素：
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [ISummaryZoomSection](../../isummaryzoomsection/)
* 类 [ISection](../../isection/)
* 类 [SummaryZoomSectionCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)