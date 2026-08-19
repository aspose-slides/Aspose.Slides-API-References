---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Java API Reference
description: Representuje handler pro ukládání SVG obrázků ve formátu markdown události \#SvgImageSavingDelegate.SvgImageSavingDelegate.
type: docs
url: /cs/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---
```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

Representuje handler pro ukládání SVG obrázků ve formátu markdown události \#SvgImageSavingDelegate.SvgImageSavingDelegate.
## Metody

| Metoda | Popis |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | Invoked for each SVG image during Markdown export. |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

Vyvoláno pro každý SVG obrázek během exportu do Markdownu. Vrátí true pro použití určeného odkazu, nebo false pro použití výchozí logiky ukládání.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | SVG obrázek, který se exportuje. |
| link | java.lang.String[] | Markdown odkaz, který se použije při vrácení true. |

**Návratová hodnota:**
boolean