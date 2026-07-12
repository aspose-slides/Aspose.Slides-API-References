---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the markdown image saving handler of ImageSavingDelegate.ImageSavingDelegate event.
type: docs
url: /de/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

Stellt den markdown image saving handler des ImageSavingDelegate.ImageSavingDelegate-Ereignisses dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Invoked for each non-SVG image (bitmap or metafile) during Markdown export. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Wird für jedes Nicht-SVG-Bild (Bitmap oder Metadatei) während des Markdown-Exports aufgerufen. Gibt true zurück, um den angegebenen Link zu verwenden, oder false, um die Standard-Speicherlogik anzuwenden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Das zu exportierende Bild (Bitmap oder Metadatei). |
| format | int | Das Bildformat. |
| link | java.lang.String[] | Der Markdown-Link, der verwendet wird, wenn true zurückgegeben wird. |

**Rückgabewert:**
boolean