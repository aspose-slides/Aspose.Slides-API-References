---
title: SwfOptions
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Proporciona opciones que controlan cómo se guarda una presentación en formato Swf.
type: docs
url: /es/com.aspose.slides/swfoptions/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Todas las interfaces implementadas:**
[com.aspose.slides.ISwfOptions](../../com.aspose.slides/iswfoptions)
```
public class SwfOptions extends SaveOptions implements ISwfOptions
```

Proporciona opciones que controlan cómo se guarda una presentación en formato Swf.

--------------------

> ```
> The following example shows how to convert PowerPoint to SWF Flash.
>  
>  // Instanciar un objeto Presentation que representa un archivo de presentación
>  Presentation pres = new Presentation("HelloWorld.pptx");
>  try {
>      SwfOptions swfOptions = new SwfOptions();
>      swfOptions.setViewerIncluded(false);
>      INotesCommentsLayoutingOptions notesOptions = swfOptions.getNotesCommentsLayouting();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      // Guardando la presentación y las páginas de notas
>      pres.save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
>      swfOptions.setViewerIncluded(true);
>      pres.save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SwfOptions()](#SwfOptions--) | Constructor predeterminado. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Especifica si el documento generado debe incluir diapositivas ocultas o no. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Especifica si el documento generado debe incluir diapositivas ocultas o no. |
| [getCompressed()](#getCompressed--) | Especifica si el documento SWF generado debe estar comprimido o no. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Especifica si el documento SWF generado debe estar comprimido o no. |
| [getViewerIncluded()](#getViewerIncluded--) | Especifica si el documento SWF generado debe incluir el visor de documentos integrado o no. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Especifica si el documento SWF generado debe incluir el visor de documentos integrado o no. |
| [getShowPageBorder()](#getShowPageBorder--) | Especifica si se debe mostrar el borde alrededor de las páginas. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Especifica si se debe mostrar el borde alrededor de las páginas. |
| [getShowFullScreen()](#getShowFullScreen--) | Mostrar/ocultar el botón de pantalla completa. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Mostrar/ocultar el botón de pantalla completa. |
| [getShowPageStepper()](#getShowPageStepper--) | Mostrar/ocultar el selector de página. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Mostrar/ocultar el selector de página. |
| [getShowSearch()](#getShowSearch--) | Mostrar/ocultar la sección de búsqueda. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Mostrar/ocultar la sección de búsqueda. |
| [getShowTopPane()](#getShowTopPane--) | Mostrar/ocultar todo el panel superior. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Mostrar/ocultar todo el panel superior. |
| [getShowBottomPane()](#getShowBottomPane--) | Mostrar/ocultar el panel inferior. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Mostrar/ocultar el panel inferior. |
| [getShowLeftPane()](#getShowLeftPane--) | Mostrar/ocultar el panel izquierdo. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Mostrar/ocultar el panel izquierdo. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Iniciar con el panel izquierdo abierto. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Iniciar con el panel izquierdo abierto. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Habilitar/deshabilitar el menú contextual. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Habilitar/deshabilitar el menú contextual. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Imagen que se mostrará como logotipo en la esquina superior derecha del visor. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Imagen que se mostrará como logotipo en la esquina superior derecha del visor. |
| [getLogoLink()](#getLogoLink--) | Obtiene o establece la dirección URL completa para un logotipo. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Obtiene o establece la dirección URL completa para un logotipo. |
| [getJpegQuality()](#getJpegQuality--) | Especifica la calidad de las imágenes JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Especifica la calidad de las imágenes JPEG. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### SwfOptions() {#SwfOptions--}
```
public SwfOptions()
```


Constructor predeterminado.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es false.

**Devuelve:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es false.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}
```
public final boolean getCompressed()
```


Especifica si el documento SWF generado debe estar comprimido o no. El valor predeterminado es true.

**Devuelve:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public final void setCompressed(boolean value)
```


Especifica si el documento SWF generado debe estar comprimido o no. El valor predeterminado es true.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public final boolean getViewerIncluded()
```


Especifica si el documento SWF generado debe incluir el visor de documentos integrado o no. El valor predeterminado es true.

**Devuelve:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public final void setViewerIncluded(boolean value)
```


Especifica si el documento SWF generado debe incluir el visor de documentos integrado o no. El valor predeterminado es true.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public final boolean getShowPageBorder()
```


Especifica si se debe mostrar el borde alrededor de las páginas. El valor predeterminado es true.

**Devuelve:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public final void setShowPageBorder(boolean value)
```


Especifica si se debe mostrar el borde alrededor de las páginas. El valor predeterminado es true.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public final boolean getShowFullScreen()
```


Mostrar/ocultar el botón de pantalla completa. Puede sobrescribirse en flashvars. El valor predeterminado es true.

**Devuelve:**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public final void setShowFullScreen(boolean value)
```


Mostrar/ocultar el botón de pantalla completa. Puede sobrescribirse en flashvars. El valor predeterminado es true.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public final boolean getShowPageStepper()
```


Mostrar/ocultar el selector de página. Puede sobrescribirse en flashvars. El valor predeterminado es true.

**Devuelve:**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public final void setShowPageStepper(boolean value)
```


Mostrar/ocultar el selector de página. Puede sobrescribirse en flashvars. El valor predeterminado es true.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public final boolean getShowSearch()
```


Mostrar/ocultar la sección de búsqueda. Puede sobrescribirse en flashvars. El valor predeterminado es true.

**Devuelve:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public final void setShowSearch(boolean value)
```


Mostrar/ocultar la sección de búsqueda. Puede sobrescribirse en flashvars. El valor predeterminado es true.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public final boolean getShowTopPane()
```


Mostrar/ocultar todo el panel superior. Puede sobrescribirse en flashvars. El valor predeterminado es true.

**Devuelve:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public final void setShowTopPane(boolean value)
```


Mostrar/ocultar todo el panel superior. Puede sobrescribirse en flashvars. El valor predeterminado es true.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public final boolean getShowBottomPane()
```


Mostrar/ocultar el panel inferior. Puede sobrescribirse en flashvars. El valor predeterminado es true.

**Devuelve:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public final void setShowBottomPane(boolean value)
```


Mostrar/ocultar el panel inferior. Puede sobrescribirse en flashvars. El valor predeterminado es true.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public final boolean getShowLeftPane()
```


Mostrar/ocultar el panel izquierdo. Puede sobrescribirse en flashvars. El valor predeterminado es true.

**Devuelve:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public final void setShowLeftPane(boolean value)
```


Mostrar/ocultar el panel izquierdo. Puede sobrescribirse en flashvars. El valor predeterminado es true.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public final boolean getStartOpenLeftPane()
```


Iniciar con el panel izquierdo abierto. Puede sobrescribirse en flashvars. El valor predeterminado es false.

**Devuelve:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public final void setStartOpenLeftPane(boolean value)
```


Iniciar con el panel izquierdo abierto. Puede sobrescribirse en flashvars. El valor predeterminado es false.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public final boolean getEnableContextMenu()
```


Habilitar/deshabilitar el menú contextual. El valor predeterminado es true.

**Devuelve:**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public final void setEnableContextMenu(boolean value)
```


Habilitar/deshabilitar el menú contextual. El valor predeterminado es true.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public final byte[] getLogoImageBytes()
```


Imagen que se mostrará como logotipo en la esquina superior derecha del visor. La imagen debe ser PNG de 32 × 64 píxeles; de lo contrario, el logotipo puede mostrarse incorrectamente.

**Devuelve:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final void setLogoImageBytes(byte[] value)
```


Imagen que se mostrará como logotipo en la esquina superior derecha del visor. La imagen debe ser PNG de 32 × 64 píxeles; de lo contrario, el logotipo puede mostrarse incorrectamente.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public final String getLogoLink()
```


Obtiene o establece la dirección URL completa para un logotipo. Tiene efecto solo si se especifica (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])).

**Devuelve:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public final void setLogoLink(String value)
```


Obtiene o establece la dirección URL completa para un logotipo. Tiene efecto solo si se especifica (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```


Especifica la calidad de las imágenes JPEG. El valor predeterminado es 95.

**Devuelve:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```


Especifica la calidad de las imágenes JPEG. El valor predeterminado es 95.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Esta propiedad no admite asignar objetos del tipo [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Esta propiedad no admite asignar objetos del tipo [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |