---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Android via Java API Reference
description: Reprezentuje handler ukládání SVG obrázků v markdownu události #SvgImageSavingDelegate.SvgImageSavingDelegate.
type: docs
url: /cs/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

Reprezentuje handler ukládání SVG obrázků v markdownu události #SvgImageSavingDelegate.SvgImageSavingDelegate.

## Metody

| Metoda | Popis |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | Vyvoláno pro každý SVG obrázek během exportu do Markdownu. |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

Vyvoláno pro každý SVG obrázek během exportu do Markdownu. Vrátí true, pokud se má použít zadaný odkaz, nebo false pro použití výchozí logiky ukládání.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | SVG obrázek, který se exportuje. |
| link | java.lang.String[] | Markdown odkaz, který se použije při vrácení true. |

**Návratová hodnota:**
boolean