---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Java API Reference
description: Represents the markdown image saving handler of ImageSavingDelegate.ImageSavingDelegate event.
type: docs
url: /nl/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

Stelt de markdown-afbeelding opslaan-handler van \#ImageSavingDelegate.ImageSavingDelegate evenement voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Wordt aangeroepen voor elke niet-SVG-afbeelding (bitmap of metafile) tijdens het exporteren naar Markdown. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Wordt aangeroepen voor elke niet-SVG-afbeelding (bitmap of metafile) tijdens het exporteren naar Markdown. Retourneer true om de opgegeven link te gebruiken, of false om de standaard opslaan-logica toe te passen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | De afbeelding die wordt geëxporteerd (bitmap of metafile). |
| format | int | Het afbeeldingsformaat. |
| link | java.lang.String[] | De Markdown-link die moet worden gebruikt bij het retourneren van true. |

**Retourwaarde:**
boolean