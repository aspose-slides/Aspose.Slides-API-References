---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Opciones para extraer HTML del texto del Pptx.
type: docs
url: /es/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

Opciones para extraer HTML del texto del Pptx.
## Métodos

| Método | Descripción |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Devuelve o establece el valor, indicando si se deben agregar encabezados del portapapeles. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Devuelve o establece el valor, indicando si se deben agregar encabezados del portapapeles. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Devuelve o establece la profundidad heredada para propiedades de texto. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Devuelve o establece la profundidad heredada para propiedades de texto. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Devuelve o establece un objeto de devolución de llamada que controla cómo se almacenará el objeto externo. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Devuelve o establece un objeto de devolución de llamada que controla cómo se almacenará el objeto externo. |
| [getEncodingName()](#getEncodingName--) | Devuelve o establece el nombre de codificación html. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Devuelve o establece el nombre de codificación html. |
### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```

Devuelve o establece el valor, indicando si se deben agregar encabezados del portapapeles. Boolean de lectura/escritura.

**Devuelve:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```

Devuelve o establece el valor, indicando si se deben agregar encabezados del portapapeles. Boolean de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```

Devuelve o establece la profundidad heredada para propiedades de texto. Lectura/escritura [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Devuelve:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```

Devuelve o establece la profundidad heredada para propiedades de texto. Lectura/escritura [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```

Devuelve o establece un objeto de devolución de llamada que controla cómo se almacenará el objeto externo. Lectura/escritura [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Devuelve:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```

Devuelve o establece un objeto de devolución de llamada que controla cómo se almacenará el objeto externo. Lectura/escritura [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```

Devuelve o establece el nombre de codificación html. Este valor se guardará en el archivo HTML generado, pero depende del llamador asegurar que el archivo se guarde con esta codificación. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```

Devuelve o establece el nombre de codificación html. Este valor se guardará en el archivo HTML generado, pero depende del llamador asegurar que el archivo se guarde con esta codificación. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |