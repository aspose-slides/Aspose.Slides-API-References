---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides für die Java-API-Referenz
description: Stellt den markdown-Bildspeicherungs-Handler des ImageSavingDelegate.ImageSavingDelegate-Ereignisses dar.
type: docs
url: /de/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

Stellt den markdown-Bildspeicherungs-Handler des \#ImageSavingDelegate.ImageSavingDelegate Ereignisses dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Wird für jedes Nicht-SVG-Bild (Bitmap oder Metadatei) während des Markdown-Exports aufgerufen. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Wird für jedes Nicht-SVG-Bild (Bitmap oder Metadatei) während des Markdown-Exports aufgerufen. Gibt true zurück, um den angegebenen Link zu verwenden, oder false, um die Standardspeicherlogik anzuwenden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Das zu exportierende Bild (Bitmap oder Metadatei). |
| format | int | Das Bildformat. |
| link | java.lang.String[] | Der Markdown-Link, der verwendet wird, wenn true zurückgegeben wird. |

**Rückgabewert:**
boolean