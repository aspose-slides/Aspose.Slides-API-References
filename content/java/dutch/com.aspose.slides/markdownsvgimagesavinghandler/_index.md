---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides voor Java API-referentie
description: Stelt de markdown SVG image saving handler van SvgImageSavingDelegate.SvgImageSavingDelegate event voor.
type: docs
url: /nl/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

Stelt de markdown SVG image saving handler van #SvgImageSavingDelegate.SvgImageSavingDelegate event voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | Wordt aangeroepen voor elke SVG-afbeelding tijdens de Markdown-export. |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

Wordt aangeroepen voor elke SVG-afbeelding tijdens de Markdown-export. Retourneer true om de opgegeven link te gebruiken, of false om de standaard opslaglogica toe te passen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | De SVG-afbeelding die wordt geëxporteerd. |
| link | java.lang.String[] | De Markdown-link die gebruikt moet worden bij het retourneren van true. |

**Retourwaarde:**
boolean