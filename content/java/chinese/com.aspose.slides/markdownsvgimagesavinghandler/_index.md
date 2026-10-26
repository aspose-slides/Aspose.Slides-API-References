---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Java API Reference
description: Represents the markdown SVG image saving handler of SvgImageSavingDelegate.SvgImageSavingDelegate event.
type: docs
url: /zh/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

表示 \#SvgImageSavingDelegate.SvgImageSavingDelegate 事件的 markdown SVG 图像保存处理程序。
## 方法

| 方法 | 描述 |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | 在 Markdown 导出期间为每个 SVG 图像调用此方法。 |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```


在 Markdown 导出期间为每个 SVG 图像调用此方法。返回 true 以使用指定的链接，返回 false 则应用默认保存逻辑。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | 正在导出的 SVG 图像。 |
| link | java.lang.String[] | 返回 true 时使用的 Markdown 链接。 |

**返回值：**
boolean