---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Android via Java API Reference
description: Представляет обработчик сохранения изображений markdown события ImageSavingDelegate.ImageSavingDelegate.
type: docs
url: /ru/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

Представляет обработчик сохранения изображений markdown события \#ImageSavingDelegate.ImageSavingDelegate.

## Методы

| Метод | Описание |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Вызывается для каждого изображения, не являющегося SVG (bitmap или metafile), во время экспорта Markdown. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Вызывается для каждого изображения, не являющегося SVG (bitmap или metafile), во время экспорта Markdown. Верните true, чтобы использовать указанный link, или false, чтобы применить логику сохранения по умолчанию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Изображение, которое экспортируется (bitmap или metafile). |
| format | int | Формат изображения. |
| link | java.lang.String[] | Ссылка Markdown, используемая при возврате true. |

**Возвращаемое значение:**
boolean