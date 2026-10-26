---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the markdown image saving handler of ImageSavingDelegate.ImageSavingDelegate event.
type: docs
url: /sv/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

Representerar markdown-bildsparningshanteraren för ImageSavingDelegate.ImageSavingDelegate-händelsen.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Anropas för varje bild som inte är SVG (bitmap eller metafil) under Markdown-export. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Anropas för varje bild som inte är SVG (bitmap eller metafil) under Markdown-export. Returnera true för att använda den angivna länken, eller false för att tillämpa standardlagringslogiken.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Bilden som exporteras (bitmap eller metafil). |
| format | int | Bildformatet. |
| link | java.lang.String[] | Markdown-länken att använda när true returneras. |

**Returnerar:**
boolean