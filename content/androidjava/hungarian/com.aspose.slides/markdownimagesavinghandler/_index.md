---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Android via Java API Reference
description: A markdown kép mentési kezelő a ImageSavingDelegate.ImageSavingDelegate eseményhez tartozik.
type: docs
url: /hu/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

A markdown kép mentési kezelő a #ImageSavingDelegate.ImageSavingDelegate eseményhez tartozik.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Minden nem SVG képre (bitmap vagy metafájl) meghívásra kerül a Markdown exportálás során. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Minden nem SVG képre (bitmap vagy metafájl) meghívásra kerül a Markdown exportálás során. A true értékkel a megadott hivatkozást használja, a false értékkel pedig az alapértelmezett mentési logikát alkalmazza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Az exportálandó kép (bitmap vagy metafájl). |
| format | int | A képformátum. |
| link | java.lang.String[] | A Markdown hivatkozás, amely true érték visszaadása esetén használatos. |

**Visszatérési érték:**
boolean