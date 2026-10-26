---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Android via Java API 参考
description: 表示 SvgImageSavingDelegate.SvgImageSavingDelegate 事件的 markdown SVG 图像保存处理程序。
type: docs
url: /zh/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

表示 markdown SVG 图像保存处理程序的 \#SvgImageSavingDelegate.SvgImageSavingDelegate 事件。

## Methods

| 方法 | 描述 |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | 在 Markdown 导出期间为每个 SVG 图像调用。 |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

在 Markdown 导出期间为每个 SVG 图像调用。返回 true 以使用指定的链接，或返回 false 以应用默认的保存逻辑。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | 正在导出的 SVG 图像。 |
| link | java.lang.String[] | 返回 true 时要使用的 Markdown 链接。 |

**返回值:**
boolean