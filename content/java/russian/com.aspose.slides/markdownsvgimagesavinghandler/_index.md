---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Java API Reference
description: Represents the markdown SVG image saving handler of SvgImageSavingDelegate.SvgImageSavingDelegate event.
type: docs
url: /ru/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

Представляет обработчик сохранения SVG-изображений markdown события \#SvgImageSavingDelegate.SvgImageSavingDelegate.

## Методы

| Method | Description |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | Вызывается для каждого SVG-изображения во время экспорта Markdown. |

### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

Вызывается для каждого SVG-изображения во время экспорта Markdown. Верните true, чтобы использовать указанный link, или false, чтобы применить логику сохранения по умолчанию.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | SVG-изображение, экспортируемое. |
| link | java.lang.String[] | Markdown-ссылка, используемая при возврате true. |

**Возвращаемое значение:**  
boolean