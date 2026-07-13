---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Android via Java API Reference
description: Reprezentuje obsługę zapisywania obrazów markdown zdarzenia ImageSavingDelegate.ImageSavingDelegate.
type: docs
url: /pl/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

Reprezentuje obsługę zapisywania obrazów markdown zdarzenia #ImageSavingDelegate.ImageSavingDelegate.

## Metody

| Metoda | Opis |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Wywoływana dla każdego obrazu nie-SVG (bitmapa lub metaplik) podczas eksportu Markdown. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Wywoływana dla każdego obrazu nie-SVG (bitmapa lub metaplik) podczas eksportu Markdown. Zwróć true, aby użyć określonego linku, lub false, aby zastosować domyślną logikę zapisywania.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Obraz eksportowany (bitmapa lub metaplik). |
| format | int | Format obrazu. |
| link | java.lang.String[] | Link Markdown używany, gdy zwracane jest true. |

**Zwraca:**
boolean