---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Java API Reference
description: Represents the markdown image saving handler of ImageSavingDelegate.ImageSavingDelegate event.
type: docs
url: /cs/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

Reprezentuje obslužnou rutinu ukládání obrázků pro markdown události \#ImageSavingDelegate.ImageSavingDelegate.

## Metody

| Method | Description |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Vyvoláno pro každý ne-SVG obrázek (bitmapa nebo metafile) během exportu do Markdownu. |

### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Vyvoláno pro každý ne-SVG obrázek (bitmapa nebo metafile) během exportu do Markdownu. Vraťte true pro použití zadaného odkazu nebo false pro použití výchozí logiky ukládání.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Obrázek, který se exportuje (bitmapa nebo metafile). |
| format | int | Formát obrázku. |
| link | java.lang.String[] | Odkaz Markdown, který se použije při vrácení true. |

**Vrací:**
boolean