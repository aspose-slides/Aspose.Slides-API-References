---
title: ILoadOptions
second_title: Aspose.Slides para Android vía Java Referencia de API
description: Permite especificar opciones adicionales como el formato o la fuente predeterminada al cargar una presentación.
type: docs
url: /es/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

Permite especificar opciones adicionales (como el formato o la fuente predeterminada) al cargar una presentación.
## Métodos

| Method | Description |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Devuelve o establece el formato de una presentación a cargar. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Devuelve o establece el formato de una presentación a cargar. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Devuelve o establece la fuente Regular utilizada en caso de que no se encuentre la fuente origen. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Devuelve o establece la fuente Regular utilizada en caso de que no se encuentre la fuente origen. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Devuelve o establece la fuente Symbol utilizada en caso de que no se encuentre la fuente origen. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Devuelve o establece la fuente Symbol utilizada en caso de que no se encuentre la fuente origen. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Devuelve o establece la fuente Asian utilizada en caso de que no se encuentre la fuente origen. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Devuelve o establece la fuente Asian utilizada en caso de que no se encuentre la fuente origen. |
| [getPassword()](#getPassword--) | Obtiene o establece la contraseña. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Obtiene o establece la contraseña. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Esta propiedad tiene sentido si el archivo de presentación está protegido con contraseña. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Esta propiedad tiene sentido si el archivo de presentación está protegido con contraseña. |
| [getWarningCallback()](#getWarningCallback--) | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Representa las opciones que pueden usarse para gestionar el comportamiento de manejo de Binary Large Objects (BLOBs), como el uso de archivos temporales o el número máximo de bytes de BLOBs en memoria. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Representa las opciones que pueden usarse para gestionar el comportamiento de manejo de Binary Large Objects (BLOBs), como el uso de archivos temporales o el número máximo de bytes de BLOBs en memoria. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Especifica fuentes externas que se usarán en la presentación. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Especifica fuentes externas que se usarán en la presentación. |
| [getInterruptionToken()](#getInterruptionToken--) | El token para monitorizar solicitudes de interrupción. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | El token para monitorizar solicitudes de interrupción. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Devuelve o establece la interfaz de devolución de llamadas que gestiona la carga de recursos externos. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Devuelve o establece la interfaz de devolución de llamadas que gestiona la carga de recursos externos. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Representa opciones que pueden usarse para especificar un comportamiento adicional de hojas de cálculo. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Representa opciones que pueden usarse para especificar un comportamiento adicional de hojas de cálculo. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Devuelve o establece el idioma predeterminado para el texto de la presentación. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Devuelve o establece el idioma predeterminado para el texto de la presentación. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Determina si Aspose.Slides eliminará todos los objetos binarios incrustados al cargar la presentación. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Determina si Aspose.Slides eliminará todos los objetos binarios incrustados al cargar la presentación. |
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Devuelve o establece el formato de una presentación a cargar. Lectura/escritura [LoadFormat](../../com.aspose.slides/loadformat).

**Devuelve:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```

Devuelve o establece el formato de una presentación a cargar. Lectura/escritura [LoadFormat](../../com.aspose.slides/loadformat).

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

Devuelve o establece la fuente Regular utilizada en caso de que no se encuentre la fuente origen. Lectura-escritura String.

**Devuelve:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

Devuelve o establece la fuente Regular utilizada en caso de que no se encuentre la fuente origen. Lectura-escritura String.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```

Devuelve o establece la fuente Symbol utilizada en caso de que no se encuentre la fuente origen. Lectura-escritura String.

**Devuelve:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```

Devuelve o establece la fuente Symbol utilizada en caso de que no se encuentre la fuente origen. Lectura-escritura String.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```

Devuelve o establece la fuente Asian utilizada en caso de que no se encuentre la fuente origen. Lectura-escritura String.

**Devuelve:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```

Devuelve o establece la fuente Asian utilizada en caso de que no se encuentre la fuente origen. Lectura-escritura String.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Obtiene o establece la contraseña. Lectura-escritura String.

Valor: La contraseña.

**Devuelve:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Obtiene o establece la contraseña. Lectura-escritura String.

Valor: La contraseña.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```

Esta propiedad tiene sentido si el archivo de presentación está protegido con contraseña. Un valor true indica que solo se deben cargar las propiedades del documento desde un archivo de presentación encriptado y se debe ignorar la contraseña. Un valor false indica que toda la presentación encriptada debe cargarse utilizando la contraseña correcta. Si la presentación no está encriptada, el valor de la propiedad siempre se ignora. Si las propiedades del documento de un archivo encriptado no son públicas y el valor de la propiedad es true, las propiedades del documento no se pueden cargar y se lanzará una excepción. Lectura-escritura boolean.

**Devuelve:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```

Esta propiedad tiene sentido si el archivo de presentación está protegido con contraseña. Un valor true indica que solo se deben cargar las propiedades del documento desde un archivo de presentación encriptado y se debe ignorar la contraseña. Un valor false indica que toda la presentación encriptada debe cargarse utilizando la contraseña correcta. Si la presentación no está encriptada, el valor de la propiedad siempre se ignora. Si las propiedades del documento de un archivo encriptado no son públicas y el valor de la propiedad es true, las propiedades del documento no se pueden cargar y se lanzará una excepción. Lectura-escritura boolean.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará. Lectura/escritura [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Devuelve:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará. Lectura/escritura [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |
### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```

Representa las opciones que pueden usarse para gestionar el comportamiento de manejo de Binary Large Objects (BLOBs), como el uso de archivos temporales o el número máximo de bytes de BLOBs en memoria. Estas opciones están destinadas a establecer la mejor relación rendimiento/consumo de memoria para un entorno o requisitos específicos.

--------------------

Un Binary Large Object (BLOB) es un dato binario almacenado como una única entidad; por ejemplo, un BLOB puede ser un audio, un vídeo o la propia presentación.

**Devuelve:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```

Representa las opciones que pueden usarse para gestionar el comportamiento de manejo de Binary Large Objects (BLOBs), como el uso de archivos temporales o el número máximo de bytes de BLOBs en memoria. Estas opciones están destinadas a establecer la mejor relación rendimiento/consumo de memoria para un entorno o requisitos específicos.

--------------------

Un Binary Large Object (BLOB) es un dato binario almacenado como una única entidad; por ejemplo, un BLOB puede ser un audio, un vídeo o la propia presentación.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |
### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```

Especifica fuentes externas que se usarán en la presentación. Estas fuentes están disponibles para la presentación durante todo su ciclo de vida y no se comparten con otras presentaciones.

**Devuelve:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```

Especifica fuentes externas que se usarán en la presentación. Estas fuentes están disponibles para la presentación durante todo su ciclo de vida y no se comparten con otras presentaciones.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |
### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```

El token para monitorizar solicitudes de interrupción.

--------------------

Este token gestiona la vida completa de la instancia [IPresentation](../../com.aspose.slides/ipresentation). Cualquier operación prolongada, como la carga o guardado de una presentación, será interrumpida llamando al método [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) de [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Devuelve:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```

El token para monitorizar solicitudes de interrupción.

--------------------

Este token gestiona la vida completa de la instancia [IPresentation](../../com.aspose.slides/ipresentation). Cualquier operación prolongada, como la carga o guardado de una presentación, será interrumpida llamando al método [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) de [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |
### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public abstract IResourceLoadingCallback getResourceLoadingCallback()
```

Devuelve o establece la interfaz de devolución de llamadas que gestiona la carga de recursos externos. Lectura/escritura [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Devuelve:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public abstract void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Devuelve o establece la interfaz de devolución de llamadas que gestiona la carga de recursos externos. Lectura/escritura [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Parámetros:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
>  // Utilice opciones de carga para definir la cultura de texto predeterminada
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Agregar una nueva forma rectangular con texto
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Verificar el idioma de la primera porción
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
>  // Utilice opciones de carga para definir la cultura de texto predeterminada
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Agregar una nueva forma rectangular con texto
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Verificar el idioma de la primera porción
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public abstract boolean getDeleteEmbeddedBinaryObjects()
```

Determina si Aspose.Slides eliminará todos los objetos binarios incrustados al cargar la presentación.

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

Determina si Aspose.Slides eliminará todos los objetos binarios incrustados al cargar la presentación.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |