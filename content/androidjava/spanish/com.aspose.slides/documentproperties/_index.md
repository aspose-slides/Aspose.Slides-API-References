---
title: DocumentProperties
second_title: Referencia de API de Aspose.Slides para Android mediante Java
description: Representa las propiedades de una presentación.
type: docs
url: /es/com.aspose.slides/documentproperties/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IDocumentProperties](../../com.aspose.slides/idocumentproperties), com.aspose.slides.IGenericCloneable, java.lang.Cloneable
```
public class DocumentProperties implements IDocumentProperties, IGenericCloneable<IDocumentProperties>, Cloneable
```

Representa las propiedades de una presentación.

--------------------

> ```
> The following example shows how to access built-in Properties of PowerPoint Presentation.
>  
>  // Instanciar la clase Presentation que representa la presentación
>  Presentation pres = new Presentation("AccessBuiltin Properties.pptx");
>  try {
>      // Crear una referencia al objeto IDocumentProperties asociado a Presentation
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Mostrar las propiedades integradas
>      System.out.println("Category : " + documentProperties.getCategory());
>      System.out.println("Current Status : " + documentProperties.getContentStatus());
>      System.out.println("Creation Date : " + documentProperties.getCreatedTime());
>      System.out.println("Author : " + documentProperties.getAuthor());
>      System.out.println("Description : " + documentProperties.getComments());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to modify built-in Properties of PowerPoint Presentation.
>  
>  // Instanciar la clase Presentation que representa la Presentation
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // Crear una referencia al objeto IDocumentProperties asociado a Presentation
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Establecer las propiedades integradas
>      documentProperties.setAuthor("Aspose.Slides for Android via Java");
>      documentProperties.setTitle("Modifying Presentation Properties");
>      documentProperties.setSubject("Aspose Subject");
>      // Guardar la presentación en un archivo
>      pres.save("DocumentProperties_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Constructores

| Constructor | Descripción |
| --- | --- |
| [DocumentProperties()](#DocumentProperties--) | Inicializa una nueva instancia de la clase [DocumentProperties](../../com.aspose.slides/documentproperties). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Devuelve la versión de la aplicación. |
| [getNameOfApplication()](#getNameOfApplication--) | Devuelve o establece el nombre de la aplicación. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Devuelve o establece el nombre de la aplicación. |
| [getCompany()](#getCompany--) | Devuelve o establece la propiedad de la empresa. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Devuelve o establece la propiedad de la empresa. |
| [getManager()](#getManager--) | Devuelve o establece la propiedad del gestor. |
| [setManager(String value)](#setManager-java.lang.String-) | Devuelve o establece la propiedad del gestor. |
| [getPresentationFormat()](#getPresentationFormat--) | Devuelve o establece el formato previsto de una presentación. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Devuelve o establece el formato previsto de una presentación. |
| [getSharedDoc()](#getSharedDoc--) | Determina si la presentación se comparte entre varias personas. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Determina si la presentación se comparte entre varias personas. |
| [getApplicationTemplate()](#getApplicationTemplate--) | Devuelve o establece la plantilla de una aplicación. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | Devuelve o establece la plantilla de una aplicación. |
| [getTotalEditingTime()](#getTotalEditingTime--) | Tiempo total de edición de una presentación. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | Tiempo total de edición de una presentación. |
| [getTitle()](#getTitle--) | Devuelve o establece el título de una presentación. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Devuelve o establece el título de una presentación. |
| [getSubject()](#getSubject--) | Devuelve o establece el asunto de una presentación. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Devuelve o establece el asunto de una presentación. |
| [getAuthor()](#getAuthor--) | Devuelve o establece el autor de una presentación. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Devuelve o establece el autor de una presentación. |
| [getKeywords()](#getKeywords--) | Devuelve o establece las palabras clave de una presentación. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Devuelve o establece las palabras clave de una presentación. |
| [getComments()](#getComments--) | Devuelve o establece los comentarios de una presentación. |
| [setComments(String value)](#setComments-java.lang.String-) | Devuelve o establece los comentarios de una presentación. |
| [getCategory()](#getCategory--) | Devuelve o establece la categoría de una presentación. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Devuelve o establece la categoría de una presentación. |
| [getCreatedTime()](#getCreatedTime--) | Devuelve la fecha en que se creó una presentación. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Devuelve la fecha en que se creó una presentación. |
| [getLastSavedTime()](#getLastSavedTime--) | Devuelve la fecha en que una presentación se modificó por última vez. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Devuelve la fecha en que una presentación se modificó por última vez. |
| [getLastPrinted()](#getLastPrinted--) | Devuelve la fecha en que una presentación se imprimió por última vez. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Devuelve la fecha en que una presentación se imprimió por última vez. |
| [getLastSavedBy()](#getLastSavedBy--) | Devuelve o establece el nombre de la última persona que modificó una presentación. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Devuelve o establece el nombre de la última persona que modificó una presentación. |
| [getRevisionNumber()](#getRevisionNumber--) | Devuelve o establece el número de revisión de la presentación. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Devuelve o establece el número de revisión de la presentación. |
| [getContentStatus()](#getContentStatus--) | Devuelve o establece el estado del contenido de una presentación. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Devuelve o establece el estado del contenido de una presentación. |
| [getContentType()](#getContentType--) | Devuelve o establece el tipo de contenido de una presentación. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Devuelve o establece el tipo de contenido de una presentación. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Devuelve o establece la propiedad de documento HyperlinkBase. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Devuelve o establece la propiedad de documento HyperlinkBase. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Devuelve el número de propiedades personalizadas realmente contenidas en una colección. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Devuelve el nombre de una propiedad personalizada en el índice especificado. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Elimina una propiedad personalizada asociada a un nombre especificado. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Comprueba la presencia de una propiedad personalizada con un nombre especificado. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Devuelve o establece la propiedad personalizada asociada a un nombre especificado. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Devuelve o establece la propiedad personalizada asociada a un nombre especificado. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Obtiene un valor booleano con nombre de las propiedades personalizadas. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Obtiene un valor entero con nombre de las propiedades personalizadas. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Obtiene un valor DateTime con nombre de las propiedades personalizadas. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Obtiene un valor cadena con nombre de las propiedades personalizadas. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Obtiene un valor flotante con nombre de las propiedades personalizadas. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Obtiene un valor doble con nombre de las propiedades personalizadas. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Establece una propiedad personalizada booleana con nombre. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Establece una propiedad personalizada entera con nombre. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Establece una propiedad personalizada DateTime con nombre. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Establece una propiedad personalizada cadena con nombre. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Establece una propiedad personalizada flotante con nombre. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Establece una propiedad personalizada doble con nombre. |
| [clearCustomProperties()](#clearCustomProperties--) | Elimina todas las propiedades personalizadas. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Obtiene una matriz de etiquetas de sensibilidad de las propiedades personalizadas del documento (Microsoft Information Protection SDK Metadata). |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Borra y establece valores predeterminados para todas las propiedades incorporadas. |
| [getScaleCrop()](#getScaleCrop--) | Indica el modo de visualización de la miniatura del documento. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Indica el modo de visualización de la miniatura del documento. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Indica si los hipervínculos en un documento están actualizados. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Indica si los hipervínculos en un documento están actualizados. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Especifica que uno o más hipervínculos en esta parte fueron actualizados exclusivamente en esta parte por un productor. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Especifica que uno o más hipervínculos en esta parte fueron actualizados exclusivamente en esta parte por un productor. |
| [getSlides()](#getSlides--) | Devuelve el número total de diapositivas en un documento de presentación. |
| [getHiddenSlides()](#getHiddenSlides--) | Devuelve el número de diapositivas ocultas en un documento de presentación. |
| [getNotes()](#getNotes--) | Devuelve el número de diapositivas en una presentación que contienen notas. |
| [getParagraphs()](#getParagraphs--) | Devuelve el número total de párrafos encontrados en un documento, si corresponde. |
| [getWords()](#getWords--) | Devuelve el número total de palabras contenidas en un documento. |
| [getMultimediaClips()](#getMultimediaClips--) | Devuelve el número total de clips de sonido o vídeo presentes en el documento. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Especifica el título de cada parte del documento. |
| [getHeadingPairs()](#getHeadingPairs--) | Indica la agrupación de partes del documento y el número de partes en cada grupo. |
| [deepClone()](#deepClone--) | Clona el objeto actual |
| [cloneT()](#cloneT--) | Clona el objeto actual |
### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```

Inicializa una nueva instancia de la clase [DocumentProperties](../../com.aspose.slides/documentproperties).

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```

Devuelve la versión de la aplicación. Solo lectura String.

**Devuelve:**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```

Devuelve o establece el nombre de la aplicación. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```

Devuelve o establece el nombre de la aplicación. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public final String getCompany()
```

Devuelve o establece la propiedad de la empresa. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```

Devuelve o establece la propiedad de la empresa. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public final String getManager()
```

Devuelve o establece la propiedad del gestor. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```

Devuelve o establece la propiedad del gestor. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```

Devuelve o establece el formato previsto de una presentación. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```

Devuelve o establece el formato previsto de una presentación. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```

Determina si la presentación se comparte entre varias personas. Lectura/escritura boolean.

**Devuelve:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```

Determina si la presentación se comparte entre varias personas. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```

Devuelve o establece la plantilla de una aplicación. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```

Devuelve o establece la plantilla de una aplicación. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```

Tiempo total de edición de una presentación. Lectura/escritura double.

**Devuelve:**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```

Tiempo total de edición de una presentación. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```

Devuelve o establece el título de una presentación. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

Devuelve o establece el título de una presentación. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```

Devuelve o establece el asunto de una presentación. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```

Devuelve o establece el asunto de una presentación. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```

Devuelve o establece el autor de una presentación. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```

Devuelve o establece el autor de una presentación. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```

Devuelve o establece las palabras clave de una presentación. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```

Devuelve o establece las palabras clave de una presentación. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```

Devuelve o establece los comentarios de una presentación. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

Devuelve o establece los comentarios de una presentación. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public final String getCategory()
```

Devuelve o establece la categoría de una presentación. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```

Devuelve o establece la categoría de una presentación. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

Devuelve la fecha en que se creó una presentación. Los valores están en UTC. Lectura/escritura java.util.Date.

**Devuelve:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

Devuelve la fecha en que se creó una presentación. Los valores están en UTC. Lectura/escritura java.util.Date.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```

Devuelve la fecha en que una presentación se modificó por última vez. Los valores están en UTC. Solo lectura en caso de Presentation.DocumentProperties (porque se actualizará internamente durante el proceso de guardado del objeto IPresentation). Puede modificarse a través de la instancia DocumentProperties devuelta por el método [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Consulte el ejemplo en el resumen del método [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Devuelve:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```

Devuelve la fecha en que una presentación se modificó por última vez. Los valores están en UTC. Solo lectura en caso de Presentation.DocumentProperties (porque se actualizará internamente durante el proceso de guardado del objeto IPresentation). Puede modificarse a través de la instancia DocumentProperties devuelta por el método [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Consulte el ejemplo en el resumen del método [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```

Devuelve la fecha en que una presentación se imprimió por última vez. Lectura/escritura java.util.Date.

**Devuelve:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```

Devuelve la fecha en que una presentación se imprimió por última vez. Lectura/escritura java.util.Date.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public final String getLastSavedBy()
```

Devuelve o establece el nombre de la última persona que modificó una presentación. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```

Devuelve o establece el nombre de la última persona que modificó una presentación. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```

Devuelve o establece el número de revisión de la presentación. Lectura/escritura int.

**Devuelve:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public final void setRevisionNumber(int value)
```

Devuelve o establece el número de revisión de la presentación. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public final String getContentStatus()
```

Devuelve o establece el estado del contenido de una presentación. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public final void setContentStatus(String value)
```

Devuelve o establece el estado del contenido de una presentación. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

Devuelve o establece el tipo de contenido de una presentación. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

Devuelve o establece el tipo de contenido de una presentación. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```

Devuelve o establece la propiedad de documento HyperlinkBase. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```

Devuelve o establece la propiedad de documento HyperlinkBase. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public final int getCountOfCustomProperties()
```

Devuelve el número de propiedades personalizadas realmente contenidas en una colección. Solo lectura int.

**Devuelve:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public final String getCustomPropertyName(int index)
```

Devuelve el nombre de una propiedad personalizada en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero de la propiedad personalizada a obtener. |

**Devuelve:**
java.lang.String - Nombre de la propiedad personalizada en el índice especificado.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public final boolean removeCustomProperty(String name)
```

Elimina una propiedad personalizada asociada a un nombre especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la propiedad personalizada a eliminar. |

**Devuelve:**
boolean - Devuelve true si se eliminó una propiedad, false en caso contrario.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public final boolean containsCustomProperty(String name)
```

Comprueba la presencia de una propiedad personalizada con un nombre especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la propiedad personalizada a comprobar. |

**Devuelve:**
boolean - Devuelve true si la propiedad existe, false en caso contrario.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final Object get_Item(String name)
```

Devuelve o establece la propiedad personalizada asociada a un nombre especificado. Lectura/escritura Object.

--------------------

El valor puede ser **int**, **float**, **String**, **boolean** o **Date**.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String |  |

**Devuelve:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public final void set_Item(String name, Object value)
```

Devuelve o establece la propiedad personalizada asociada a un nombre especificado. Lectura/escritura Object.

--------------------

El valor puede ser **int**, **float**, **String**, **boolean** o **Date**.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public final void getCustomPropertyValue(String name, boolean[] value)
```

Obtiene un valor booleano con nombre de las propiedades personalizadas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la propiedad personalizada a obtener |
| value | boolean[] | Valor de la propiedad personalizada |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public **** ** ** ** ** ** ** ** ** 
```

Obtiene un valor entero con nombre de las propiedades personalizadas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la propiedad personalizada a obtener |
| value | int[] | Valor de la propiedad personalizada |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```

Obtiene un valor DateTime con nombre de las propiedades personalizadas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la propiedad personalizada a obtener |
| value | java.util.Date[] | Valor de la propiedad personalizada |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public final void getCustomPropertyValue(String name, String[] value)
```

Obtiene un valor cadena con nombre de las propiedades personalizadas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la propiedad personalizada a obtener |
| value | java.lang.String[] | Valor de la propiedad personalizada |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```

Obtiene un valor flotante con nombre de las propiedades personalizadas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la propiedad personalizada a obtener |
| value | float[] | Valor de la propiedad personalizada |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```

Obtiene un valor doble con nombre de las propiedades personalizadas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la propiedad personalizada a obtener. |
| value | double[] | Valor de la propiedad personalizada |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```

Establece una propiedad personalizada booleana con nombre.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la propiedad personalizada a establecer |
| value | boolean | Valor de la propiedad personalizada |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```

Establece una propiedad personalizada entera con nombre.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la propiedad personalizada a establecer |
| value | int | Valor de la propiedad personalizada |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```

Establece una propiedad personalizada DateTime con nombre.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la propiedad personalizada a establecer |
| value | java.util.Date | Valor de la propiedad personalizada |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public final void setCustomPropertyValue(String name, String value)
```

Establece una propiedad personalizada cadena con nombre.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la propiedad personalizada a establecer |
| value | java.lang.String | Valor de la propiedad personalizada |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```

Establece una propiedad personalizada flotante con nombre.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la propiedad personalizada a establecer |
| value | float | Valor de la propiedad personalizada |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```

Establece una propiedad personalizada doble con nombre.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la propiedad personalizada a establecer |
| value | double | Valor de la propiedad personalizada |

### clearCustomProperties() {#clearCustomProperties--}
```
public final void clearCustomProperties()
```

Elimina todas las propiedades personalizadas.

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabel[] getSensitivityLabels()
```

Obtiene una matriz de etiquetas de sensibilidad de las propiedades personalizadas del documento (Microsoft Information Protection SDK Metadata).

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Obtener etiquetas de sensibilidad de las propiedades personalizadas del documento
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Agregar etiqueta a la colección
>          // Aquí puedes agregar una verificación de la validez de la información de la etiqueta (la etiqueta está disponible, etc.)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
com.aspose.slides.ISensitivityLabel[]
### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public final void clearBuiltInProperties()
```

Borra y establece valores predeterminados para todas las propiedades integradas.

### getScaleCrop() {#getScaleCrop--}
```
public final boolean getScaleCrop()
```

Indica el modo de visualización de la miniatura del documento. Establezca este elemento en **true** para habilitar el escalado de la miniatura del documento a la pantalla. Establezca este elemento en **false** para habilitar el recorte de la miniatura del documento y mostrar solo las secciones que se ajustan a la pantalla. Lectura/escritura boolean.

**Devuelve:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public final void setScaleCrop(boolean value)
```

Indica el modo de visualización de la miniatura del documento. Establezca este elemento en **true** para habilitar el escalado de la miniatura del documento a la pantalla. Establezca este elemento en **false** para habilitar el recorte de la miniatura del documento y mostrar solo las secciones que se ajustan a la pantalla. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public final boolean getLinksUpToDate()
```

Indica si los hipervínculos en un documento están actualizados. Establezca este elemento en **true** para indicar que los hipervínculos están actualizados. Establezca este elemento en **false** para indicar que los hipervínculos están desactualizados. Lectura/escritura boolean.

**Devuelve:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public final void setLinksUpToDate(boolean value)
```

Indica si los hipervínculos en un documento están actualizados. Establezca este elemento en **true** para indicar que los hipervínculos están actualizados. Establezca este elemento en **false** para indicar que los hipervínculos están desactualizados. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

Especifica que uno o más hipervínculos en esta parte fueron actualizados exclusivamente en esta parte por un productor. El siguiente productor que abra este documento actualizará las relaciones de hipervínculos con los nuevos hipervínculos especificados en esta parte. Lectura/escritura boolean.

**Devuelve:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

Especifica que uno o más hipervínculos en esta parte fueron actualizados exclusivamente en esta parte por un productor. El siguiente productor que abra este documento actualizará las relaciones de hipervínculos con los nuevos hipervínculos especificados en esta parte. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public final int getSlides()
```

Devuelve el número total de diapositivas en un documento de presentación. Solo lectura int.

**Devuelve:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

Devuelve el número de diapositivas ocultas en un documento de presentación. Solo lectura int.

**Devuelve:**
int
### getNotes() {#getNotes--}
```
public 


The answer? **:**



Okay



The…

```

Devuelve el número de diapositivas en una presentación que contienen notas. Solo lectura int.

**Devuelve:**
int
### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```

Devuelve el número total de párrafos encontrados en un documento, si corresponde. Solo lectura int.

**Devuelve:**
int
### getWords() {#getWords--}
```
public final int getWords()
```

Devuelve el número total de palabras contenidas en un documento. Solo lectura int.

**Devuelve:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

Devuelve el número total de clips de sonido o vídeo presentes en el documento. Solo lectura int.

**Devuelve:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

Especifica el título de cada parte del documento. Estas partes no son partes del documento sino representaciones conceptuales de secciones del documento. Solo lectura String[].

**Devuelve:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```

Indica la agrupación de partes del documento y el número de partes en cada grupo. Solo lectura IHeadingPair[].

**Devuelve:**
com.aspose.slides.IHeadingPair[]
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Clona el objeto actual

**Devuelve:**
java.lang.Object - Clone
### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

Clona el objeto actual

**Devuelve:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Clone