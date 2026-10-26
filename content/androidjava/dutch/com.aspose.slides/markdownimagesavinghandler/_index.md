---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Android via Java API Reference
description: Representeert de markdown-afbeeldingsbewaarhandler van het ImageSavingDelegate.ImageSavingDelegate-evenement.
type: docs
url: /nl/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

Representeert de markdown-afbeeldingsbewaarhandler van #ImageSavingDelegate.ImageSavingDelegate event.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Wordt aangeroepen voor elke non-SVG-afbeelding (bitmap of metafile) tijdens de Markdown-export. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Wordt aangeroepen voor elke non-SVG-afbeelding (bitmap of metafile) tijdens de Markdown-export. Retourneer true om de opgegeven link te gebruiken, of false om de standaard opslaglogica toe te passen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | De afbeelding die wordt geëxporteerd (bitmap of metafile). |
| format | int | Het afbeeldingsformaat. |
| link | java.lang.String[] | De Markdown-link die moet worden gebruikt wanneer true wordt geretourneerd. |

**Retourwaarde:**
boolean