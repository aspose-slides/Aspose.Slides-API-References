---
title: XmlSchemaAttribute
second_title: Referencia de la API de Aspose.Slides para C++
description: Representa el elemento attribute del XML Schema según lo especificado por el World Wide Web Consortium (W3C). Los atributos proporcionan información adicional para otros elementos del documento. La etiqueta attribute se anida entre las etiquetas del elemento de un documento para el esquema. El documento XML muestra los atributos como elementos con nombre en la etiqueta de apertura de un elemento.
type: docs
weight: 170
url: /es/system.xml.schema/xmlschemaattribute/
---
## XmlSchemaAttribute clase

Representa el elemento **attribute** del XML [Schema](../) según lo especificado por el Consorcio World Wide [Web](../../system.web/) (W3C). Los atributos proporcionan información adicional para otros elementos del documento. La etiqueta de atributo se anida entre las etiquetas del elemento de un documento para el esquema. El documento XML muestra los atributos como elementos con nombre en la etiqueta de apertura de un elemento.

```cpp
class XmlSchemaAttribute : public System::Xml::Schema::XmlSchemaAnnotated
```

## Métodos

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaNs se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaNs se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | Devuelve la propiedad **annotation**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [get_AttributeSchemaType](./get_attributeschematype/)() | Devuelve un objeto [XmlSchemaSimpleType](../xmlschemasimpletype/) que representa el tipo del atributo basado en el valor [XmlSchemaAttribute::get_SchemaType](./get_schematype/) o [XmlSchemaAttribute::get_SchemaTypeName](./get_schematypename/) del atributo. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_AttributeType](./get_attributetype/)() | Devuelve el objeto basado en el valor [XmlSchemaAttribute::get_SchemaType](./get_schematype/) o [XmlSchemaAttribute::get_SchemaTypeName](./get_schematypename/) del atributo que contiene la interpretación posterior a la compilación del valor **AttributeType**. |
| [String](../../system/string/) [get_DefaultValue](./get_defaultvalue/)() | Devuelve el valor predeterminado del atributo. |
| [String](../../system/string/) [get_FixedValue](./get_fixedvalue/)() | Devuelve el valor fijo del atributo. |
| [XmlSchemaForm](../xmlschemaform/) [get_Form](./get_form/)() | Devuelve la forma del atributo. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | Devuelve el identificador de cadena. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Devuelve el número de línea en el archivo al que se refiere el elemento **schema**. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Devuelve la posición de línea en el archivo al que se refiere el elemento **schema**. |
| [String](../../system/string/) [get_Name](./get_name/)() | Devuelve el nombre del atributo. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Devuelve el XmlSerializerNamespaces a usar con este objeto de esquema. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Devuelve el padre de este [XmlSchemaObject](../xmlschemaobject/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](./get_qualifiedname/)() | Devuelve el nombre calificado del atributo. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_RefName](./get_refname/)() | Devuelve el nombre de un atributo declarado en este esquema (o en otro esquema indicado por el espacio de nombres especificado). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [get_SchemaType](./get_schematype/)() | Devuelve el tipo de atributo a un tipo simple. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SchemaTypeName](./get_schematypename/)() | Devuelve el nombre del tipo simple definido en este esquema (o en otro esquema indicado por el espacio de nombres especificado). |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Devuelve la ubicación de origen del archivo que cargó el esquema. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | Devuelve los atributos calificados que no pertenecen al espacio de nombres objetivo del esquema actual. |
| [XmlSchemaUse](../xmlschemause/) [get_Use](./get_use/)() | Devuelve información sobre cómo se utiliza el atributo. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. No copia nada, realmente, sólo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. No copia nada, realmente, sólo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | Establece la propiedad **annotation**. |
| void [set_DefaultValue](./set_defaultvalue/)(const [String](../../system/string/)\&) | Establece el valor predeterminado del atributo. |
| void [set_FixedValue](./set_fixedvalue/)(const [String](../../system/string/)\&) | Establece el valor fijo del atributo. |
| void [set_Form](./set_form/)([XmlSchemaForm](../xmlschemaform/)) | Establece la forma del atributo. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | Establece el identificador de cadena. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Establece el número de línea en el archivo al que se refiere el elemento **schema**. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Establece la posición de línea en el archivo al que se refiere el elemento **schema**. |
| void [set_Name](./set_name/)(const [String](../../system/string/)\&) | Establece el nombre del atributo. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Establece el XmlSerializerNamespaces a utilizar con este objeto de esquema. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Establece el padre de este [XmlSchemaObject](../xmlschemaobject/). |
| void [set_RefName](./set_refname/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Establece el nombre de un atributo declarado en este esquema (o en otro esquema indicado por el espacio de nombres especificado). |
| void [set_SchemaType](./set_schematype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\>\&) | Establece el tipo de atributo a un tipo simple. |
| void [set_SchemaTypeName](./set_schematypename/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Establece el nombre del tipo simple definido en este esquema (o en otro esquema indicado por el espacio de nombres especificado). |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Establece la ubicación de origen del archivo que cargó el esquema. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Establece los atributos calificados que no pertenecen al espacio de nombres objetivo del esquema actual. |
| void [set_Use](./set_use/)([XmlSchemaUse](../xmlschemause/)) | Establece información sobre cómo se usa el atributo. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe ser llamado directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe ser llamado directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe ser llamado directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe ser llamado directamente; en su lugar, use punteros inteligentes o ThisProtector. |
|  [XmlSchemaAttribute](./xmlschemaattribute/)() | Inicializa una nueva instancia de la clase [XmlSchemaAttribute](./). |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Inicializa una nueva instancia de la clase [XmlSchemaObject](../xmlschemaobject/). |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Definiciones de tipos

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |

## Observaciones

Los objetos de esta clase sólo deben ser asignados usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Véase también

* Clase [XmlSchemaAnnotated](../xmlschemaannotated/)
* Espacio de nombres [System::Xml::Schema](../)
* Biblioteca [Aspose.Slides](../../)