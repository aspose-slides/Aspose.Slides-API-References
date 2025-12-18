---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the markdown image saving handler of ImageSavingDelegate.ImageSavingDelegate event.
type: docs
url: /com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

Represents the markdown image saving handler of \#ImageSavingDelegate.ImageSavingDelegate event.
## Methods

| Method | Description |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Invoked for each non-SVG image (bitmap or metafile) during Markdown export. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```


Invoked for each non-SVG image (bitmap or metafile) during Markdown export. Return true to use the specified link, or false to apply the default saving logic.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | The image being exported (bitmap or metafile). |
| format | int | The image format. |
| link | java.lang.String[] | The Markdown link to use when returning true. |

**Returns:**
boolean
