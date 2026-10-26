---
title: XmlReaderSettings
second_title: Referencia de la API de Aspose.Slides para C++
description: "Especifica un conjunto de características que se admiten en el objeto XmlReader creado por el método XmlReader::Create."
type: docs
weight: 443
url: /es/system.xml/xmlreadersettings/
---
## XmlReaderSettings clase

Especifica un conjunto de características que se admiten en el [XmlReader](../xmlreader/) objeto creado por el método [XmlReader::Create](../xmlreader/create/).

```cpp
class XmlReaderSettings : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| void [CheckReadOnly](./checkreadonly/)(const [String](../../system/string/)\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](./)\> [Clone](./clone/)() | Crea una copia de la instancia [XmlReaderSettings](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | Devuelve un valor que indica si se debe hacer la verificación de caracteres. |
| **bool** [get_CloseInput](./get_closeinput/)() | Devuelve un valor que indica si el flujo subyacente o TextReader debe cerrarse cuando se cierra el lector. |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | Devuelve el nivel de conformidad que el [XmlReader](../xmlreader/) cumplirá. |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | Devuelve un valor que determina el procesamiento de DTDs. |
| **bool** [get_IgnoreComments](./get_ignorecomments/)() | Devuelve un valor que indica si se deben ignorar los comentarios. |
| **bool** [get_IgnoreProcessingInstructions](./get_ignoreprocessinginstructions/)() | Devuelve un valor que indica si se deben ignorar las instrucciones de procesamiento. |
| **bool** [get_IgnoreWhitespace](./get_ignorewhitespace/)() | Devuelve un valor que indica si se debe ignorar el espacio en blanco insignificante. |
| **int32_t** [get_LineNumberOffset](./get_linenumberoffset/)() | Devuelve el desplazamiento del número de línea del objeto [XmlReader](../xmlreader/). |
| **int32_t** [get_LinePositionOffset](./get_linepositionoffset/)() | Devuelve el desplazamiento de la posición de línea del objeto [XmlReader](../xmlreader/). |
| **int64_t** [get_MaxCharactersFromEntities](./get_maxcharactersfromentities/)() | Devuelve un valor que indica el número máximo permitido de caracteres en un documento que resultan de expandir entidades. |
| **int64_t** [get_MaxCharactersInDocument](./get_maxcharactersindocument/)() | Devuelve un valor que indica el número máximo permitido de caracteres en un documento XML. Un valor cero (0) significa que no hay límites en el tamaño del documento XML. Un valor distinto de cero especifica el tamaño máximo, en caracteres. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | Devuelve el [XmlNameTable](../xmlnametable/) utilizado para comparaciones de cadenas atomizadas. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | Devuelve un valor que indica si se debe prohibir el procesamiento de definiciones de tipo de documento (DTD). |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\> [get_Schemas](./get_schemas/)() | Devuelve el XmlSchemaSet a usar al realizar la validación de esquema. |
| [Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/) [get_ValidationFlags](./get_validationflags/)() | Devuelve un valor que indica la configuración de validación de esquema. Esta configuración se aplica a los objetos [XmlReader](../xmlreader/) que validan esquemas (el valor [XmlReaderSettings::get_ValidationType](./get_validationtype/) es [ValidationType::Schema](../validationtype/)). |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | Devuelve un valor que indica si el [XmlReader](../xmlreader/) realizará validación o asignación de tipo al leer. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. No copia nada, en realidad, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. No copia nada, en realidad, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [Reset](./reset/)() | Restablece los miembros de la clase de configuración a sus valores predeterminados. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | Establece un valor que indica si se debe hacer la verificación de caracteres. |
| void [set_CloseInput](./set_closeinput/)(**bool**) | Establece un valor que indica si el flujo subyacente o TextReader debe cerrarse cuando se cierra el lector. |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | Establece el nivel de conformidad que el [XmlReader](../xmlreader/) cumplirá. |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | Establece un valor que determina el procesamiento de DTD. |
| void [set_IgnoreComments](./set_ignorecomments/)(**bool**) | Establece un valor que indica si se deben ignorar los comentarios. |
| void [set_IgnoreProcessingInstructions](./set_ignoreprocessinginstructions/)(**bool**) | Establece un valor que indica si se deben ignorar las instrucciones de procesamiento. |
| void [set_IgnoreWhitespace](./set_ignorewhitespace/)(**bool**) | Establece un valor que indica si se debe ignorar el espacio en blanco insignificante. |
| void [set_LineNumberOffset](./set_linenumberoffset/)(**int32_t**) | Establece el desplazamiento del número de línea del objeto [XmlReader](../xmlreader/). |
| void [set_LinePositionOffset](./set_linepositionoffset/)(**int32_t**) | Establece el desplazamiento de la posición de línea del objeto [XmlReader](../xmlreader/). |
| void [set_MaxCharactersFromEntities](./set_maxcharactersfromentities/)(**int64_t**) | Establece un valor que indica el número máximo permitido de caracteres en un documento que resultan de expandir entidades. |
| void [set_MaxCharactersInDocument](./set_maxcharactersindocument/)(**int64_t**) | Establece un valor que indica el número máximo permitido de caracteres en un documento XML. Un valor cero (0) significa que no hay límites en el tamaño del documento XML. Un valor distinto de cero especifica el tamaño máximo, en caracteres. |
| void [set_NameTable](./set_nametable/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Establece el [XmlNameTable](../xmlnametable/) utilizado para comparaciones de cadenas atomizadas. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | Establece un valor que indica si se debe prohibir el procesamiento de definiciones de tipo de documento (DTD). |
| void [set_Schemas](./set_schemas/)(const [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>\&) | Establece el XmlSchemaSet a usar al realizar la validación de esquema. |
| void [set_ValidationFlags](./set_validationflags/)([Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/)) | Establece un valor que indica la configuración de validación de esquema. Esta configuración se aplica a los objetos [XmlReader](../xmlreader/) que validan esquemas (el valor [XmlReaderSettings::get_ValidationType](./get_validationtype/) es [ValidationType::Schema](../validationtype/)). |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | Establece un valor que indica si el [XmlReader](../xmlreader/) realizará validación o asignación de tipo al leer. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Establece el [XmlResolver](../xmlresolver/) utilizado para acceder a documentos externos. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../../system/lockcontext/). |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Añade un controlador de eventos que ocurre cuando el lector encuentra errores de validación. |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Elimina un controlador de eventos que ocurre cuando el lector encuentra errores de validación. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
|  [XmlReaderSettings](./xmlreadersettings/)() | Inicializa una nueva instancia de la clase [XmlReaderSettings](./). |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Definiciones de tipo

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para puntero compartido a una instancia de esta clase. |

## Observaciones

Los objetos de esta clase solo deben asignarse utilizando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila ni utilizando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y utilice ese puntero para pasarlo a funciones como argumento. 

## Véase también

* Clase [Object](../../system/object/)
* Espacio de nombres [System::Xml](../)
* Biblioteca [Aspose.Slides](../../)