---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Java API-referens
description: Representerar markdown-bildsparningshanteraren för ImageSavingDelegate.ImageSavingDelegate-händelsen.
type: docs
url: /sv/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

Representerar markdown-bildsparningshanteraren för #ImageSavingDelegate.ImageSavingDelegate-händelsen.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Anropas för varje icke-SVG-bild (bitmap eller metafile) under Markdown-export. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Anropas för varje icke-SVG-bild (bitmap eller metafile) under Markdown-export. Returnera true för att använda den angivna länken, eller false för att tillämpa standardsparlogiken.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Bilden som exporteras (bitmap eller metafile). |
| format | int | Bildformatet. |
| link | java.lang.String[] | Markdown-länken som ska användas när true returneras. |

**Returnerar:**
boolean