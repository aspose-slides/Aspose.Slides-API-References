---
title: MarkdownSaveOptions
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa opciones que controlan cómo se debe guardar la presentación en markdown.
type: docs
url: /es/com.aspose.slides/markdownsaveoptions/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

Representa opciones que controlan cómo se debe guardar la presentación en markdown.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation(presentationFileName);
>  try {
>      FileOutputStream stream = new FileOutputStream("MdFileForGitHubFlavor");
>      try {
>          MarkdownSaveOptions markdownSaveOptions = new MarkdownSaveOptions();
>          markdownSaveOptions.setShowHiddenSlides(true);
>          markdownSaveOptions.setShowSlideNumber(true);
>          markdownSaveOptions.setFlavor(Flavor.Github);
>          markdownSaveOptions.setExportType(MarkdownExportType.Sequential);
>          markdownSaveOptions.setNewLineType(NewLineType.Windows);
>          markdownSaveOptions.setBasePath(documentResourcesPath);
> 
>          pres.save(stream, new int[]{1, 2, 3, 4, 5, 6, 7, 8, 9}, SaveFormat.Md, markdownSaveOptions);
>      } finally {
>          if (stream != null) stream.close();
>      }
>  } catch (Exception e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Constructores

| Constructor | Descripción |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) | Ctor. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getExportType()](#getExportType--) | Especifica la especificación markdown para convertir la presentación. |
| [setExportType(int value)](#setExportType-int-) | Especifica la especificación markdown para convertir la presentación. |
| [getBasePath()](#getBasePath--) | Especifica la ruta base donde se guardará el documento con recursos. |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | Especifica la ruta base donde se guardará el documento con recursos. |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | Especifica el nombre de la carpeta donde se guardarán las imágenes. |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | Especifica el nombre de la carpeta donde se guardarán las imágenes. |
| [getNewLineType()](#getNewLineType--) | Especifica si el documento generado debe tener saltos de línea \\r(Macintosh) \\n(Unix) o \\r\\n(Windows). |
| [setNewLineType(int value)](#setNewLineType-int-) | Especifica si el documento generado debe tener saltos de línea \\r(Macintosh) \\n(Unix) o \\r\\n(Windows). |
| [getShowComments()](#getShowComments--) | Especifica si el documento generado debe mostrar comentarios o no. |
| [setShowComments(boolean value)](#setShowComments-boolean-) | Especifica si el documento generado debe mostrar comentarios o no. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Especifica si el documento generado debe incluir diapositivas ocultas o no. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Especifica si el documento generado debe incluir diapositivas ocultas o no. |
| [getShowSlideNumber()](#getShowSlideNumber--) | Especifica si el documento generado debe mostrar el número de cada diapositiva o no. |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | Especifica si el documento generado debe mostrar el número de cada diapositiva o no. |
| [getFlavor()](#getFlavor--) | Especifica la especificación markdown para convertir la presentación. |
| [setFlavor(int value)](#setFlavor-int-) | Especifica la especificación markdown para convertir la presentación. |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | Obtiene o establece la cadena de formato utilizada para los encabezados de número de diapositiva en la salida Markdown. |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | Obtiene o establece la cadena de formato utilizada para los encabezados de número de diapositiva en la salida Markdown. |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | Especifica cómo deben manejarse los caracteres de espacio regular repetidos durante la exportación a Markdown. |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | Especifica cómo deben manejarse los caracteres de espacio regular repetidos durante la exportación a Markdown. |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | Si se establece en true, elimina líneas vacías o que contengan solo espacios en blanco de la salida Markdown final. |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | Si se establece en true, elimina líneas vacías o que contengan solo espacios en blanco de la salida Markdown final. |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | Se produce para cada imagen que no sea SVG (bitmap o metafile) durante la exportación a Markdown. Permite personalizar cómo se guarda y referencia la imagen. Si no se maneja, la imagen se guarda localmente con un enlace relativo. |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | Se produce para cada imagen SVG durante la exportación a Markdown. Permite sobrescribir el guardado y la generación de enlaces predeterminados. Si no se maneja, el SVG se guarda localmente con un enlace relativo. |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```


Ctor.

### getExportType() {#getExportType--}
```
public final int getExportType()
```


Especifica la especificación markdown para convertir la presentación. Predeterminado es TextOnly.

**Devuelve:**
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```


Especifica la especificación markdown para convertir la presentación. Predeterminado es TextOnly.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```


Especifica la ruta base donde se guardará el documento con recursos. Predeterminado es el directorio actual de la aplicación.

**Devuelve:**
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```


Especifica la ruta base donde se guardará el documento con recursos. Predeterminado es el directorio actual de la aplicación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```


Especifica el nombre de la carpeta donde se guardarán las imágenes. Predeterminado es Images.

**Devuelve:**
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```


Especifica el nombre de la carpeta donde se guardarán las imágenes. Predeterminado es Images.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```


Especifica si el documento generado debe tener saltos de línea \\r(Macintosh) \\n(Unix) o \\r\\n(Windows). Predeterminado es Unix.

**Devuelve:**
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```


Especifica si el documento generado debe tener saltos de línea \\r(Macintosh) \\n(Unix) o \\r\\n(Windows). Predeterminado es Unix.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```


Especifica si el documento generado debe mostrar comentarios o no. Predeterminado es false.

**Devuelve:**
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```


Especifica si el documento generado debe mostrar comentarios o no. Predeterminado es false.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Especifica si el documento generado debe incluir diapositivas ocultas o no. Predeterminado es false.

**Devuelve:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Especifica si el documento generado debe incluir diapositivas ocultas o no. Predeterminado es false.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```


Especifica si el documento generado debe mostrar el número de cada diapositiva o no. Predeterminado es false.

**Devuelve:**
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```


Especifica si el documento generado debe mostrar el número de cada diapositiva o no. Predeterminado es false.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```


Especifica la especificación markdown para convertir la presentación. Predeterminado es Multi-markdown.

**Devuelve:**
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```


Especifica la especificación markdown para convertir la presentación. Predeterminado es Multi-markdown.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```


Obtiene o establece la cadena de formato utilizada para los encabezados de número de diapositiva en la salida Markdown. El formato debe incluir el "\{0\}" como marcador de posición, que será reemplazado por el índice de la diapositiva durante la exportación. Ejemplo: "\# Slide \{0\}" producirá "\# Slide 1", "\# Slide 2", etc.

**Devuelve:**
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```


Obtiene o establece la cadena de formato utilizada para los encabezados de número de diapositiva en la salida Markdown. El formato debe incluir el "\{0\}" como marcador de posición, que será reemplazado por el índice de la diapositiva durante la exportación. Ejemplo: "\# Slide \{0\}" producirá "\# Slide 1", "\# Slide 2", etc.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```


Especifica cómo deben manejarse los caracteres de espacio regular repetidos durante la exportación a Markdown. Esta propiedad define si los espacios consecutivos son: - preservados como caracteres de espacio regular, - alternados entre espacios regulares y entidades de espacio de no separación (�), - o totalmente reemplazados (después del primero) por un espacio de no separación para preservar la alineación visual en la salida Markdown. El valor predeterminado es [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Devuelve:**
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```


Especifica cómo deben manejarse los caracteres de espacio regular repetidos durante la exportación a Markdown. Esta propiedad define si los espacios consecutivos son: - preservados como caracteres de espacio regular, - alternados entre espacios regulares y entidades de espacio de no separación (�), - o totalmente reemplazados (después del primero) por un espacio de no separación para preservar la alineación visual en la salida Markdown. El valor predeterminado es [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```


Si se establece en true, elimina líneas vacías o que contengan solo espacios en blanco de la salida Markdown final. Predeterminado es false.

**Devuelve:**
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```


Si se establece en true, elimina líneas vacías o que contengan solo espacios en blanco de la salida Markdown final. Predeterminado es false.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event) {#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-}
```
public final void setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)
```


Se produce para cada imagen que no sea SVG (bitmap o metafile) durante la exportación a Markdown. Permite personalizar cómo se guarda y referencia la imagen. Si no se maneja, la imagen se guarda localmente con un enlace relativo.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | Evento de guardado de imagen Markdown. |

### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```


Se produce para cada imagen SVG durante la exportación a Markdown. Permite sobrescribir el guardado y la generación de enlaces predeterminados. Si no se maneja, el SVG se guarda localmente con un enlace relativo.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | Evento de guardado de imagen SVG Markdown. |