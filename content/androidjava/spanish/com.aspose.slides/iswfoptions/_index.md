---
title: ISwfOptions
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Proporciona opciones que controlan cómo se guarda una presentación en formato SWF.
type: docs
url: /es/com.aspose.slides/iswfoptions/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISwfOptions extends ISaveOptions
```

Proporciona opciones que controlan cómo se guarda una presentación en formato SWF.
## Métodos

| Method | Description |
| --- | --- |
| [getCompressed()](#getCompressed--) | Especifica si el documento SWF generado debe comprimirse o no. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Especifica si el documento SWF generado debe comprimirse o no. |
| [getViewerIncluded()](#getViewerIncluded--) | Especifica si el documento SWF generado debe incluir el visor de documentos integrado o no. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Especifica si el documento SWF generado debe incluir el visor de documentos integrado o no. |
| [getShowPageBorder()](#getShowPageBorder--) | Especifica si se debe mostrar el borde alrededor de las páginas. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Especifica si se debe mostrar el borde alrededor de las páginas. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Especifica si el documento generado debe incluir diapositivas ocultas o no. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Especifica si el documento generado debe incluir diapositivas ocultas o no. |
| [getShowFullScreen()](#getShowFullScreen--) | Mostrar/ocultar botón de pantalla completa. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Mostrar/ocultar botón de pantalla completa. |
| [getShowPageStepper()](#getShowPageStepper--) | Mostrar/ocultar control de página. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Mostrar/ocultar control de página. |
| [getShowSearch()](#getShowSearch--) | Mostrar/ocultar sección de búsqueda. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Mostrar/ocultar sección de búsqueda. |
| [getShowTopPane()](#getShowTopPane--) | Mostrar/ocultar todo el panel superior. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Mostrar/ocultar todo el panel superior. |
| [getShowBottomPane()](#getShowBottomPane--) | Mostrar/ocultar panel inferior. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Mostrar/ocultar panel inferior. |
| [getShowLeftPane()](#getShowLeftPane--) | Mostrar/ocultar panel izquierdo. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Mostrar/ocultar panel izquierdo. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Iniciar con el panel izquierdo abierto. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Iniciar con el panel izquierdo abierto. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Activar/desactivar menú contextual. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Activar/desactivar menú contextual. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Imagen que se mostrará como logotipo en la esquina superior derecha del visor. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Imagen que se mostrará como logotipo en la esquina superior derecha del visor. |
| [getLogoLink()](#getLogoLink--) | Obtiene o establece la dirección completa del hipervínculo para un logotipo. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Obtiene o establece la dirección completa del hipervínculo para un logotipo. |
| [getJpegQuality()](#getJpegQuality--) | Especifica la calidad de las imágenes JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Especifica la calidad de las imágenes JPEG. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |

### getCompressed() {#getCompressed--}
```
public abstract boolean getCompressed()
```

Especifica si el documento SWF generado debe comprimirse o no. El valor predeterminado es true.

**Devuelve:**
boolean

### setCompressed(boolean value) {#setCompressed-boolean-}
```
public abstract void setCompressed(boolean value)
```

Especifica si el documento SWF generado debe comprimirse o no. El valor predeterminado es true.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public abstract boolean getViewerIncluded()
```

Especifica si el documento SWF generado debe incluir el visor de documentos integrado o no. El valor predeterminado es true.

**Devuelve:**
boolean

### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public abstract void setViewerIncluded(boolean value)
```

Especifica si el documento SWF generado debe incluir el visor de documentos integrado o no. El valor predeterminado es true.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public abstract boolean getShowPageBorder()
```

Especifica si se debe mostrar el borde alrededor de las páginas. El valor predeterminado es true.

**Devuelve:**
boolean

### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public abstract void setShowPageBorder(boolean value)
```

Especifica si se debe mostrar el borde alrededor de las páginas. El valor predeterminado es true.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es false.

**Devuelve:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es false.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public abstract boolean getShowFullScreen()
```

Mostrar/ocultar botón de pantalla completa. Puede sobrescribirse mediante flashvars. El valor predeterminado es true.

**Devuelve:**
boolean

### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public abstract void setShowFullScreen(boolean value)
```

Mostrar/ocultar botón de pantalla completa. Puede sobrescribirse mediante flashvars. El valor predeterminado es true.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public abstract boolean getShowPageStepper()
```

Mostrar/ocultar control de página. Puede sobrescribirse mediante flashvars. El valor predeterminado es true.

**Devuelve:**
boolean

### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public abstract void setShowPageStepper(boolean value)
```

Mostrar/ocultar control de página. Puede sobrescribirse mediante flashvars. El valor predeterminado es true.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public abstract boolean getShowSearch()
```

Mostrar/ocultar sección de búsqueda. Puede sobrescribirse mediante flashvars. El valor predeterminado es true.

**Devuelve:**
boolean

### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public abstract void setShowSearch(boolean value)
```

Mostrar/ocultar sección de búsqueda. Puede sobrescribirse mediante flashvars. El valor predeterminado es true.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public abstract boolean getShowTopPane()
```

Mostrar/ocultar todo el panel superior. Puede sobrescribirse mediante flashvars. El valor predeterminado es true.

**Devuelve:**
boolean

### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public abstract void setShowTopPane(boolean value)
```

Mostrar/ocultar todo el panel superior. Puede sobrescribirse mediante flashvars. El valor predeterminado es true.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public abstract boolean getShowBottomPane()
```

Mostrar/ocultar panel inferior. Puede sobrescribirse mediante flashvars. El valor predeterminado es true.

**Devuelve:**
boolean

### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public abstract void setShowBottomPane(boolean value)
```

Mostrar/ocultar panel inferior. Puede sobrescribirse mediante flashvars. El valor predeterminado es true.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public abstract boolean getShowLeftPane()
```

Mostrar/ocultar panel izquierdo. Puede sobrescribirse mediante flashvars. El valor predeterminado es true.

**Devuelve:**
boolean

### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public abstract void setShowLeftPane(boolean value)
```

Mostrar/ocultar panel izquierdo. Puede sobrescribirse mediante flashvars. El valor predeterminado es true.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public abstract boolean getStartOpenLeftPane()
```

Iniciar con el panel izquierdo abierto. Puede sobrescribirse mediante flashvars. El valor predeterminado es false.

**Devuelve:**
boolean

### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public abstract void setStartOpenLeftPane(boolean value)
```

Iniciar con el panel izquierdo abierto. Puede sobrescribirse mediante flashvars. El valor predeterminado es false.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public abstract boolean getEnableContextMenu()
```

Activar/desactivar menú contextual. El valor predeterminado es true.

**Devuelve:**
boolean

### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public abstract void setEnableContextMenu(boolean value)
```

Activar/desactivar menú contextual. El valor predeterminado es true.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public abstract byte[] getLogoImageBytes()
```

Imagen que se mostrará como logotipo en la esquina superior derecha del visor. La imagen debe ser PNG de 32 × 64 píxeles; de lo contrario, el logotipo puede mostrarse incorrectamente.

**Devuelve:**
byte[]

### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public abstract void setLogoImageBytes(byte[] value)
```

Imagen que se mostrará como logotipo en la esquina superior derecha del visor. La imagen debe ser PNG de 32 × 64 píxeles; de lo contrario, el logotipo puede mostrarse incorrectamente.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public abstract String getLogoLink()
```

Obtiene o establece la dirección completa del hipervínculo para un logotipo. Solo tiene efecto si se especifica un (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])).

**Devuelve:**
java.lang.String

### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public abstract void setLogoLink(String value)
```

Obtiene o establece la dirección completa del hipervínculo para un logotipo. Solo tiene efecto si se especifica un (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])).

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

Especifica la calidad de las imágenes JPEG. El valor predeterminado es 95.

**Devuelve:**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

Especifica la calidad de las imágenes JPEG. El valor predeterminado es 95.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Esta propiedad no admite asignar objetos del tipo [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

--------------------

> ```
> Ejemplo:
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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Esta propiedad no admite asignar objetos del tipo [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

--------------------

> ```
> Ejemplo:
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |