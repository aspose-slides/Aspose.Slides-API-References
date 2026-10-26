---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the markdown SVG image saving handler of SvgImageSavingDelegate.SvgImageSavingDelegate event.
type: docs
url: /ru/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

Представляет обработчик сохранения SVG-изображений markdown события #SvgImageSavingDelegate.SvgImageSavingDelegate.

## Методы

| Method | Description |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | Вызывается для каждого SVG-изображения при экспорте в Markdown. |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```


Вызывается для каждого SVG-изображения при экспорте в Markdown. Верните true, чтобы использовать указанный link, или false, чтобы применить стандартную логику сохранения.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Экспортируемое SVG-изображение. |
| link | java.lang.String[] | Ссылка Markdown, используемая при возврате true. |

**Returns:**
boolean