---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Android via Java API Reference
description: Representa el controlador de guardado de imágenes SVG de markdown del evento SvgImageSavingDelegate.SvgImageSavingDelegate.
type: docs
url: /es/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

Representa el controlador de guardado de imágenes SVG de markdown del evento \#SvgImageSavingDelegate.SvgImageSavingDelegate.
## Métodos

| Método | Descripción |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | Se invoca para cada imagen SVG durante la exportación a Markdown. |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

Se invoca para cada imagen SVG durante la exportación a Markdown. Devuelve true para usar el enlace especificado, o false para aplicar la lógica de guardado predeterminada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | La imagen SVG que se está exportando. |
| link | java.lang.String[] | El enlace Markdown a usar cuando se devuelve true. |

**Devuelve:**
boolean