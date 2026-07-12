---
title: IDocumentProperties
second_title: Aspose.Slides para Android vía Referencia de API Java
description: Representa las propiedades de una presentación.
type: docs
url: /es/com.aspose.slides/idocumentproperties/
---```
public interface IDocumentProperties
```

Representa las propiedades de una presentación.
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
| [getContentStatus()](#getContentStatus--) | Devuelve o establece el estado de contenido de una presentación. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Devuelve o establece el estado de contenido de una presentación. |
| [getContentType()](#getContentType--) | Devuelve o establece el tipo de contenido de una presentación. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Devuelve o establece el tipo de contenido de una presentación. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Devuelve o establece la propiedad de documento HyperlinkBase. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Devuelve o establece la propiedad de documento HyperlinkBase. |
| [getScaleCrop()](#getScaleCrop--) | Indica el modo de visualización de la miniatura del documento. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Indica el modo de visualización de la miniatura del documento. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Indica si los hipervínculos en un documento están actualizados. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Indica si los hipervínculos en un documento están actualizados. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Especifica que uno o más hipervínculos en esta parte fueron actualizados exclusivamente en esta parte por un productor. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Especifica que uno o más hipervínculos en esta parte fueron actualizados exclusivamente en esta parte por un productor. |
| [getSlides()](#getSlides--) | Especifica el número total de diapositivas en un documento de presentación. |
| [getHiddenSlides()](#getHiddenSlides--) | Especifica el número de diapositivas ocultas en un documento de presentación. |
| [getNotes()](#getNotes--) | Especifica el número de diapositivas en una presentación que contienen notas. |
| [getParagraphs()](#getParagraphs--) | Especifica el número total de párrafos encontrados en un documento, si corresponde. |
| [getWords()](#getWords--) | Especifica el número total de palabras contenidas en un documento. |
| [getMultimediaClips()](#getMultimediaClips--) | Especifica el número total de clips de sonido o video presentes en el documento. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Especifica el título de cada parte del documento. |
| [getHeadingPairs()](#getHeadingPairs--) | Indica la agrupación de partes del documento y el número de partes en cada grupo. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Devuelve el número de propiedades personalizadas realmente contenidas en una colección. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Devuelve el nombre de una propiedad personalizada en el índice especificado. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Elimina una propiedad personalizada asociada con un nombre especificado. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Comprueba la presencia de una propiedad personalizada con un nombre especificado. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Devuelve o establece la propiedad personalizada asociada con un nombre especificado. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Devuelve o establece la propiedad personalizada asociada con un nombre especificado. |
| [clearCustomProperties()](#clearCustomProperties--) | Elimina todas las propiedades personalizadas. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Borra y establece valores predeterminados para todas las propiedades integradas. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Obtiene un valor booleano con nombre de las propiedades personalizadas. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Obtiene un valor entero con nombre de las propiedades personalizadas. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Obtiene un valor DateTime con nombre de las propiedades personalizadas. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Obtiene un valor string con nombre de las propiedades personalizadas. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Obtiene un valor float con nombre de las propiedades personalizadas. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Obtiene un valor double con nombre de las propiedades personalizadas. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Define una propiedad personalizada booleana con nombre. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Define una propiedad personalizada entera con nombre. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Define una propiedad personalizada DateTime con nombre. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Define una propiedad personalizada string con nombre. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Define una propiedad personalizada float con nombre. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Define una propiedad personalizada double con nombre. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Obtiene una matriz de etiquetas de sensibilidad de las propiedades personalizadas del documento (Microsoft Information Protection SDK Metadata). |
### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```

Devuelve la versión de la aplicación. String de solo lectura.

--------------------

El contenido de este elemento debe tener la forma XX.YYYY, donde X y Y representan valores numéricos; de lo contrario, el documento se considerará no conforme. Aspose.Slides representa su versión en el formato XX.YY.ZZ, donde: XX - versión principal YY - versión menor ZZ - versión de parche. Por ejemplo, el valor 23.0105 significa la versión 23.1.5 de Aspose.Slides.

**Devuelve:** java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public abstract String getNameOfApplication()
```

Devuelve o establece el nombre de la aplicación. String de lectura/escritura.

**Devuelve:** java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public abstract void setNameOfApplication(String value)
```

Devuelve o establece el nombre de la aplicación. String de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |
### getCompany() {#getCompany--}
```
public abstract String getCompany()
```

Devuelve o establece la propiedad de la empresa. String de lectura/escritura.

**Devuelve:** java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public abstract void setCompany(String value)
```

Devuelve o establece la propiedad de la empresa. String de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |
### getManager() {#getManager--}
```
public abstract String getManager()
```

Devuelve o establece la propiedad del gestor. String de lectura/escritura.

**Devuelve:** java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```

Devuelve o establece la propiedad del gestor. String de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresentationFormat() {#getPresentationFormat--}
```
public abstract String getPresentationFormat()
```

Devuelve o establece el formato previsto de una presentación. String de lectura/escritura.

**Devuelve:** java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public abstract void setPresentationFormat(String value)
```

Devuelve o establece el formato previsto de una presentación. String de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |
### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```

Determina si la presentación se comparte entre varias personas. boolean de lectura/escritura.

**Devuelve:** boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```

Determina si la presentación se comparte entre varias personas. boolean de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```

Devuelve o establece la plantilla de una aplicación. String de lectura/escritura.

**Devuelve:** java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public abstract void setApplicationTemplate(String value)
```

Devuelve o establece la plantilla de una aplicación. String de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |
### getTotalEditingTime() {#getTotalEditingTime--}
```
public abstract double getTotalEditingTime()
```

Tiempo total de edición de una presentación. double de lectura/escritura.

**Devuelve:** double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public abstract void setTotalEditingTime(double value)
```

Tiempo total de edición de una presentación. double de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |
### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

Devuelve o establece el título de una presentación. String de lectura/escritura.

**Devuelve:** java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

Devuelve o establece el título de una presentación. String de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |
### getSubject() {#getSubject--}
```
public abstract String getSubject()
```

Devuelve o establece el asunto de una presentación. String de lectura/escritura.

**Devuelve:** java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```

Devuelve o establece el asunto de una presentación. String de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |
### getAuthor() {#getAuthor--}
```
public abstract String getAuthor()
```

Devuelve o establece el autor de una presentación. String de lectura/escritura.

**Devuelve:** java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public abstract void setAuthor(String value)
```

Devuelve o establece el autor de una presentación. String de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |
### getKeywords() {#getKeywords--}
```
public abstract String getKeywords()
```

Devuelve o establece las palabras clave de una presentación. String de lectura/escritura.

**Devuelve:** java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public abstract void setKeywords(String value)
```

Devuelve o establece las palabras clave de una presentación. String de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public abstract String getComments()
```

Devuelve o establece los comentarios de una presentación. String de lectura/escritura.

**Devuelve:** java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

Devuelve o establece los comentarios de una presentación. String de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |
### getCategory() {#getCategory--}
```
public abstract String getCategory()
```

Devuelve o establece la categoría de una presentación. String de lectura/escritura.

**Devuelve:** java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public abstract void setCategory(String value)
```

Devuelve o establece la categoría de una presentación. String de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

Devuelve la fecha en que se creó una presentación. Los valores están en UTC. java.util.Date de lectura/escritura.

**Devuelve:** java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Devuelve la fecha en que se creó una presentación. Los valores están en UTC. java.util.Date de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```

Devuelve la fecha en que una presentación se modificó por última vez. Los valores están en UTC.P Solo lectura en caso de Presentation.DocumentProperties (porque se actualizará internamente durante el proceso de guardado del objeto IPresentation). Puede modificarse mediante la instancia DocumentProperties devuelta por el método [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Consulte el ejemplo en el resumen del método [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Devuelve:** java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```

Devuelve la fecha en que una presentación se modificó por última vez. Los valores están en UTC.P Solo lectura en caso de Presentation.DocumentProperties (porque se actualizará internamente durante el proceso de guardado del objeto IPresentation). Puede modificarse mediante la instancia DocumentProperties devuelta por el método [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Consulte el ejemplo en el resumen del método [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```

Devuelve la fecha en que una presentación se imprimió por última vez. java.util.Date de lectura/escritura.

**Devuelve:** java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```

Devuelve la fecha en que una presentación se imprimió por última vez. java.util.Date de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```

Devuelve o establece el nombre de la última persona que modificó una presentación. String de lectura/escritura.

**Devuelve:** java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```

Devuelve o establece el nombre de la última persona que modificó una presentación. String de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |
### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```

Devuelve o establece el número de revisión de la presentación. int de lectura/escritura.

**Devuelve:** int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```

Devuelve o establece el número de revisión de la presentación. int de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```

Devuelve o establece el estado de contenido de una presentación. String de lectura/escritura.

**Devuelve:** java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentStatus(String value)
```

Devuelve o establece el estado de contenido de una presentación. String de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Devuelve o establece el tipo de contenido de una presentación. String de lectura/escritura.

**Devuelve:** java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```

Devuelve o establece el tipo de contenido de una presentación. String de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |
### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```

Devuelve o establece la propiedad de documento HyperlinkBase. String de lectura/escritura.

**Devuelve:** java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```

Devuelve o establece la propiedad de documento HyperlinkBase. String de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |
### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```

Indica el modo de visualización de la miniatura del documento. Establezca este elemento en **true** para habilitar el escalado de la miniatura al tamaño de la pantalla. Establezca este elemento en **false** para habilitar el recorte de la miniatura y mostrar solo las secciones que se ajusten a la pantalla. boolean de lectura/escritura.

**Devuelve:** boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```

Indica el modo de visualización de la miniatura del documento. Establezca este elemento en **true** para habilitar el escalado de la miniatura al tamaño de la pantalla. Establezca este elemento en **false** para habilitar el recorte de la miniatura y mostrar solo las secciones que se ajusten a la pantalla. boolean de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```

Indica si los hipervínculos en un documento están actualizados. Establezca este elemento en **true** para indicar que los hipervínculos están actualizados. Establezca este elemento en **false** para indicar que los hipervínculos están desactualizados. boolean de lectura/escritura.

**Devuelve:** boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```

Indica si los hipervínculos en un documento están actualizados. Establezca este elemento en **true** para indicar que los hipervínculos están actualizados. Establezca este elemento en **false** para indicar que los hipervínculos están desactualizados. boolean de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```

Especifica que uno o más hipervínculos en esta parte fueron actualizados exclusivamente en esta parte por un productor. El siguiente productor que abra este documento deberá actualizar las relaciones de hipervínculo con los nuevos hipervínculos especificados en esta parte. boolean de lectura/escritura.

**Devuelve:** boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract boolean getHyperlinksChanged()
```

Especifica que uno o más hipervínculos en esta parte fueron actualizados exclusivamente en esta parte por un productor. El siguiente productor que abra este documento deberá actualizar las relaciones de hipervínculo con los nuevos hipervínculos especificados en esta parte. boolean de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getSlides() {#getSlides--}
```
public abstract int getSlides()
```

Especifica el número total de diapositivas en un documento de presentación. int de solo lectura.

**Devuelve:** int
### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```

Especifica el número de diapositivas ocultas en un documento de presentación. int de solo lectura.

**Devuelve:** int
### getNotes() {#getNotes--}
```
public abstract int getNotes()
```

Especifica el número de diapositivas en una presentación que contienen notas. int de solo lectura.

**Devuelve:** int
### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```

Especifica el número total de párrafos encontrados en un documento, si corresponde. int de solo lectura.

**Devuelve:** int
### getWords() {#getWords--}
```
public abstract int getWords()
```

Especifica el número total de palabras contenidas en un documento. int de solo lectura.

**Devuelve:** int
### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```

Especifica el número total de clips de sonido o video presentes en el documento. int de solo lectura.

**Devuelve:** int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```

Especifica el título de cada parte del documento. Estas partes no son partes del documento sino representaciones conceptuales de secciones del documento. String[] de solo lectura.

**Devuelve:** java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```

Indica la agrupación de partes del documento y el número de partes en cada grupo. IHeadingPair[] de solo lectura.

**Devuelve:** com.aspose.slides.IHeadingPair[]
### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```

Devuelve el número de propiedades personalizadas realmente contenidas en una colección. int de solo lectura.

**Devuelve:** int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```

Devuelve el nombre de una propiedad personalizada en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero de la propiedad personalizada a obtener. |

**Devuelve:** java.lang.String - Nombre de la propiedad personalizada en el índice especificado.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public abstract boolean removeCustomProperty(String name)
```

Elimina una propiedad personalizada asociada con un nombre especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la propiedad personalizada a eliminar. |

**Devuelve:** boolean - Devuelve true si se eliminó una propiedad, false en caso contrario.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public abstract boolean containsCustomProperty(String name)
```

Comprueba la presencia de una propiedad personalizada con un nombre especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la propiedad personalizada a comprobar. |

**Devuelve:** boolean - Devuelve true si la propiedad existe, false en caso contrario.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract Object get_Item(String name)
```

Devuelve o establece la propiedad personalizada asociada con un nombre especificado. Object de lectura/escritura.

--------------------

El valor puede ser **int**, **float**, **double**, **String**, **boolean** o **Date**.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String |  |

**Devuelve:** java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```

Devuelve o establece la propiedad personalizada asociada con un nombre especificado. Object de lectura/escritura.

--------------------

El valor puede ser **int**, **float**, **double**, **String**, **boolean** o **Date**.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |
### clearCustomProperties() {#clearCustomProperties--}
```
public abstract void clearCustomProperties()
```

Elimina todas las propiedades personalizadas.
### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public abstract void clearBuiltInProperties()
```

Borra y establece valores predeterminados para todas las propiedades integradas.
### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```

Obtiene un valor booleano con nombre de las propiedades personalizadas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la propiedad personalizada a obtener |
| value | boolean[] | Valor de la propiedad personalizada |
### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```

Obtiene un valor entero con nombre de las propiedades personalizadas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la propiedad personalizada a obtener |
| value | int[] | Valor de la propiedad personalizada |
### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```

Obtiene un valor DateTime con nombre de las propiedades personalizadas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la propiedad personalizada a obtener |
| value | java.util.Date[] | Valor de la propiedad personalizada |
### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```

Obtiene un valor string con nombre de las propiedades personalizadas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la propiedad personalizada a obtener |
| value | java.lang.String[] | Valor de la propiedad personalizada |
### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```

Obtiene un valor float con nombre de las propiedades personalizadas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la propiedad personalizada a obtener |
| value | float[] | Valor de la propiedad personalizada |
### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```

Obtiene un valor double con nombre de las propiedades personalizadas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la propiedad personalizada a obtener. |
| value | double[] | Valor de la propiedad personalizada |
### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```

Define una propiedad personalizada booleana con nombre.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la propiedad personalizada a definir |
| value | boolean | Valor de la propiedad personalizada |
### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```

Define una propiedad personalizada entera con nombre.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la propiedad personalizada a definir |
| value | int | Valor de la propiedad personalizada |
### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```

Define una propiedad personalizada DateTime con nombre.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la propiedad personalizada a definir |
| value | java.util.Date | Valor de la propiedad personalizada |
### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```

Define una propiedad personalizada string con nombre.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la propiedad personalizada a definir |
| value | java.lang.String | Valor de la propiedad personalizada |
### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```

Define una propiedad personalizada float con nombre.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la propiedad personalizada a definir |
| value | float | Valor de la propiedad personalizada |
### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```

Define una propiedad personalizada double con nombre.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la propiedad personalizada a definir |
| value | double | Valor de la propiedad personalizada |
### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```

Obtiene una matriz de etiquetas de sensibilidad de las propiedades personalizadas del documento (Microsoft Information Protection SDK Metadata).

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Get sensitivity labels from the custom document properties
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Add label to the collection
>          // Here you can add a check for the validity of the label information (the label is available, etc)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:** com.aspose.slides.ISensitivityLabel[]