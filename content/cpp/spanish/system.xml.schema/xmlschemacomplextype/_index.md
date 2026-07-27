---
title: XmlSchemaComplexType
second_title: Referencia de la API de Aspose.Slides para C++
description: Representa el elemento complexType del esquema XML según lo especificado por el Consorcio World Wide Web (W3C). Esta clase define un tipo complejo que determina el conjunto de atributos y el contenido de un elemento.
type: docs
weight: 300
url: /es/system.xml.schema/xmlschemacomplextype/
---
## XmlSchemaComplexType clase

Representa el elemento **complexType** de XML [Schema](../) según lo especificado por el consorcio World Wide [Web](../../system.web/) (W3C). Esta clase define un tipo complejo que determina el conjunto de atributos y el contenido de un elemento.

```cpp
class XmlSchemaComplexType : public System::Xml::Schema::XmlSchemaType
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo de C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo de C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | Devuelve la propiedad **annotation**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\> [get_AnyAttribute](./get_anyattribute/)() | Devuelve el valor del componente [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) del tipo complejo. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Attributes](./get_attributes/)() | Devuelve la colección de atributos del tipo complejo. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_AttributeUses](./get_attributeuses/)() | Devuelve la colección de todos los atributos compilados de este tipo complejo y sus tipos base. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\> [get_AttributeWildcard](./get_attributewildcard/)() | Devuelve el valor posterior a la compilación para **anyAttribute** de este tipo complejo y sus tipos base. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_BaseSchemaType](../xmlschematype/get_baseschematype/)() | Devuelve el tipo de objeto posterior a la compilación o el tipo de datos incorporado del Lenguaje de Definición XML [Schema](../) (XSD), elemento simpleType o elemento complexType. Este es un valor del conjunto de información posterior a la compilación del esquema. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_BaseXmlSchemaType](../xmlschematype/get_basexmlschematype/)() | Devuelve el valor posterior a la compilación para el tipo base de este tipo de esquema. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Block](./get_block/)() | Devuelve el atributo **block**. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockResolved](./get_blockresolved/)() | Devuelve el valor después de que el tipo haya sido compilado al conjunto de información (infoset) posterior a la validación del esquema. Este valor indica cómo se aplica el tipo cuando se usa **xsi:type** en el documento de instancia. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaContentModel](../xmlschemacontentmodel/)\> [get_ContentModel](./get_contentmodel/)() | Devuelve el [XmlSchemaContentModel](../xmlschemacontentmodel/) posterior a la compilación de este tipo complejo. |
| [XmlSchemaContentType](../xmlschemacontenttype/) [get_ContentType](./get_contenttype/)() | Devuelve el modelo de contenido del tipo complejo que contiene el valor posterior a la compilación. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\> [get_ContentTypeParticle](./get_contenttypeparticle/)() | Devuelve la partícula que contiene el valor posterior a la compilación de la partícula [XmlSchemaComplexType::get_ContentType](./get_contenttype/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaDatatype](../xmlschemadatatype/)\> [get_Datatype](../xmlschematype/get_datatype/)() | Devuelve el valor posterior a la compilación para el tipo de datos del tipo complejo. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_DerivedBy](../xmlschematype/get_derivedby/)() | Devuelve la información posterior a la compilación sobre cómo se derivó este elemento de su tipo base. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](../xmlschematype/get_final/)() | Devuelve el atributo final de la derivación del tipo que indica si se permiten más derivaciones. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](../xmlschematype/get_finalresolved/)() | Devuelve la interpretación posterior a la compilación del valor [XmlSchemaType::get_Final](../xmlschematype/get_final/). |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | Devuelve el identificador de cadena. |
| **bool** [get_IsAbstract](./get_isabstract/)() | Devuelve la información que determina si el elemento **complexType** puede usarse en el documento de instancia. |
| **bool** [get_IsMixed](./get_ismixed/)() override | Devuelve información que determina si el tipo complejo tiene un modelo de contenido mixto (marcado dentro del contenido). |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Devuelve el número de línea en el archivo al que hace referencia el elemento **schema**. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Devuelve la posición de línea en el archivo al que hace referencia el elemento **schema**. |
| [String](../../system/string/) [get_Name](../xmlschematype/get_name/)() | Devuelve el nombre del tipo. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Devuelve los XmlSerializerNamespaces a usar con este objeto de esquema. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Devuelve el padre de este [XmlSchemaObject](../xmlschemaobject/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\> [get_Particle](./get_particle/)() | Devuelve el tipo de compositor como una de las clases [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) o [XmlSchemaSequence](../xmlschemasequence/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](../xmlschematype/get_qualifiedname/)() | Devuelve el nombre calificado para el tipo construido a partir del atributo **Name** de este tipo. Este es un valor posterior a la compilación del esquema. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Devuelve la ubicación de origen del archivo que cargó el esquema. |
| [XmlTypeCode](../xmltypecode/) [get_TypeCode](../xmlschematype/get_typecode/)() | Devuelve el XmlTypeCode del tipo. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | Devuelve los atributos calificados que no pertenecen al espacio de nombres objetivo del esquema actual. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](./)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)([XmlTypeCode](../xmltypecode/)) | Devuelve un [XmlSchemaComplexType](./) que representa el tipo complejo incorporado del tipo complejo especificado. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](./)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Devuelve un [XmlSchemaComplexType](./) que representa el tipo complejo incorporado del tipo complejo especificado por nombre calificado. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Devuelve un [XmlSchemaSimpleType](../xmlschemasimpletype/) que representa el tipo simple incorporado del tipo simple especificado por el nombre calificado. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)([XmlTypeCode](../xmltypecode/)) | Devuelve un [XmlSchemaSimpleType](../xmlschemasimpletype/) que representa el tipo simple incorporado del tipo simple especificado. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Analogo de la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Analogo del operador C# 'is'. |
| static **bool** [IsDerivedFrom](../xmlschematype/isderivedfrom/)([SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&, [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Devuelve un valor que indica si el tipo de esquema derivado especificado se deriva del tipo base de esquema especificado. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite la clonación de tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias en subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias en subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | Establece la propiedad **annotation**. |
| void [set_AnyAttribute](./set_anyattribute/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\>\&) | Establece el valor para el componente [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) del tipo complejo. |
| void [set_Block](./set_block/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Establece el atributo **block**. |
| void [set_ContentModel](./set_contentmodel/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaContentModel](../xmlschemacontentmodel/)\>\&) | Establece el [XmlSchemaContentModel](../xmlschemacontentmodel/) posterior a la compilación de este tipo complejo. |
| void [set_Final](../xmlschematype/set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Establece el atributo final de la derivación del tipo que indica si se permiten más derivaciones. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | Establece el identificador de cadena. |
| void [set_IsAbstract](./set_isabstract/)(**bool**) | Establece la información que determina si el elemento **complexType** puede usarse en el documento de instancia. |
| void [set_IsMixed](./set_ismixed/)(**bool**) override | Establece la información que determina si el tipo complejo tiene un modelo de contenido mixto (marcado dentro del contenido). |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Establece el número de línea en el archivo al que hace referencia el elemento **schema**. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Establece la posición de línea en el archivo al que hace referencia el elemento **schema**. |
| void [set_Name](../xmlschematype/set_name/)(const [String](../../system/string/)\&) | Establece el nombre del tipo. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Establece los XmlSerializerNamespaces a usar con este objeto de esquema. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Establece el padre de este [XmlSchemaObject](../xmlschemaobject/). |
| void [set_Particle](./set_particle/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\>\&) | Establece el tipo de compositor como una de las clases [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) o [XmlSchemaSequence](../xmlschemasequence/). |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Establece la ubicación de origen del archivo que cargó el esquema. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Establece los atributos calificados que no pertenecen al espacio de nombres objetivo del esquema actual. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores al modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
|  [XmlSchemaComplexType](./xmlschemacomplextype/)() | Inicializa una nueva instancia de la clase [XmlSchemaComplexType](./). |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Inicializa una nueva instancia de la clase [XmlSchemaObject](../xmlschemaobject/). |
|  [XmlSchemaType](../xmlschematype/xmlschematype/)() | Inicializa una nueva instancia de la clase [XmlSchemaType](../xmlschematype/). |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Definiciones de tipo

| Definición de tipo | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para puntero compartido a una instancia de esta clase. |

## Observaciones

Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila ni utilizando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. 

## Ver también

* Clase [XmlSchemaType](../xmlschematype/)
* Espacio de nombres [System::Xml::Schema](../)
* Biblioteca [Aspose.Slides](../../)