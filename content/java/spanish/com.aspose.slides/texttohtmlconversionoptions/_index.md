---
title: TextToHtmlConversionOptions
second_title: Referencia de API de Aspose.Slides para Java
description: Opciones para extraer HTML del texto Pptx.
type: docs
url: /es/com.aspose.slides/texttohtmlconversionoptions/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions)
```
public final class TextToHtmlConversionOptions implements ITextToHtmlConversionOptions
```

Opciones para extraer HTML del texto Pptx.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextToHtmlConversionOptions()](#TextToHtmlConversionOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Devuelve o establece el valor, que indica si se deben agregar encabezados del portapapeles. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Devuelve o establece el valor, que indica si se deben agregar encabezados del portapapeles. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Devuelve o establece la profundidad de herencia para las propiedades de texto. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Devuelve o establece la profundidad de herencia para las propiedades de texto. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Devuelve o establece un objeto de devolución de llamada que controla cómo se almacenará el objeto externo. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Devuelve o establece un objeto de devolución de llamada que controla cómo se almacenará el objeto externo. |
| [getEncodingName()](#getEncodingName--) | Devuelve o establece el nombre de codificación HTML. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Devuelve o establece el nombre de codificación HTML. |
### TextToHtmlConversionOptions() {#TextToHtmlConversionOptions--}
```
public TextToHtmlConversionOptions()
```


### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public final boolean getAddClipboardFragmentHeader()
```


Devuelve o establece el valor, que indica si se deben agregar encabezados del portapapeles. Lectura/escritura booleano.

**Devuelve:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public final void setAddClipboardFragmentHeader(boolean value)
```


Devuelve o establece el valor, que indica si se deben agregar encabezados del portapapeles. Lectura/escritura booleano.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public final int getTextInheritanceLimit()
```


Devuelve o establece la profundidad de herencia para las propiedades de texto. Lectura/escritura [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Devuelve:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```


Devuelve o establece la profundidad de herencia para las propiedades de texto. Lectura/escritura [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```


Devuelve o establece un objeto de devolución de llamada que controla cómo se almacenará el objeto externo. Lectura/escritura [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Devuelve:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```


Devuelve o establece un objeto de devolución de llamada que controla cómo se almacenará el objeto externo. Lectura/escritura [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```


Devuelve o establece el nombre de codificación HTML. Este valor se guardará en el archivo HTML generado, pero depende del llamador asegurar que el archivo se guarde con esta codificación. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```


Devuelve o establece el nombre de codificación HTML. Este valor se guardará en el archivo HTML generado, pero depende del llamador asegurar que el archivo se guarde con esta codificación. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |