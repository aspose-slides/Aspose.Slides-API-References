---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Android via Java API Reference
description: Stelt de markdown SVG-afbeeldingsopslaghandler van SvgImageSavingDelegate.SvgImageSavingDelegate gebeurtenis voor.
type: docs
url: /nl/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

Stelt de markdown SVG-afbeeldingsopslaghandler van \#SvgImageSavingDelegate.SvgImageSavingDelegate gebeurtenis voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | Aangeroepen voor elke SVG-afbeelding tijdens de Markdown-export. |

### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

Aangeroepen voor elke SVG-afbeelding tijdens de Markdown-export. Retourneer true om de opgegeven link te gebruiken, of false om de standaardopslaglogica toe te passen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | De SVG-afbeelding die wordt geëxporteerd. |
| link | java.lang.String[] | De Markdown-link die moet worden gebruikt bij het retourneren van true. |

**Retour:**
boolean