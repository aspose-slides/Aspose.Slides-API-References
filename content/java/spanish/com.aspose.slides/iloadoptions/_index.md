---
title: ILoadOptions
second_title: Aspose.Slides for Java API Reference
description: Permite especificar opciones adicionales, como el formato o la fuente predeterminada, al cargar una presentación.
type: docs
url: /es/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

Permite especificar opciones adicionales (como el formato o la fuente predeterminada) al cargar una presentación.
## Métodos

| Method | Description |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Devuelve o establece el formato de una presentación para cargar. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Devuelve o establece el formato de una presentación para cargar. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Devuelve o establece la fuente Regular utilizada en caso de que no se encuentre la fuente de origen. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Devuelve o establece la fuente Regular utilizada en caso de que no se encuentre la fuente de origen. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Devuelve o establece la fuente Symbol utilizada en caso de que no se encuentre la fuente de origen. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Devuelve o establece la fuente Symbol utilizada en caso de que no se encuentre la fuente de origen. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Devuelve o establece la fuente Asian utilizada en caso de que no se encuentre la fuente de origen. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Devuelve o establece la fuente Asian utilizada en caso de que no se encuentre la fuente de origen. |
| [getPassword()](#getPassword--) | Obtiene o establece la contraseña. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Obtiene o establece la contraseña. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Esta propiedad tiene sentido si el archivo de presentación está protegido con contraseña. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Esta propiedad tiene sentido si el archivo de presentación está protegido con contraseña. |
| [getWarningCallback()](#getWarningCallback--) | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o será abortado. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o será abortado. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Representa las opciones que pueden usarse para gestionar el comportamiento de manejo de objetos binarios grandes (BLOBs), como el uso de archivos temporales o el máximo de bytes de BLOBs en memoria. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Representa las opciones que pueden usarse para gestionar el comportamiento de manejo de objetos binarios grandes (BLOBs), como el uso de archivos temporales o el máximo de bytes de BLOBs en memoria. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Especifica las fuentes externas que se usarán en la presentación. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Especifica las fuentes externas que se usarán en la presentación. |
| [getInterruptionToken()](#getInterruptionToken--) | El token para monitorizar solicitudes de interrupción. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | El token para monitorizar solicitudes de interrupción. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Devuelve o establece la interfaz de devolución de llamada que gestiona la carga de recursos externos. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Devuelve o establece la interfaz de devolución de llamada que gestiona la carga de recursos externos. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Representa opciones que pueden usarse para especificar un comportamiento adicional de hojas de cálculo. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Representa opciones que pueden usarse para especificar un comportamiento adicional de hojas de cálculo. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Devuelve o establece el idioma predeterminado para el texto de la presentación. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Devuelve o establece el idioma predeterminado para el texto de la presentación. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Determina si Aspose.Slides eliminará todos los objetos binarios incrustados durante la carga de la presentación. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Determina si Aspose.Slides eliminará todos los objetos binarios incrustados durante la carga de la presentación. |

### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Devuelve o establece el formato de una presentación para cargar. Lectura/escritura [LoadFormat](../../com.aspose.slides/loadformat).

**Devuelve:**
int

### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```

Devuelve o establece el formato de una presentación para cargar. Lectura/escritura [LoadFormat](../../com.aspose.slides/loadformat).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

Devuelve o establece la fuente Regular utilizada en caso de que no se encuentre la fuente de origen. Lectura/escritura String.

**Devuelve:**
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

Devuelve o establece la fuente Regular utilizada en caso de que no se encuentre la fuente de origen. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```

Devuelve o establece la fuente Symbol utilizada en caso de que no se encuentre la fuente de origen. Lectura/escritura String.

**Devuelve:**
java.lang.String

### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```

Devuelve o establece la fuente Symbol utilizada en caso de que no se encuentre la fuente de origen. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```

Devuelve o establece la fuente Asian utilizada en caso de que no se encuentre la fuente de origen. Lectura/escritura String.

**Devuelve:**
java.lang.String

### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```

Devuelve o establece la fuente Asian utilizada en caso de que no se encuentre la fuente de origen. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Obtiene o establece la contraseña. Lectura/escritura String.

Valor: La contraseña.

**Devuelve:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Obtiene o establece la contraseña. Lectura/escritura String.

Valor: La contraseña.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```

Esta propiedad tiene sentido si el archivo de presentación está protegido con contraseña. Un valor de true significa que solo se deben cargar las propiedades del documento de un archivo de presentación cifrado y la contraseña se debe ignorar. Un valor de false significa que se debe cargar toda la presentación cifrada usando la contraseña correcta. Si la presentación no está cifrada, el valor de la propiedad siempre se ignora. Si las propiedades del documento de un archivo cifrado no son públicas y el valor de la propiedad es true, entonces no se pueden cargar las propiedades del documento y se lanzará una excepción. Lectura/escritura boolean.

**Devuelve:**
boolean

### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```

Esta propiedad tiene sentido si el archivo de presentación está protegido con contraseña. Un valor de true significa que solo se deben cargar las propiedades del documento de un archivo de presentación cifrado y la contraseña se debe ignorar. Un valor de false significa que se debe cargar toda la presentación cifrada usando la contraseña correcta. Si la presentación no está cifrada, el valor de la propiedad siempre se ignora. Si las propiedades del documento de un archivo cifrado no son públicas y el valor de la propiedad es true, entonces no se pueden cargar las propiedades del documento y se lanzará una excepción. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o será abortado. Lectura/escritura [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Devuelve:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o será abortado. Lectura/escritura [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```

Representa las opciones que pueden usarse para gestionar el comportamiento de manejo de objetos binarios grandes (BLOBs), como el uso de archivos temporales o el máximo de bytes de BLOBs en memoria. Estas opciones están destinadas a establecer la mejor relación rendimiento/consumo de memoria para un entorno o requisitos particulares.

--------------------

Un objeto binario grande (BLOB) es un dato binario almacenado como una única entidad; es decir, un BLOB puede ser un audio, video o la propia presentación.

**Devuelve:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)

### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```

Representa las opciones que pueden usarse para gestionar el comportamiento de manejo de objetos binarios grandes (BLOBs), como el uso de archivos temporales o el máximo de bytes de BLOBs en memoria. Estas opciones están destinadas a establecer la mejor relación rendimiento/consumo de memoria para un entorno o requisitos particulares.

--------------------

Un objeto binario grande (BLOB) es un dato binario almacenado como una única entidad; es decir, un BLOB puede ser un audio, video o la propia presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```

Especifica las fuentes externas que se usarán en la presentación. Estas fuentes están disponibles para la presentación durante toda su vida útil y no se comparten con otras presentaciones.

**Devuelve:**
[IFontSources](../../com.aspose.slides/ifontsources)

### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```

Especifica las fuentes externas que se usarán en la presentación. Estas fuentes están disponibles para la presentación durante toda su vida útil y no se comparten con otras presentaciones.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```

El token para monitorizar solicitudes de interrupción.

--------------------

Este token gestiona toda la vida útil de la instancia [IPresentation](../../com.aspose.slides/ipresentation). Cualquier operación de larga duración, como la carga o guardado de una presentación, se interrumpirá llamando al método [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) de [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Devuelve:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)

### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```

El token para monitorizar solicitudes de interrupción.

--------------------

Este token gestiona toda la vida útil de la instancia [IPresentation](../../com.aspose.slides/ipresentation). Cualquier operación de larga duración, como la carga o guardado de una presentación, se interrumpirá llamando al método [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) de [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public abstract IResourceLoadingCallback getResourceLoadingCallback()
```

Devuelve o establece la interfaz de devolución de llamada que gestiona la carga de recursos externos. Lectura/escritura [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Devuelve:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)

### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public abstract void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Devuelve o establece la interfaz de devolución de llamada que gestiona la carga de recursos externos. Lectura/escritura [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public abstract ISpreadsheetOptions getSpreadsheetOptions()
```

Representa opciones que pueden usarse para especificar un comportamiento adicional de hojas de cálculo.

**Devuelve:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)

### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Representa opciones que pueden usarse para especificar un comportamiento adicional de hojas de cálculo.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public abstract String getDefaultTextLanguage()
```

Devuelve o establece el idioma predeterminado para el texto de la presentación. Lectura/escritura String.

--------------------

> ```
> Example:
>   
>  // Use load options to define the default text culture
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Add new rectangle shape with text
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Check the first portion language
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
java.lang.String

### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public abstract void setDefaultTextLanguage(String value)
```

Devuelve o establece el idioma predeterminado para el texto de la presentación. Lectura/escritura String.

--------------------

> ```
> Example:
>   
>  // Usa opciones de carga para definir la cultura de texto predeterminada
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Añade una nueva forma rectangular con texto
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Comprueba el idioma de la primera porción
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public abstract boolean getDeleteEmbeddedBinaryObjects()
```

Determina si Aspose.Slides eliminará todos los objetos binarios incrustados durante la carga de la presentación.

Los tipos de los objetos binarios incrustados:

 *  
 *  
 *  

Lectura/escritura boolean.

--------------------

> ```
> El siguiente ejemplo muestra cómo cargar la presentación sin ningún objeto binario incrustado.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

El valor predeterminado es **false**.

**Devuelve:**
boolean

### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public abstract void setDeleteEmbeddedBinaryObjects(boolean value)
```

Determina si Aspose.Slides eliminará todos los objetos binarios incrustados durante la carga de la presentación.

Los tipos de los objetos binarios incrustados:

 *  
 *  
 *  

Lectura/escritura boolean.

--------------------

> ```
> El siguiente ejemplo muestra cómo cargar la presentación sin ningún objeto binario incrustado.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

El valor predeterminado es **false**.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |