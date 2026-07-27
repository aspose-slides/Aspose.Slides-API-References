---
title: XmlValidatingReader
second_title: Referencia de la API de Aspose.Slides para C++
description: Representa un lector que proporciona validación de definición de tipo de documento (DTD), esquema XML-Data Reduced (XDR) y del lenguaje de definición de esquemas XML (XSD).
type: docs
weight: 547
url: /es/system.xml/xmlvalidatingreader/
---
## XmlValidatingReader clase

Representa un lector que proporciona definición de tipo de documento (DTD), esquema XML-Data Reduced (XDR) y validación del lenguaje de definición XML [Schema](../../system.xml.schema/) (XSD).

```cpp
class XmlValidatingReader : public System::Xml::XmlReader,
                            public System::Xml::IXmlLineInfo,
                            public System::Xml::IXmlNamespaceResolver
```

## Métodos

| Método | Descripción |
| --- | --- |
| void [Close](./close/)() override | Cambia el [XmlReader::get_ReadState](../xmlreader/get_readstate/) a Closed. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | Crea una nueva instancia de [XmlReader](../xmlreader/) con el URI especificado. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Crea una nueva instancia de [XmlReader](../xmlreader/) usando el URI y la configuración especificados. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Crea una nueva instancia de [XmlReader](../xmlreader/) usando el URI, la configuración y la información de contexto especificados para el análisis. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Crea una nueva instancia de [XmlReader](../xmlreader/) usando el flujo especificado con la configuración predeterminada. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Crea una nueva instancia de [XmlReader](../xmlreader/) con el flujo y la configuración especificados. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Crea una nueva instancia de [XmlReader](../xmlreader/) usando el flujo especificado, el URI base y la configuración. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Crea una nueva instancia de [XmlReader](../xmlreader/) usando el flujo, la configuración y la información de contexto especificados para el análisis. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Crea una nueva instancia de [XmlReader](../xmlreader/) usando el lector de texto especificado. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Crea una nueva instancia de [XmlReader](../xmlreader/) usando el lector de texto y la configuración especificados. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Crea una nueva instancia de [XmlReader](../xmlreader/) usando el lector de texto, la configuración y el URI base especificados. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Crea una nueva instancia de [XmlReader](../xmlreader/) usando el lector de texto, la configuración y la información de contexto especificados para el análisis. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Crea una nueva instancia de [XmlReader](../xmlreader/) usando el lector XML y la configuración especificados. |
| void [Dispose](../xmlreader/dispose/)() override | Libera todos los recursos utilizados por la instancia actual de la clase [XmlReader](../xmlreader/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica [Object.Equals](../../system/object/equals/) de C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Devuelve el número de atributos del nodo actual. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Devuelve el URI base del nodo actual. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Devuelve un valor que indica si [XmlValidatingReader](./) implementa los métodos de lectura de contenido binario. |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | Devuelve un valor que indica si [XmlReader](../xmlreader/) implementa el método [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/). |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Devuelve un valor que indica si este lector puede analizar y resolver entidades. |
| **int32_t** [get_Depth](./get_depth/)() override | Devuelve la profundidad del nodo actual en el documento XML. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Devuelve el atributo de codificación del documento. |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | Devuelve un valor que especifica cómo el lector maneja las entidades. |
| **bool** [get_EOF](./get_eof/)() override | Devuelve un valor que indica si el lector está posicionado al final del flujo. |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | Devuelve un valor que indica si el nodo actual tiene atributos. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Devuelve un valor que indica si el nodo actual puede tener un [XmlValidatingReader::get_Value](./get_value/) distinto de [String::Empty](../../system/string/empty/). |
| **bool** [get_IsDefault](./get_isdefault/)() override | Devuelve un valor que indica si el nodo actual es un atributo generado a partir del valor predeterminado definido en la definición de tipo de documento (DTD) o esquema. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Devuelve un valor que indica si el nodo actual es un elemento vacío (por ejemplo, **<MyElement/>**). |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | Devuelve el número de línea actual. |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | Devuelve la posición de línea actual. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Devuelve el nombre local del nodo actual. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Devuelve el nombre calificado del nodo actual. |
| **bool** [get_Namespaces](./get_namespaces/)() | Devuelve un valor que indica si se debe habilitar el soporte de espacios de nombres. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Devuelve el Identificador Uniforme de Recurso (URI) del espacio de nombres (según lo definido en la especificación de espacios de nombres del Consorcio World Wide [Web](../../system.web/) (W3C)) del nodo donde está posicionado el lector. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Devuelve el [XmlNameTable](../xmlnametable/) asociado con esta implementación. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Devuelve el tipo del nodo actual. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Devuelve el prefijo del espacio de nombres asociado al nodo actual. |
| char16_t [get_QuoteChar](./get_quotechar/)() override | Devuelve el carácter de comilla usado para encerrar el valor de un nodo de atributo. |
| [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [get_Reader](./get_reader/)() | Devuelve el [XmlReader](../xmlreader/) usado para construir este [XmlValidatingReader](./). |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Devuelve el estado del lector. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | Devuelve la información del esquema que se ha asignado al nodo actual como resultado de la validación del esquema. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaCollection](../../system.xml.schema/xmlschemacollection/)\> [get_Schemas](./get_schemas/)() | Devuelve una XmlSchemaCollection para usar en la validación. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SchemaType](./get_schematype/)() | Devuelve un objeto de tipo de esquema. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Devuelve el objeto [XmlReaderSettings](../xmlreadersettings/) usado para crear esta instancia [XmlReader](../xmlreader/). |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | Devuelve un valor que indica el tipo de validación a realizar. |
| [String](../../system/string/) [get_Value](./get_value/)() override | Devuelve el valor de texto del nodo actual. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Devuelve el tipo del nodo actual. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Devuelve el alcance actual de **xml:lang**. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Devuelve el alcance actual de **xml:space**. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Devuelve el valor del atributo con el nombre especificado. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Devuelve el valor del atributo con el nombre local y el Identificador Uniforme de Recurso (URI) de espacio de nombres especificados. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Devuelve el valor del atributo con el índice especificado. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método [Object.GetHashCode()](../../system/object/gethashcode/) de C#. Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada [System.Object.GetType()](../../system/object/gettype/) de C#. |
| **bool** [HasLineInfo](./haslineinfo/)() override | Devuelve un valor que indica si la clase puede devolver información de línea. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | Cuando se sobrescribe en una clase derivada, obtiene el valor del atributo con el índice especificado. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | Cuando se sobrescribe en una clase derivada, obtiene el valor del atributo con el valor [XmlReader::get_Name](../xmlreader/get_name/) especificado. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Cuando se sobrescribe en una clase derivada, obtiene el valor del atributo con los valores [XmlReader::get_LocalName](../xmlreader/get_localname/) y [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) especificados. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador 'is' de C#. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Devuelve un valor que indica si el argumento de cadena es un nombre XML válido. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Devuelve un valor que indica si el argumento de cadena es un token de nombre XML válido. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | Llama a [XmlReader::MoveToContent](../xmlreader/movetocontent/) y verifica si el nodo de contenido actual es una etiqueta de inicio o una etiqueta de elemento vacío. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | Llama a [XmlReader::MoveToContent](../xmlreader/movetocontent/) y verifica si el nodo de contenido actual es una etiqueta de inicio o una etiqueta de elemento vacío y si el valor [XmlReader::get_Name](../xmlreader/get_name/) del elemento encontrado coincide con el argumento proporcionado. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Llama a [XmlReader::MoveToContent](../xmlreader/movetocontent/) y verifica si el nodo de contenido actual es una etiqueta de inicio o una etiqueta de elemento vacío y si los valores [XmlReader::get_LocalName](../xmlreader/get_localname/) y [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) del elemento encontrado coinciden con las cadenas proporcionadas. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la instrucción lock() de C#. Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Resuelve un prefijo de espacio de nombres en el ámbito del elemento actual. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método [Object.MemberwiseClone()](../../system/object/memberwiseclone/) de C#. Permite clonar tipos personalizados. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Se desplaza al atributo con el nombre especificado. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Se desplaza al atributo con el nombre local y el Identificador Uniforme de Recurso (URI) de espacio de nombres especificados. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Se desplaza al atributo con el índice especificado. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Comprueba si el nodo actual es un nodo de contenido (texto que no es espacio en blanco, **CDATA**, **Element**, **EndElement**, **EntityReference** o **EndEntity**). Si el nodo no es un nodo de contenido, el lector avanza hasta el siguiente nodo de contenido o el fin del archivo. Omite los nodos del siguiente tipo: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace** o **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Se desplaza al elemento que contiene el nodo de atributo actual. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | Se desplaza al primer atributo. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Se desplaza al siguiente atributo. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. No copia nada, en realidad, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. No copia nada, en realidad, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| **bool** [Read](./read/)() override | Lee el siguiente nodo del flujo. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Analiza el valor del atributo en uno o más nodos **[Text](../../system.text/)**, **EntityReference** o **EndEntity**. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Lee el contenido como un objeto del tipo especificado. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Lee el contenido y devuelve los bytes binarios decodificados en Base64. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Lee el contenido y devuelve los bytes binarios decodificados en BinHex. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | Lee el contenido de texto en la posición actual como un [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | Lee el contenido de texto en la posición actual como un objeto [DateTime](../../system/datetime/). |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | Lee el contenido de texto en la posición actual como un objeto [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | Lee el contenido de texto en la posición actual como un objeto [Decimal](../../system/decimal/). |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | Lee el contenido de texto en la posición actual como un número de coma flotante de doble precisión. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | Lee el contenido de texto en la posición actual como un número de coma flotante de precisión simple. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | Lee el contenido de texto en la posición actual como un entero con signo de 32 bits. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | Lee el contenido de texto en la posición actual como un entero con signo de 64 bits. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | Lee el contenido de texto en la posición actual como un [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | Lee el contenido de texto en la posición actual como un objeto [String](../../system/string/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Lee el contenido del elemento como el tipo solicitado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Verifica que el nombre local y el URI del espacio de nombres especificados coincidan con los del elemento actual, luego lee el contenido del elemento como el tipo solicitado. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Lee el elemento y decodifica el contenido Base64. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Lee el elemento y decodifica el contenido BinHex. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Lee el elemento actual y devuelve el contenido como un objeto [Boolean](../../system/boolean/). |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Verifica que el nombre local y el URI del espacio de nombres especificados coincidan con los del elemento actual, luego lee el elemento actual y devuelve el contenido como un objeto [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Lee el elemento actual y devuelve el contenido como un objeto [DateTime](../../system/datetime/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Verifica que el nombre local y el URI del espacio de nombres especificados coincidan con los del elemento actual, luego lee el elemento actual y devuelve el contenido como un objeto [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Lee el elemento actual y devuelve el contenido como un objeto [Decimal](../../system/decimal/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Verifica que el nombre local y el URI del espacio de nombres especificados coincidan con los del elemento actual, luego lee el elemento actual y devuelve el contenido como un objeto [Decimal](../../system/decimal/). |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Lee el elemento actual y devuelve el contenido como un número de coma flotante de doble precisión. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Verifica que el nombre local y el URI del espacio de nombres especificados coincidan con los del elemento actual, luego lee el elemento actual y devuelve el contenido como un número de coma flotante de doble precisión. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Lee el elemento actual y devuelve el contenido como un número de coma flotante de precisión simple. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Verifica que el nombre local y el URI del espacio de nombres especificados coincidan con los del elemento actual, luego lee el elemento actual y devuelve el contenido como un número de coma flotante de precisión simple. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Lee el elemento actual y devuelve el contenido como un entero con signo de 32 bits. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Verifica que el nombre local y el URI del espacio de nombres especificados coincidan con los del elemento actual, luego lee el elemento actual y devuelve el contenido como un entero con signo de 32 bits. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Lee el elemento actual y devuelve el contenido como un entero con signo de 64 bits. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Verifica que el nombre local y el URI del espacio de nombres especificados coincidan con los del elemento actual, luego lee el elemento actual y devuelve el contenido como un entero con signo de 64 bits. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Lee el elemento actual y devuelve el contenido como un [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Verifica que el nombre local y el URI del espacio de nombres especificados coincidan con los del elemento actual, luego lee el elemento actual y devuelve el contenido como un [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Lee el elemento actual y devuelve el contenido como un objeto [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Verifica que el nombre local y el URI del espacio de nombres especificados coincidan con los del elemento actual, luego lee el elemento actual y devuelve el contenido como un objeto [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Lee un elemento solo de texto. Sin embargo, se recomienda usar el método [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) en su lugar, porque proporciona una forma más directa de manejar esta operación. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Verifica que el valor [XmlReader::get_Name](../xmlreader/get_name/) del elemento encontrado coincida con la cadena dada antes de leer un elemento solo de texto. Sin embargo, se recomienda usar el método [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) en su lugar, porque proporciona una forma más directa de manejar esta operación. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Verifica que los valores [XmlReader::get_LocalName](../xmlreader/get_localname/) y [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) del elemento encontrado coincidan con las cadenas dadas antes de leer un elemento solo de texto. Sin embargo, se recomienda usar el método [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) en su lugar, porque proporciona una forma más directa de manejar esta operación. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Verifica que el nodo de contenido actual sea una etiqueta de cierre y avanza el lector al siguiente nodo. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | Cuando se sobrescribe en una clase derivada, lee todo el contenido, incluido el marcado, como una cadena. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | Cuando se sobrescribe en una clase derivada, lee el contenido, incluido el marcado, que representa este nodo y todos sus hijos. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Verifica que el nodo actual sea un elemento y avanza el lector al siguiente nodo. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Verifica que el nodo de contenido actual sea un elemento con el valor [XmlReader::get_Name](../xmlreader/get_name/) dado y avanza el lector al siguiente nodo. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Verifica que el nodo de contenido actual sea un elemento con los valores [XmlReader::get_LocalName](../xmlreader/get_localname/) y [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) dados y avanza el lector al siguiente nodo. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Lee el contenido de un elemento o nodo de texto como una cadena. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Devuelve una nueva instancia [XmlReader](../xmlreader/) que puede usarse para leer el nodo actual y todos sus descendientes. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | Avanza el [XmlReader](../xmlreader/) al siguiente elemento descendiente con el nombre calificado especificado. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Avanza el [XmlReader](../xmlreader/) al siguiente elemento descendiente con el nombre local y el URI del espacio de nombres especificados. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Lee hasta que se encuentre un elemento con el nombre calificado especificado. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Lee hasta que se encuentre un elemento con el nombre local y el URI del espacio de nombres especificados. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | Avanza el [XmlReader](../xmlreader/) al siguiente elemento hermano con el nombre calificado especificado. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Avanza el [XmlReader](../xmlreader/) al siguiente elemento hermano con el nombre local y el URI del espacio de nombres especificados. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadTypedValue](./readtypedvalue/)() | Devuelve el tipo de tiempo de ejecución para el tipo de lenguaje de definición XML [Schema](../../system.xml.schema/) (XSD) especificado. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Lee flujos grandes de texto incrustados en un documento XML. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [ResolveEntity](./resolveentity/)() override | Resuelve la referencia de entidad para nodos **EntityReference**. |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | Establece un valor que especifica cómo el lector maneja las entidades. |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Establece un valor que indica si se debe soportar espacios de nombres. |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | Establece un valor que indica el tipo de validación a realizar. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Establece el [XmlResolver](../xmlresolver/) usado para resolver referencias externas de definición de tipo de documento (DTD) y de ubicación de esquema. El [XmlResolver](../xmlresolver/) también se usa para manejar cualquier elemento import o include encontrado en esquemas de lenguaje de definición XML [Schema](../../system.xml.schema/) (XSD). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual void [Skip](../xmlreader/skip/)() | Omite los hijos del nodo actual. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Añade un manejador de eventos para recibir información sobre errores de validación de definiciones de tipo de documento (DTD), esquema XML-Data Reduced (XDR) y esquema de lenguaje de definición XML [Schema](../../system.xml.schema/) (XSD). |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Elimina un manejador de eventos para recibir información sobre errores de validación de definiciones de tipo de documento (DTD), esquema XML-Data Reduced (XDR) y esquema de lenguaje de definición XML [Schema](../../system.xml.schema/) (XSD). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&) | Inicializa una nueva instancia de la clase [XmlValidatingReader](./) que valida el contenido devuelto por el [XmlReader](../xmlreader/) dado. |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Inicializa una nueva instancia de la clase [XmlValidatingReader](./) con los valores especificados. |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Inicializa una nueva instancia de la clase [XmlValidatingReader](./) con los valores especificados. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Tipos definidos

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |

## Comentarios

Obsoleto
:   Esta clase está obsoleta. Se recomienda usar la clase [XmlReaderSettings](../xmlreadersettings/) y el método [XmlReader::Create](../xmlreader/create/) para crear un lector XML validador.
Objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando operator new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

## Ver también

* Clase [XmlReader](../xmlreader/)
* Clase [IXmlLineInfo](../ixmllineinfo/)
* Clase [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Espacio de nombres [System::Xml](../)
* Biblioteca [Aspose.Slides](../../)