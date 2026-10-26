---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the markdown SVG image saving handler of SvgImageSavingDelegate.SvgImageSavingDelegate event.
type: docs
url: /de/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

Stellt den Markdown SVG Bild Speicherungs Handler des #SvgImageSavingDelegate.SvgImageSavingDelegate Ereignisses dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | Wird für jedes SVG Bild während des Markdown-Exports aufgerufen. |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

Wird für jedes SVG Bild während des Markdown-Exports aufgerufen. Gibt true zurück, um den angegebenen Link zu verwenden, oder false, um die Standard-Speicherlogik anzuwenden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Das exportierte SVG Bild. |
| link | java.lang.String[] | Der Markdown-Link, der verwendet wird, wenn true zurückgegeben wird. |

**Rückgabewert:**
boolean