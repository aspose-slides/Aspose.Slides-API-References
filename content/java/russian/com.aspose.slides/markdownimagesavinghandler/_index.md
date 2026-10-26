---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Java API Reference
description: Представляет обработчик сохранения изображений в markdown события ImageSavingDelegate.ImageSavingDelegate.
type: docs
url: /ru/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

Представляет обработчик сохранения изображений в markdown события \#ImageSavingDelegate.ImageSavingDelegate.

## Методы

| Метод | Описание |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Вызывается для каждого изображения, не являющегося SVG (растрового или метафайла) во время экспорта Markdown. |

### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Вызывается для каждого изображения, не являющегося SVG (растрового или метафайла) во время экспорта Markdown. Верните true, чтобы использовать указанный link, или false, чтобы применить логику сохранения по умолчанию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Изображение, которое экспортируется (растровое или метафайл). |
| format | int | Формат изображения. |
| link | java.lang.String[] | Markdown-link, используемый при возврате true. |

**Возвращаемое значение:**
boolean