---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Java API Reference
description: Representerar markdown SVG-bildsparningshanteraren för SvgImageSavingDelegate.SvgImageSavingDelegate-händelsen.
type: docs
url: /sv/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

Representerar markdown SVG-bildsparningshanteraren för \#SvgImageSavingDelegate.SvgImageSavingDelegate-händelsen.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | Anropas för varje SVG-bild under Markdown-export. |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

Anropas för varje SVG-bild under Markdown-export. Returnera true för att använda den angivna länken, eller false för att tillämpa standardlagringslogiken.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | SVG-bilden som exporteras. |
| link | java.lang.String[] | Markdown-länken som ska användas när true returneras. |

**Returnerar:**
boolean