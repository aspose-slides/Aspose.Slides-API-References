---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides dla Java API Reference
description: Reprezentuje obsługę zapisywania obrazów SVG w formacie markdown zdarzenia SvgImageSavingDelegate.SvgImageSavingDelegate.
type: docs
url: /pl/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

Reprezentuje obsługę zapisywania obrazów SVG w formacie markdown zdarzenia \#SvgImageSavingDelegate.SvgImageSavingDelegate event.
## Metody

| Metoda | Opis |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | Wywoływana dla każdego obrazu SVG podczas eksportu Markdown. |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

Wywoływana dla każdego obrazu SVG podczas eksportu Markdown. Zwróć true, aby użyć określonego linku, lub false, aby zastosować domyślną logikę zapisu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Obraz SVG poddawany eksportowi. |
| link | java.lang.String[] | Link Markdown do użycia, gdy zwrócono true. |

**Zwraca:**
boolean