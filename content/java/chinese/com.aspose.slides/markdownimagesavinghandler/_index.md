---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Java API Reference
description: Represents the markdown image saving handler of ImageSavingDelegate.ImageSavingDelegate event.
type: docs
url: /zh/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

表示 #ImageSavingDelegate.ImageSavingDelegate 事件的 markdown 图像保存处理程序。

## 方法

| 方法 | 描述 |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | 在 Markdown 导出期间，对每个非 SVG 图像（位图或元文件）调用此方法。 |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

在 Markdown 导出期间，对每个非 SVG 图像（位图或元文件）调用此方法。返回 true 以使用指定的链接，返回 false 则采用默认的保存逻辑。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | 正在导出的图像（位图或元文件）。 |
| format | int | 图像格式。 |
| link | java.lang.String[] | 在返回 true 时使用的 Markdown 链接。 |

**返回值:**
boolean