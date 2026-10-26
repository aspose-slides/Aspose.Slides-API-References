---
title: DocumentProperties
second_title: Referencia de API de Aspose.Slides para C++
description: Representa propiedades de una presentación.
type: docs
weight: 794
url: /es/aspose.slides/documentproperties/
---
## DocumentProperties clase

Representa propiedades de una presentación.

```cpp
class DocumentProperties : public Aspose::Slides::IDocumentProperties,
                           public Aspose::Slides::IGenericCloneable<System::SharedPtr<Aspose::Slides::IDocumentProperties>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| void [ClearBuiltInProperties](./clearbuiltinproperties/)() override | Borra y establece valores predeterminados para todas las propiedades integradas. |
| void [ClearCustomProperties](./clearcustomproperties/)() override | Elimina todas las propiedades personalizadas. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](./clone/)() override | Clona el objeto actual. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [CloneT](./clonet/)() override | Clona el objeto actual. |
| **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) override | Comprueba la presencia de una propiedad personalizada con un nombre especificado. |
| [DocumentProperties](./documentproperties/)() | Inicializa una nueva instancia de la clase [DocumentProperties](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() override | Devuelve la plantilla de una aplicación. Lea [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() override | Devuelve la versión de la aplicación. Solo lectura [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Author](./get_author/)() override | Devuelve el autor de una presentación. Lea [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Category](./get_category/)() override | Devuelve la categoría de una presentación. Lea [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Comments](./get_comments/)() override | Devuelve los comentarios de una presentación. Lea [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Company](./get_company/)() override | Devuelve la propiedad de la empresa. Lea [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() override | Devuelve el estado del contenido de una presentación. Lea [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() override | Devuelve el tipo de contenido de una presentación. Lea [System::String](../../system/string/). |
| **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() override | Devuelve el número de propiedades personalizadas realmente contenidas en una colección. Solo lectura **int32_t**. |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() override | Devuelve la fecha en que se creó una presentación. Los valores están en UTC. Lea [System::DateTime](../../system/datetime/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() override | Indica la agrupación de partes del documento y el número de partes en cada grupo. Solo lectura [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| **int32_t** [get_HiddenSlides](./get_hiddenslides/)() override | Devuelve el número de diapositivas ocultas en un documento de presentación. Solo lectura **int32_t**. |
| [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() override | Devuelve la propiedad de documento HyperlinkBase. Lea [System::String](../../system/string/). |
| **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() override | Especifica que uno o más hipervínculos en esta parte fueron actualizados exclusivamente en esta parte por un productor. El siguiente productor que abra este documento deberá actualizar las relaciones de hipervínculos con los nuevos hipervínculos especificados en esta parte. Lea **bool**. |
| [System::String](../../system/string/) [get_Keywords](./get_keywords/)() override | Devuelve las palabras clave de una presentación. Lea [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() override | Devuelve la fecha en que una presentación se imprimió por última vez. Lea [System::DateTime](../../system/datetime/). |
| [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() override | Devuelve el nombre de la última persona que modificó una presentación. Lea [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() override | Devuelve la fecha en que una presentación fue modificada por última vez. Los valores están en UTC. Solo lectura en caso de [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (porque se actualizará internamente mientras el proceso de guardado del objeto [IPresentation](../ipresentation/)). Puede modificarse a través de la instancia [DocumentProperties](./) devuelta por el método [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Consulte el ejemplo en el resumen del método [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| **bool** [get_LinksUpToDate](./get_linksuptodate/)() override | Indica si los hipervínculos en un documento están actualizados. Establezca este elemento en **true** para indicar que los hipervínculos están actualizados. Establezca este elemento en **false** para indicar que los hipervínculos están desactualizados. Lea **bool**. |
| [System::String](../../system/string/) [get_Manager](./get_manager/)() override | Devuelve la propiedad del gestor. Lea [System::String](../../system/string/). |
| **int32_t** [get_MultimediaClips](./get_multimediaclips/)() override | Devuelve el número total de clips de sonido o video presentes en el documento. Solo lectura **int32_t**. |
| [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() override | Devuelve el nombre de la aplicación. Lea [System::String](../../system/string/). |
| **int32_t** [get_Notes](./get_notes/)() override | Devuelve el número de diapositivas en una presentación que contienen notas. Solo lectura **int32_t**. |
| **int32_t** [get_Paragraphs](./get_paragraphs/)() override | Devuelve el número total de párrafos encontrados en un documento, si corresponde. Solo lectura **int32_t**. |
| [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() override | Devuelve el formato previsto de una presentación. Lea [System::String](../../system/string/). |
| **int32_t** [get_RevisionNumber](./get_revisionnumber/)() override | Devuelve el número de revisión de la presentación. Lea **int32_t**. |
| **bool** [get_ScaleCrop](./get_scalecrop/)() override | Indica el modo de visualización de la miniatura del documento. Establezca este elemento en **true** para habilitar el escalado de la miniatura del documento a la pantalla. Establezca este elemento en **false** para habilitar el recorte de la miniatura del documento para mostrar solo secciones que se ajusten a la pantalla. Lea **bool**. |
| **bool** [get_SharedDoc](./get_shareddoc/)() override | Determina si la presentación se comparte entre varias personas. Lea **bool**. |
| **int32_t** [get_Slides](./get_slides/)() override | Devuelve el número total de diapositivas en un documento de presentación. Solo lectura **int32_t**. |
| [System::String](../../system/string/) [get_Subject](./get_subject/)() override | Devuelve el asunto de una presentación. Lea [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Title](./get_title/)() override | Devuelve el título de una presentación. Lea [System::String](../../system/string/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() override | Especifica el título de cada parte del documento. Estas partes no son partes del documento sino representaciones conceptuales de secciones del documento. Solo lectura [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() override | Tiempo total de edición de una presentación. Lea [System::TimeSpan](../../system/timespan/). |
| **int32_t** [get_Words](./get_words/)() override | Devuelve el número total de palabras contenidas en un documento. Solo lectura **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) override | Devuelve un nombre de propiedad personalizada en el índice especificado. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) override | Obtiene un valor booleano nombrado de las propiedades personalizadas. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) override | Obtiene un valor entero nombrado de las propiedades personalizadas. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) override | Obtiene un valor DateTime nombrado de las propiedades personalizadas. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) override | Obtiene un valor de cadena nombrado de las propiedades personalizadas. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) override | Obtiene un valor float nombrado de las propiedades personalizadas. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) override | Obtiene un valor double nombrado de las propiedades personalizadas. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() override | Obtiene una matriz de etiquetas de sensibilidad de las propiedades personalizadas del documento (Metadatos del SDK de Microsoft Information Protection). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo de la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) override | Devuelve la propiedad personalizada asociada a un nombre especificado. Lea [System::Object](../../system/object/). |
| void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Establece la propiedad personalizada asociada a un nombre especificado. Escritura [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo del operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo del método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
| [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) override | Elimina una propiedad personalizada asociada a un nombre especificado. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) override | Establece la plantilla de una aplicación. Escritura [System::String](../../system/string/). |
| void [set_Author](./set_author/)([System::String](../../system/string/)) override | Establece el autor de una presentación. Escritura [System::String](../../system/string/). |
| void [set_Category](./set_category/)([System::String](../../system/string/)) override | Establece la categoría de una presentación. Escritura [System::String](../../system/string/). |
| void [set_Comments](./set_comments/)([System::String](../../system/string/)) override | Establece los comentarios de una presentación. Escritura [System::String](../../system/string/). |
| void [set_Company](./set_company/)([System::String](../../system/string/)) override | Establece la propiedad de la empresa. Escritura [System::String](../../system/string/). |
| void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) override | Establece el estado del contenido de una presentación. Escritura [System::String](../../system/string/). |
| void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) override | Establece el tipo de contenido de una presentación. Escritura [System::String](../../system/string/). |
| void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) override | Devuelve la fecha en que se creó una presentación. Los valores están en UTC. Escritura [System::DateTime](../../system/datetime/). |
| void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) override | Establece la propiedad de documento HyperlinkBase. Escritura [System::String](../../system/string/). |
| void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) override | Especifica que uno o más hipervínculos en esta parte fueron actualizados exclusivamente en esta parte por un productor. El siguiente productor que abra este documento deberá actualizar las relaciones de hipervínculos con los nuevos hipervínculos especificados en esta parte. Escritura **bool**. |
| void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) override | Establece las palabras clave de una presentación. Escritura [System::String](../../system/string/). |
| void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) override | Devuelve la fecha en que una presentación se imprimió por última vez. Escritura [System::DateTime](../../system/datetime/). |
| void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) override | Establece el nombre de la última persona que modificó una presentación. Escritura [System::String](../../system/string/). |
| void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) override | Devuelve la fecha en que una presentación fue modificada por última vez. Los valores están en UTC. Solo lectura en caso de [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (porque se actualizará internamente mientras el proceso de guardado del objeto [IPresentation](../ipresentation/)). Puede modificarse a través de la instancia [DocumentProperties](./) devuelta por el método [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Consulte el ejemplo en el resumen del método [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) override | Indica si los hipervínculos en un documento están actualizados. Establezca este elemento en **true** para indicar que los hipervínculos están actualizados. Establezca este elemento en **false** para indicar que los hipervínculos están desactualizados. Escritura **bool**. |
| void [set_Manager](./set_manager/)([System::String](../../system/string/)) override | Establece la propiedad del gestor. Escritura [System::String](../../system/string/). |
| void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) override | Establece el nombre de la aplicación. Escritura [System::String](../../system/string/). |
| void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) override | Establece el formato previsto de una presentación. Escritura [System::String](../../system/string/). |
| void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) override | Establece el número de revisión de la presentación. Escritura **int32_t**. |
| void [set_ScaleCrop](./set_scalecrop/)(**bool**) override | Indica el modo de visualización de la miniatura del documento. Establezca este elemento en **true** para habilitar el escalado de la miniatura del documento a la pantalla. Establezca este elemento en **false** para habilitar el recorte de la miniatura del documento para mostrar solo secciones que se ajusten a la pantalla. Escritura **bool**. |
| void [set_SharedDoc](./set_shareddoc/)(**bool**) override | Determina si la presentación se comparte entre varias personas. Escritura **bool**. |
| void [set_Subject](./set_subject/)([System::String](../../system/string/)) override | Establece el asunto de una presentación. Escritura [System::String](../../system/string/). |
| void [set_Title](./set_title/)([System::String](../../system/string/)) override | Establece el título de una presentación. Escritura [System::String](../../system/string/). |
| void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) override | Tiempo total de edición de una presentación. Escritura [System::TimeSpan](../../system/timespan/). |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) override | Establece una propiedad personalizada booleana nombrada. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) override | Establece una propiedad personalizada entera nombrada. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) override | Establece una propiedad personalizada DateTime nombrada. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) override | Establece una propiedad personalizada de cadena nombrada. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) override | Establece una propiedad personalizada float nombrada. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) override | Establece una propiedad personalizada double nombrada. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla a un puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debería llamarse directamente; use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debería llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debería llamarse directamente; use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debería llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Comentarios

El siguiente ejemplo muestra cómo acceder a las propiedades integradas de PowerPoint [Presentation](../presentation/).
```cpp
// Instanciar la clase Presentation que representa la presentación
auto pres = System::MakeObject<Presentation>(dataDir + u"AccessBuiltin Properties.pptx");

// Create a reference to IDocumentProperties object associated with Presentation
System::SharedPtr<IDocumentProperties> documentProperties = pres->get_DocumentProperties();
// Display the builtin properties
System::Console::WriteLine(System::String(u"Category : ") + documentProperties->get_Category());
System::Console::WriteLine(System::String(u"Current Status : ") + documentProperties->get_ContentStatus());
System::Console::WriteLine(System::String(u"Creation Date : ") + documentProperties->get_CreatedTime());
System::Console::WriteLine(System::String(u"Author : ") + documentProperties->get_Author());
System::Console::WriteLine(System::String(u"Description : ") + documentProperties->get_Comments());
```
El siguiente ejemplo muestra cómo modificar las propiedades integradas de PowerPoint [Presentation](../presentation/).
```cpp
// Instanciar la clase Presentation que representa la Presentation
auto presentation = System::MakeObject<Presentation>(dataDir + u"ModifyBuiltinProperties.pptx");

// Crear una referencia al objeto IDocumentProperties asociado a Presentation
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();
// Establecer las propiedades integradas
documentProperties->set_Author(u"Aspose.Slides for .NET");
documentProperties->set_Title(u"Modifying Presentation Properties");
documentProperties->set_Subject(u"Aspose Subject");
// Guardar la presentación en un archivo
presentation->Save(u"DocumentProperties_out.pptx", SaveFormat::Pptx);
```

## Ver también

* Clase [IDocumentProperties](../idocumentproperties/)
* Clase [IGenericCloneable](../igenericcloneable/)
* Espacio de nombres [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)