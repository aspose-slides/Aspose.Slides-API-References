---
title: Title
second_title: Aspose.Sildes for .NET API 参考
description: 返回摘要缩放部分对象的文本标题。
type: docs
weight: 20
url: /zh/aspose.slides/summaryzoomsection/title/
---

## SummaryZoomSection.Title 属性

返回摘要缩放部分对象的文本标题。

```csharp
public string Title { get; set; }
```

### 示例

示例：

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomSection zoomSection = zoomFrame.SummaryZoomCollection[1];
    zoomSection.Title = "Title";
}
```

### 另请参见

* 类 [SummaryZoomSection](../../summaryzoomsection)
* 命名空间 [Aspose.Slides](../../summaryzoomsection)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->