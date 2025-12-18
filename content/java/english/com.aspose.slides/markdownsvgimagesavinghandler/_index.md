---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Java API Reference
description: Represents the markdown SVG image saving handler of SvgImageSavingDelegate.SvgImageSavingDelegate event.
type: docs
url: /com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

Represents the markdown SVG image saving handler of \#SvgImageSavingDelegate.SvgImageSavingDelegate event.
## Methods

| Method | Description |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | Invoked for each SVG image during Markdown export. |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```


Invoked for each SVG image during Markdown export. Return true to use the specified link, or false to apply the default saving logic.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | The SVG image being exported. |
| link | java.lang.String[] | The Markdown link to use when returning true. |

**Returns:**
boolean
