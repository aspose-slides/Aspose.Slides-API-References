---
title: ISwfOptions
second_title: Aspose.Sildes for .NET API Reference
description: 提供控制演示文稿如何以SWF格式保存的选项。
type: docs
weight: 3980
url: /zh/aspose.slides.export/iswfoptions/
---

## ISwfOptions 接口

提供控制演示文稿如何以SWF格式保存的选项。

```csharp
public interface ISwfOptions : ISaveOptions
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AsISaveOptions](../../aspose.slides.export/iswfoptions/asisaveoptions) { get; } | 返回 ISaveOptions 接口。只读 [`ISaveOptions`](../isaveoptions)。 |
| [Compressed](../../aspose.slides.export/iswfoptions/compressed) { get; set; } | 指定生成的SWF文档是否应被压缩。默认值为 `true`。 |
| [EnableContextMenu](../../aspose.slides.export/iswfoptions/enablecontextmenu) { get; set; } | 启用/禁用上下文菜单。默认值为 true。 |
| [JpegQuality](../../aspose.slides.export/iswfoptions/jpegquality) { get; set; } | 指定JPEG图像的质量。默认值为95。 |
| [LogoImageBytes](../../aspose.slides.export/iswfoptions/logoimagebytes) { get; set; } | 将显示为查看器右上角的标志的图像。图像应为32x64像素的PNG图像，否则可能会错误显示标志。 |
| [LogoLink](../../aspose.slides.export/iswfoptions/logolink) { get; set; } | 获取或设置标志的完整超链接地址。仅在指定了 [`LogoImageBytes`](./logoimagebytes) 时有效。 |
| [ShowBottomPane](../../aspose.slides.export/iswfoptions/showbottompane) { get; set; } | 显示/隐藏底部面板。可在flashvars中覆盖。默认值为true。 |
| [ShowFullScreen](../../aspose.slides.export/iswfoptions/showfullscreen) { get; set; } | 显示/隐藏全屏按钮。可在flashvars中覆盖。默认值为true。 |
| [ShowHiddenSlides](../../aspose.slides.export/iswfoptions/showhiddenslides) { get; set; } | 指定生成的文档是否应包括隐藏幻灯片。默认值为 `false`。 |
| [ShowLeftPane](../../aspose.slides.export/iswfoptions/showleftpane) { get; set; } | 显示/隐藏左侧面板。可在flashvars中覆盖。默认值为true。 |
| [ShowPageBorder](../../aspose.slides.export/iswfoptions/showpageborder) { get; set; } | 指定页面周围的边框是否应显示。默认值为true。 |
| [ShowPageStepper](../../aspose.slides.export/iswfoptions/showpagestepper) { get; set; } | 显示/隐藏页面步骤器。可在flashvars中覆盖。默认值为true。 |
| [ShowSearch](../../aspose.slides.export/iswfoptions/showsearch) { get; set; } | 显示/隐藏搜索部分。可在flashvars中覆盖。默认值为true。 |
| [ShowTopPane](../../aspose.slides.export/iswfoptions/showtoppane) { get; set; } | 显示/隐藏整个顶部面板。可在flashvars中覆盖。默认值为true。 |
| [SlidesLayoutOptions](../../aspose.slides.export/iswfoptions/slideslayoutoptions) { get; set; } | 获取或设置导出演示文稿时幻灯片在页面上的排列模式 [`ISlidesLayoutOptions`](../islideslayoutoptions)。此属性不支持分配类型为 `Aspose.Slides.Export.HandoutLayoutingOptions` 的对象。 |
| [StartOpenLeftPane](../../aspose.slides.export/iswfoptions/startopenleftpane) { get; set; } | 开始时打开左侧面板。可在flashvars中覆盖。默认值为false。 |
| [ViewerIncluded](../../aspose.slides.export/iswfoptions/viewerincluded) { get; set; } | 指定生成的SWF文档是否应包含集成的文档查看器。默认值为 `true`。 |

### 另请参阅

* 接口 [ISaveOptions](../isaveoptions)
* 命名空间 [Aspose.Slides.Export](../../aspose.slides.export)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->