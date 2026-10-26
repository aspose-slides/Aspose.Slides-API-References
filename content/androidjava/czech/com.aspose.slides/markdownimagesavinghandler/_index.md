---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the markdown image saving handler of ImageSavingDelegate.ImageSavingDelegate event.
type: docs
url: /cs/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

Representuje handler pro ukládání markdown obrázků události \#ImageSavingDelegate.ImageSavingDelegate.

## Metody

| Metoda | Popis |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Vyzváno pro každý obrázek, který není SVG (bitmapa nebo metasoubor), během exportu do Markdown. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Vyzváno pro každý obrázek, který není SVG (bitmapa nebo metasoubor), během exportu do Markdown. Vraťte true pro použití zadaného odkazu nebo false pro použití výchozí logiky ukládání.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Obrázek, který se exportuje (bitmapa nebo metasoubor). |
| format | int | Formát obrázku. |
| link | java.lang.String[] | Odkaz Markdown, který se použije při vrácení true. |

**Vrací:**
boolean