---
title: LoadOptions
second_title: Referencia de la API de Aspose.Slides para Java
description: Permite especificar opciones adicionales como formato o fuente predeterminada al cargar una presentación.
type: docs
url: /es/com.aspose.slides/loadoptions/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.ILoadOptions](../../com.aspose.slides/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

Permite especificar opciones adicionales (como formato o fuente predeterminada) al cargar una presentación.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Crea nuevas opciones de carga predeterminadas. |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | Crea nuevas opciones de carga. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Devuelve o establece el formato de una presentación a cargar. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Devuelve o establece el formato de una presentación a cargar. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Devuelve o establece la fuente Regular que se usa cuando no se encuentra la fuente origen. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Devuelve o establece la fuente Regular que se usa cuando no se encuentra la fuente origen. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Devuelve o establece la fuente Symbol que se usa cuando no se encuentra la fuente origen. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Devuelve o establece la fuente Symbol que se usa cuando no se encuentra la fuente origen. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Devuelve o establece la fuente Asian que se usa cuando no se encuentra la fuente origen. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Devuelve o establece la fuente Asian que se usa cuando no se encuentra la fuente origen. |
| [getPassword()](#getPassword--) | Obtiene o establece la contraseña. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Obtiene o establece la contraseña. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Esta propiedad tiene sentido si el archivo de presentación está protegido con contraseña. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Esta propiedad tiene sentido si el archivo de presentación está protegido con contraseña. |
| [getWarningCallback()](#getWarningCallback--) | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o será abortado. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o será abortado. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Representa las opciones que pueden usarse para gestionar el comportamiento de manejo de Binary Large Objects (BLOBs), como el uso de archivos temporales o el número máximo de bytes de BLOBs en memoria. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Representa las opciones que pueden usarse para gestionar el comportamiento de manejo de Binary Large Objects (BLOBs), como el uso de archivos temporales o el número máximo de bytes de BLOBs en memoria. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Especifica fuentes externas que serán usadas por la presentación. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Especifica fuentes externas que serán usadas por la presentación. |
| [getInterruptionToken()](#getInterruptionToken--) | El token para monitorizar solicitudes de interrupción. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | El token para monitorizar solicitudes de interrupción. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Devuelve o establece la interfaz de devolución de llamada que gestiona la carga de recursos externos. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Devuelve o establece la interfaz de devolución de llamada que gestiona la carga de recursos externos. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Obtiene opciones para hojas de cálculo. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Obtiene opciones para hojas de cálculo. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Devuelve o establece el idioma predeterminado para el texto de la presentación. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Devuelve o establece el idioma predeterminado para el texto de la presentación. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Determina si Aspose.Slides eliminará todos los objetos binarios incrustados mientras se carga la presentación. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Determina si Aspose.Slides eliminará todos los objetos binarios incrustados mientras se carga la presentación. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```

Crea nuevas opciones de carga predeterminadas.

### LoadOptions(int loadFormat) {#LoadOptions-int-}
```
public LoadOptions(int loadFormat)
```

Crea nuevas opciones de carga.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| loadFormat | int | Formato de una presentación a cargar. |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Devuelve o establece el formato de una presentación a cargar. Lectura/escritura [LoadFormat](../../com.aspose.slides/loadformat).

**Devuelve:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```

Devuelve o establece el formato de una presentación a cargar. Lectura/escritura [LoadFormat](../../com.aspose.slides/loadformat).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

Devuelve o establece la fuente Regular que se usa cuando no se encuentra la fuente origen. Lectura/escritura String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Use load options to define the default regular and asian fonts
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Load the presentation
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Generate slide thumbnail
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // Generate PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Generate XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

Devuelve o establece la fuente Regular que se usa cuando no se encuentra la fuente origen. Lectura/escritura String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Use load options to define the default regular and asian fonts
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Load the presentation
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Generate slide thumbnail
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // Generate PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Generate XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```

Devuelve o establece la fuente Symbol que se usa cuando no se encuentra la fuente origen. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```

Devuelve o establece la fuente Symbol que se usa cuando no se encuentra la fuente origen. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```

Devuelve o establece la fuente Asian que se usa cuando no se encuentra la fuente origen. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```

Devuelve o establece la fuente Asian que se usa cuando no se encuentra la fuente origen. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

Obtiene o establece la contraseña. Lectura/escritura String.

--------------------

> ```
> El siguiente código de ejemplo muestra cómo abrir una presentación de PowerPoint protegida con contraseña.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // trabajar con la presentación descifrada
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Valor: La contraseña.

**Devuelve:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Obtiene o establece la contraseña. Lectura/escritura String.

--------------------

> ```
> El siguiente código de ejemplo muestra cómo abrir una presentación de PowerPoint protegida con contraseña.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // trabajar con la presentación descifrada
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Valor: La contraseña.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```

Esta propiedad tiene sentido si el archivo de presentación está protegido con contraseña. Un valor verdadero indica que solo se deben cargar las propiedades del documento desde un archivo de presentación cifrado y se debe ignorar la contraseña. Un valor falso indica que se debe cargar toda la presentación cifrada utilizando la contraseña correcta. Si la presentación no está cifrada, el valor de la propiedad siempre se ignora. Si las propiedades del documento de un archivo cifrado no son públicas y el valor de la propiedad es verdadero, las propiedades del documento no pueden cargarse y se lanzará una excepción. Lectura/escritura boolean.

**Devuelve:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```

Esta propiedad tiene sentido si el archivo de presentación está protegido con contraseña. Un valor verdadero indica que solo se deben cargar las propiedades del documento desde un archivo de presentación cifrado y se debe ignorar la contraseña. Un valor falso indica que se debe cargar toda la presentación cifrada utilizando la contraseña correcta. Si la presentación no está cifrada, el valor de la propiedad siempre se ignora. Si las propiedades del documento de un archivo cifrado no son públicas y el valor de la propiedad es verdadero, las propiedades del documento no pueden cargarse y se lanzará una excepción. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o será abortado. Lectura/escritura [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Devuelve:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o será abortado. Lectura/escritura [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```

Representa las opciones que pueden usarse para gestionar el comportamiento de manejo de Binary Large Objects (BLOBs), como el uso de archivos temporales o el número máximo de bytes de BLOBs en memoria. Estas opciones están diseñadas para establecer la mejor relación rendimiento/consumo de memoria para un entorno o requisitos particulares.

--------------------

Un Binary Large Object (BLOB) es un dato binario almacenado como una única entidad, p. ej., un BLOB puede ser un audio, video o la propia presentación.

**Devuelve:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```

Representa las opciones que pueden usarse para gestionar el comportamiento de manejo de Binary Large Objects (BLOBs), como el uso de archivos temporales o el número máximo de bytes de BLOBs en memoria. Estas opciones están diseñadas para establecer la mejor relación rendimiento/consumo de memoria para un entorno o requisitos particulares.

--------------------

Un Binary Large Object (BLOB) es un dato binario almacenado como una única entidad, p. ej., un BLOB puede ser un audio, video o la propia presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```

Especifica fuentes externas que serán usadas por la presentación. Estas fuentes están disponibles para la presentación durante todo su ciclo de vida y no se comparten con otras presentaciones.

--------------------

> ```
> El siguiente ejemplo muestra cómo especificar fuentes personalizadas usadas con PowerPoint Presentation.
>  
>  byte[] memoryFont1 = Files.readAllBytes(Paths.get("customfonts\\CustomFont1.ttf"));
>  byte[] memoryFont2 = Files.readAllBytes(Paths.get("customfonts\\CustomFont2.ttf"));
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  // trabajar con la presentación
>  //CustomFont1, CustomFont2 así como fuentes de las carpetas assets\fonts & global\fonts y sus subcarpetas están disponibles para la presentación
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Devuelve:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```

Especifica fuentes externas que serán usadas por la presentación. Estas fuentes están disponibles para la presentación durante todo su ciclo de vida y no se comparten con otras presentaciones.

--------------------

> ```
> El siguiente ejemplo muestra cómo especificar fuentes personalizadas usadas con PowerPoint Presentation.
>  
>  byte[] memoryFont1 = Files.readAllBytes(Paths.get("customfonts\\CustomFont1.ttf"));
>  byte[] memoryFont2 = Files.readAllBytes(Paths.get("customfonts\\CustomFont2.ttf"));
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //trabajar con la presentación
>  //CustomFont1, CustomFont2, así como fuentes de las carpetas assets\fonts y global\fonts y sus subcarpetas están disponibles para la presentación
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```

El token para monitorizar solicitudes de interrupción.

--------------------

Este token gestiona toda la vida de la instancia [IPresentation](../../com.aspose.slides/ipresentation). Cualquier operación de larga duración, como cargar o guardar una presentación, será interrumpida mediante la llamada al método [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) del [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Devuelve:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```

El token para monitorizar solicitudes de interrupción.

--------------------

Este token gestiona toda la vida de la instancia [IPresentation](../../com.aspose.slides/ipresentation). Cualquier operación de larga duración, como cargar o guardar una presentación, será interrumpida mediante la llamada al método [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) del [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```

Devuelve o establece la interfaz de devolución de llamada que gestiona la carga de recursos externos. Lectura/escritura [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Devuelve:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Devuelve o establece la interfaz de devolución de llamada que gestiona la carga de recursos externos. Lectura/escritura [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```

Obtiene opciones para hojas de cálculo. Por ejemplo, estas opciones afectan al cálculo de fórmulas para gráficos.

**Devuelve:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Obtiene opciones para hojas de cálculo. Por ejemplo, estas opciones afectan al cálculo de fórmulas para gráficos.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```

Devuelve o establece el idioma predeterminado para el texto de la presentación. Lectura/escritura String.

--------------------

> ```
> Ejemplo:
>   
>  // Utilice opciones de carga para definir la cultura de texto predeterminada
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Añadir nueva forma de rectángulo con texto
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Comprobar el idioma de la primera porción
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
java.lang.String
### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public final void setDefaultTextLanguage(String value)
```

Devuelve o establece el idioma predeterminado para el texto de la presentación. Lectura/escritura String.

--------------------

> ```
> Ejemplo:
>   
>  // Utilice opciones de carga para definir la cultura de texto predeterminada
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Añadir nueva forma de rectángulo con texto
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Comprobar el idioma de la primera porción
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
public final boolean getDeleteEmbeddedBinaryObjects()
```

Determina si Aspose.Slides eliminará todos los objetos binarios incrustados mientras se carga la presentación.

Los tipos de los objetos binarios incrustados:

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

Predeterminado es **false**.

**Devuelve:**
boolean
### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```

Determina si Aspose.Slides eliminará todos los objetos binarios incrustados mientras se carga la presentación.

Los tipos de los objetos binarios incrustados:

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

Predeterminado es **false**.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |