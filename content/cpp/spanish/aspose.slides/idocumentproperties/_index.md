---
title: IDocumentProperties
second_title: Referencia de API de Aspose.Slides para C++
description: Representa propiedades de una presentación.
type: docs
weight: 1977
url: /es/aspose.slides/idocumentproperties/
---
## IDocumentProperties clase

Representa propiedades de una presentación.

```cpp
class IDocumentProperties : public virtual System::Object
```

## Métodos

| Method | Description |
| --- | --- |
| virtual void [ClearBuiltInProperties](./clearbuiltinproperties/)() | Borra y establece valores predeterminados para todas las propiedades builtIn. |
| virtual void [ClearCustomProperties](./clearcustomproperties/)() | Elimina todas las propiedades personalizadas. |
| virtual **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) | Comprueba la presencia de una propiedad personalizada con un nombre especificado. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica [Object.Equals](../../system/object/equals/) de C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Sólo para uso interno. |
| virtual [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() | Devuelve la plantilla de una aplicación. Leer [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() | Devuelve la versión de la aplicación. Solo lectura [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Author](./get_author/)() | Devuelve el autor de una presentación. Leer [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Category](./get_category/)() | Devuelve la categoría de una presentación. Leer [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Comments](./get_comments/)() | Devuelve los comentarios de una presentación. Leer [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Company](./get_company/)() | Devuelve la propiedad de la empresa. Leer [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() | Devuelve el estado del contenido de una presentación. Leer [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() | Devuelve el tipo de contenido de una presentación. Leer [System::String](../../system/string/). |
| virtual **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() | Devuelve el número de propiedades personalizadas realmente contenidas en una colección. Solo lectura **int32_t**. |
| virtual [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() | Devuelve la fecha en la que se creó una presentación. Los valores están en UTC. Leer [System::DateTime](../../system/datetime/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() | Indica la agrupación de partes del documento y el número de partes en cada grupo. Solo lectura [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| virtual **int32_t** [get_HiddenSlides](./get_hiddenslides/)() | Especifica el número de diapositivas ocultas en un documento de presentación. Solo lectura **int32_t**. |
| virtual [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() | Devuelve la propiedad del documento HyperlinkBase. Leer [System::String](../../system/string/). |
| virtual **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() | Especifica que uno o más hipervínculos en esta parte fueron actualizados exclusivamente en esta parte por un productor. El siguiente productor que abra este documento actualizará las relaciones de hipervínculos con los nuevos hipervínculos especificados en esta parte. Leer **bool**. |
| virtual [System::String](../../system/string/) [get_Keywords](./get_keywords/)() | Devuelve las palabras clave de una presentación. Leer [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() | Devuelve la fecha en que una presentación se imprimió por última vez. Leer [System::DateTime](../../system/datetime/). |
| virtual [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() | Devuelve el nombre de la última persona que modificó una presentación. Leer [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() | Devuelve la fecha en que una presentación fue modificada por última vez. Los valores están en UTC. Solo lectura en el caso de Presentation.DocumentProperties (porque se actualizará internamente durante el proceso de guardado del objeto [IPresentation](../ipresentation/)). Puede cambiarse mediante la instancia [DocumentProperties](../documentproperties/) devuelta por el método [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Consulte el ejemplo en el resumen del método [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| virtual **bool** [get_LinksUpToDate](./get_linksuptodate/)() | Indica si los hipervínculos en un documento están actualizados. Establezca este elemento a **true** para indicar que los hipervínculos están actualizados. Establezca este elemento a **false** para indicar que los hipervínculos están desactualizados. Leer **bool**. |
| virtual [System::String](../../system/string/) [get_Manager](./get_manager/)() | Devuelve la propiedad del gestor. Leer [System::String](../../system/string/). |
| virtual **int32_t** [get_MultimediaClips](./get_multimediaclips/)() | Especifica el número total de clips de sonido o video presentes en el documento. Solo lectura **int32_t**. |
| virtual [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() | Devuelve el nombre de la aplicación. Leer [System::String](../../system/string/). |
| virtual **int32_t** [get_Notes](./get_notes/)() | Especifica el número de diapositivas en una presentación que contienen notas. Solo lectura **int32_t**. |
| virtual **int32_t** [get_Paragraphs](./get_paragraphs/)() | Especifica el número total de párrafos encontrados en un documento si corresponde. Solo lectura **int32_t**. |
| virtual [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() | Devuelve el formato previsto de una presentación. Leer [System::String](../../system/string/). |
| virtual **int32_t** [get_RevisionNumber](./get_revisionnumber/)() | Devuelve el número de revisión de la presentación. Leer **int32_t**. |
| virtual **bool** [get_ScaleCrop](./get_scalecrop/)() | Indica el modo de visualización de la miniatura del documento. Establezca este elemento a **true** para habilitar el escalado de la miniatura del documento a la pantalla. Establezca este elemento a **false** para habilitar el recorte de la miniatura del documento para mostrar solo las secciones que se ajusten a la pantalla. Leer **bool**. |
| virtual **bool** [get_SharedDoc](./get_shareddoc/)() | Determina si la presentación se comparte entre varias personas. Leer **bool**. |
| virtual **int32_t** [get_Slides](./get_slides/)() | Especifica el número total de diapositivas en un documento de presentación. Solo lectura **int32_t**. |
| virtual [System::String](../../system/string/) [get_Subject](./get_subject/)() | Devuelve el asunto de una presentación. Leer [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Title](./get_title/)() | Devuelve el título de una presentación. Leer [System::String](../../system/string/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() | Especifica el título de cada parte del documento. Estas partes no son partes del documento sino representaciones conceptuales de secciones del documento. Solo lectura [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| virtual [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() | Tiempo total de edición de una presentación. Leer [System::TimeSpan](../../system/timespan/). |
| virtual **int32_t** [get_Words](./get_words/)() | Especifica el número total de palabras contenidas en un documento. Solo lectura **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) | Devuelve un nombre de propiedad personalizada en el índice especificado. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) | Obtiene un valor booleano con nombre de las propiedades personalizadas. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) | Obtiene un valor entero con nombre de las propiedades personalizadas. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) | Obtiene un valor DateTime con nombre de las propiedades personalizadas. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) | Obtiene un valor de cadena con nombre de las propiedades personalizadas. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) | Obtiene un valor float con nombre de las propiedades personalizadas. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) | Obtiene un valor double con nombre de las propiedades personalizadas. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() | Obtiene una matriz de etiquetas de sensibilidad de las propiedades personalizadas del documento (Metadatos del SDK de Microsoft Information Protection). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) | Devuelve la propiedad personalizada asociada a un nombre especificado. Leer [System::Object](../../system/object/). |
| virtual void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Establece la propiedad personalizada asociada a un nombre especificado. Escribir [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llálela directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción de copia en subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción de copia en subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| virtual **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) | Elimina una propiedad personalizada asociada a un nombre especificado. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas por el valor especificado. |
| virtual void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) | Establece la plantilla de una aplicación. Escribir [System::String](../../system/string/). |
| virtual void [set_Author](./set_author/)([System::String](../../system/string/)) | Establece el autor de una presentación. Escribir [System::String](../../system/string/). |
| virtual void [set_Category](./set_category/)([System::String](../../system/string/)) | Establece la categoría de una presentación. Escribir [System::String](../../system/string/). |
| virtual void [set_Comments](./set_comments/)([System::String](../../system/string/)) | Establece los comentarios de una presentación. Escribir [System::String](../../system/string/). |
| virtual void [set_Company](./set_company/)([System::String](../../system/string/)) | Establece la propiedad de la empresa. Escribir [System::String](../../system/string/). |
| virtual void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) | Establece el estado del contenido de una presentación. Escribir [System::String](../../system/string/). |
| virtual void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) | Establece el tipo de contenido de una presentación. Escribir [System::String](../../system/string/). |
| virtual void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) | Devuelve la fecha en que se creó una presentación. Los valores están en UTC. Escribir [System::DateTime](../../system/datetime/). |
| virtual void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) | Establece la propiedad del documento HyperlinkBase. Escribir [System::String](../../system/string/). |
| virtual void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) | Especifica que uno o más hipervínculos en esta parte fueron actualizados exclusivamente en esta parte por un productor. El siguiente productor que abra este documento actualizará las relaciones de hipervínculos con los nuevos hipervínculos especificados en esta parte. Escribir **bool**. |
| virtual void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) | Establece las palabras clave de una presentación. Escribir [System::String](../../system/string/). |
| virtual void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) | Devuelve la fecha en que una presentación se imprimió por última vez. Escribir [System::DateTime](../../system/datetime/). |
| virtual void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) | Establece el nombre de la última persona que modificó una presentación. Escribir [System::String](../../system/string/). |
| virtual void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) | Devuelve la fecha en que una presentación fue modificada por última vez. Los valores están en UTC. Solo lectura en el caso de Presentation.DocumentProperties (porque se actualizará internamente durante el proceso de guardado del objeto [IPresentation](../ipresentation/)). Puede cambiarse mediante la instancia [DocumentProperties](../documentproperties/) devuelta por el método [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Consulte el ejemplo en el resumen del método [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| virtual void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) | Indica si los hipervínculos en un documento están actualizados. Establezca este elemento a **true** para indicar que los hipervínculos están actualizados. Establezca este elemento a **false** para indicar que los hipervínculos están desactualizados. Escribir **bool**. |
| virtual void [set_Manager](./set_manager/)([System::String](../../system/string/)) | Establece la propiedad del gestor. Escribir [System::String](../../system/string/). |
| virtual void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) | Establece el nombre de la aplicación. Escribir [System::String](../../system/string/). |
| virtual void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) | Establece el formato previsto de una presentación. Escribir [System::String](../../system/string/). |
| virtual void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) | Establece el número de revisión de la presentación. Escribir **int32_t**. |
| virtual void [set_ScaleCrop](./set_scalecrop/)(**bool**) | Indica el modo de visualización de la miniatura del documento. Establezca este elemento a **true** para habilitar el escalado de la miniatura del documento a la pantalla. Establezca este elemento a **false** para habilitar el recorte de la miniatura del documento para mostrar solo las secciones que se ajusten a la pantalla. Escribir **bool**. |
| virtual void [set_SharedDoc](./set_shareddoc/)(**bool**) | Determina si la presentación se comparte entre varias personas. Escribir **bool**. |
| virtual void [set_Subject](./set_subject/)([System::String](../../system/string/)) | Establece el asunto de una presentación. Escribir [System::String](../../system/string/). |
| virtual void [set_Title](./set_title/)([System::String](../../system/string/)) | Establece el título de una presentación. Escribir [System::String](../../system/string/). |
| virtual void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) | Tiempo total de edición de una presentación. Escribir [System::TimeSpan](../../system/timespan/). |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) | Establece una propiedad personalizada booleana con nombre. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) | Establece una propiedad personalizada entera con nombre. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) | Establece una propiedad personalizada DateTime con nombre. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) | Establece una propiedad personalizada de cadena con nombre. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) | Establece una propiedad personalizada float con nombre. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) | Establece una propiedad personalizada double con nombre. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llálela directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [Object](../../system/object/)
* Espacio de nombres [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)