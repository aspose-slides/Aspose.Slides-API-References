---
title: SlidesLayoutOptions
second_title: Aspose.Slides for .NET API Reference
description: 获取或设置导出演示文稿时幻灯片在页面上放置的模式 ISlidesLayoutOptionsaspose.slides/islideslayoutoptions.
type: docs
weight: 70
url: /zh/aspose.slides.export/html5options/slideslayoutoptions/
---

## Html5Options.SlidesLayoutOptions 属性

获取或设置导出演示文稿时幻灯片在页面上放置的模式 [`ISlidesLayoutOptions`](../../islideslayoutoptions).

```csharp
public ISlidesLayoutOptions SlidesLayoutOptions { get; set; }
```

### 示例

示例:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    Html5Options options = new Html5Options
    {
        SlidesLayoutOptions = new HandoutLayoutingOptions
        {
            Handout = HandoutType.Handouts4Horizontal
        }
    };
    
    pres.Save("pres.html", SaveFormat.Html5, options);
}
```

### 另请参阅

* 接口 [ISlidesLayoutOptions](../../islideslayoutoptions)
* 类 [Html5Options](../../html5options)
* 命名空间 [Aspose.Slides.Export](../../html5options)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->