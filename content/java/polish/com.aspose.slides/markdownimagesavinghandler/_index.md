---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Java API Reference
description: Represents the markdown image saving handler of ImageSavingDelegate.ImageSavingDelegate event.
type: docs
url: /pl/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

Represents the markdown image saving handler of #ImageSavingDelegate.ImageSavingDelegate event.
## Metody

| Metoda | Opis |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Wywoływana dla każdego obrazu nie będącego SVG (bitmapa lub metafilu) podczas eksportu Markdown. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Wywoływana dla każdego obrazu nie będącego SVG (bitmapa lub metafilu) podczas eksportu Markdown. Zwróć true, aby użyć określonego linku, lub false, aby zastosować domyślną logikę zapisywania.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Obraz będący eksportowany (bitmapa lub metafilu). |
| format | int | Format obrazu. |
| link | java.lang.String[] | Link Markdown używany przy zwracaniu true. |

**Zwraca:**
boolean