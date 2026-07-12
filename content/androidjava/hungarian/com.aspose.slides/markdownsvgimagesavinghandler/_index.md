---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Android Java API hivatkozás
description: A markdown SVG képmentési kezelője a SvgImageSavingDelegate.SvgImageSavingDelegate eseményhez.
type: docs
url: /hu/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

A markdown SVG képmentési kezelője a \#SvgImageSavingDelegate.SvgImageSavingDelegate eseményhez.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | Invoked for each SVG image during Markdown export. |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

Minden SVG kép esetén meghívásra kerül a Markdown exportálás során. Visszatérési érték true, ha a megadott hivatkozást kell használni, vagy false, ha az alapértelmezett mentési logikát kell alkalmazni.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Az exportálandó SVG kép. |
| link | java.lang.String[] | A Markdown hivatkozás, amely true visszatérítés esetén használható. |

**Visszatérési érték:**
boolean