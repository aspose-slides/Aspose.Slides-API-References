---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Java API Reference
description: Represents the markdown SVG image saving handler of SvgImageSavingDelegate.SvgImageSavingDelegate event.
type: docs
url: /de/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

Stellt den markdown SVG-Bildspeicherungs-Handler des #SvgImageSavingDelegate.SvgImageSavingDelegate-Ereignisses dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | Wird für jedes SVG-Bild beim Markdown-Export aufgerufen. |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

Wird für jedes SVG-Bild beim Markdown-Export aufgerufen. Gibt true zurück, um den angegebenen Link zu verwenden, oder false, um die standardmäßige Speicherlogik anzuwenden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Das SVG-Bild, das exportiert wird. |
| link | java.lang.String[] | Der Markdown-Link, der verwendet wird, wenn true zurückgegeben wird. |

**Rückgabewert:**
boolean