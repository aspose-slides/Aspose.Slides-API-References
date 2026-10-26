---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Java API Reference
description: Represents the markdown SVG image saving handler of SvgImageSavingDelegate.SvgImageSavingDelegate event.
type: docs
url: /hu/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

A markdown SVG kép mentési kezelő a SvgImageSavingDelegate.SvgImageSavingDelegate eseményhez.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | Minden SVG kép esetén meghívódik a Markdown exportálás során. |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

Minden SVG kép esetén meghívódik a Markdown exportálás során. Ha true-t ad vissza, a megadott linket használja, különben false esetén az alapértelmezett mentési logikát alkalmazza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Az exportálandó SVG kép. |
| link | java.lang.String[] | A Markdown link, amely true visszatéréskor használható. |

**Visszatérési érték:**
boolean