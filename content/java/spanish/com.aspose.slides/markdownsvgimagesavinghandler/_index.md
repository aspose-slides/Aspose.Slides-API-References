---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Java API Reference
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
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | Invoked for each SVG image during Markdown export. |

### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

Se invoca para cada imagen SVG durante la exportación a Markdown. Devuelva true para usar el link especificado, o false para aplicar la lógica predeterminada de guardado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | La imagen SVG que se exporta. |
| link | java.lang.String[] | El link Markdown a usar cuando se devuelve true. |

**Retorno:**
boolean