---
title: RefreshThumbnail
second_title: Aspose.Sildes for .NET API Reference
description: 指定演示文稿缩略图是否会被刷新。可读写布尔值。默认值为true。
type: docs
weight: 30
url: /zh/aspose.slides.export/ipptxoptions/refreshthumbnail/
---

## IPptxOptions.RefreshThumbnail 属性

指定演示文稿缩略图是否会被刷新。可读写布尔值。默认值为 **true**。

```csharp
public bool RefreshThumbnail { get; set; }
```

### 备注

当选项值为 **true** 时，将生成新的缩略图。

当选项值为 **false** 时，当前缩略图将保持不变。

### 示例

示例：

```csharp
[C#]
using (Presentation pres = new Presentation("demo.pptx"))
{
    pres.Save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, new PptxOptions()
    {
        RefreshThumbnail = false
    });
}
```

### 另请参阅

* 接口 [IPptxOptions](../../ipptxoptions)
* 命名空间 [Aspose.Slides.Export](../../ipptxoptions)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->