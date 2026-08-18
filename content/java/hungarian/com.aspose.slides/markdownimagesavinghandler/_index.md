---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides Java API-referencia
description: Képviseli a markdown kép mentés kezelőjét az ImageSavingDelegate.ImageSavingDelegate eseményhez.
type: docs
url: /hu/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

A markdown kép mentés kezelőjét a \#ImageSavingDelegate.ImageSavingDelegate esemény képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Minden nem SVG kép (bitmap vagy metafájl) esetén meghívásra kerül a Markdown export során. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Minden nem SVG kép (bitmap vagy metafájl) esetén meghívásra kerül a Markdown export során. A true visszatérési érték a megadott link használatát jelenti, a false az alapértelmezett mentési logika alkalmazását.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | A exportált kép (bitmap vagy metafájl). |
| format | int | A képformátum. |
| link | java.lang.String[] | A Markdown link, amelyet akkor használ, ha true értékkel tér vissza. |

**Visszatérési érték:**
boolean