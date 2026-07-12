---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Android via Java API Reference
description: Representa el controlador de guardado de imágenes markdown del evento ImageSavingDelegate.ImageSavingDelegate.
type: docs
url: /es/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

Representa el controlador de guardado de imágenes markdown del \#ImageSavingDelegate.ImageSavingDelegate evento.
## Métodos

| Método | Descripción |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Invocado para cada imagen que no sea SVG (bitmap o metafile) durante la exportación a Markdown. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Invocado para cada imagen que no sea SVG (bitmap o metafile) durante la exportación a Markdown. Devuelve true para usar el enlace especificado, o false para aplicar la lógica de guardado predeterminada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | La imagen que se está exportando (bitmap o metafile). |
| format | int | El formato de la imagen. |
| link | java.lang.String[] | El enlace Markdown a usar cuando se devuelve true. |

**Devuelve:**
boolean