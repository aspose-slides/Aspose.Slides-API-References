---
title: AddSummaryZoomSection
second_title: Aspose.Sildes for .NET API Reference
description: 创建新的摘要缩放节对象并将其添加到集合中
type: docs
weight: 50
url: /zh/aspose.slides/summaryzoomsectioncollection/addsummaryzoomsection/
---

## SummaryZoomSectionCollection.AddSummaryZoomSection 方法

创建新的摘要缩放节对象并将其添加到集合中

```csharp
public ISummaryZoomSection AddSummaryZoomSection(ISection section)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| section | ISection | 新摘要缩放节元素的节 [`ISection`](../../isection) |

### 返回值

添加的 [`ISummaryZoomFrame`](../../isummaryzoomframe) 元素

### 异常

| 異常 | 条件 |
| --- | --- |
| ArgumentException | 引用的节不属于当前演示文稿或不包含任何幻灯片。 |

### 备注

如果该节的元素已经存在于集合中，则返回现有的元素。

### 示例

该示例演示如何通过索引获取摘要缩放节元素：

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame) pres.Slides[1].Shapes[0];
    ISummaryZoomSectionCollection collection = zoomFrame.SummaryZoomCollection;
    ISummaryZoomSection newZoomSection = collection.AddSummaryZoomSection(pres.Sections[3]);
}
```

### 另见

* 接口 [ISummaryZoomSection](../../isummaryzoomsection)
* 接口 [ISection](../../isection)
* 类 [SummaryZoomSectionCollection](../../summaryzoomsectioncollection)
* 命名空间 [Aspose.Slides](../../summaryzoomsectioncollection)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->