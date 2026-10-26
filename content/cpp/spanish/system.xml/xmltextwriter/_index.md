---
title: XmlTextWriter
second_title: Referencia de API de Aspose.Slides para C++
description: Representa un escritor que proporciona una manera rápida, sin caché y solo en avance de generar flujos o archivos que contienen datos XML que cumplen con las recomendaciones del Lenguaje de Marcado Extensible (XML) 1.0 de la W3C y los Espacios de Nombres en XML.
type: docs
weight: 521
url: /es/system.xml/xmltextwriter/
---
## XmlTextWriter clase

Representa un escritor que proporciona una forma rápida, sin caché y solo en avance de generar flujos o archivos que contienen datos XML que cumplen con las recomendaciones W3C Extensible Markup Language (XML) 1.0 y Namespaces in XML.

```cpp
class XmlTextWriter : public System::Xml::XmlWriter
```

## Métodos

| Método | Descripción |
| --- | --- |
| void [Close](./close/)() override | Cierra este flujo y el flujo subyacente. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&) | Crea una nueva instancia de [XmlWriter](../xmlwriter/) usando el nombre de archivo especificado. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Crea una nueva instancia de [XmlWriter](../xmlwriter/) usando el nombre de archivo y el objeto [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Crea una nueva instancia de [XmlWriter](../xmlwriter/) usando el flujo especificado. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Crea una nueva instancia de [XmlWriter](../xmlwriter/) usando el flujo y el objeto [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Crea una nueva instancia de [XmlWriter](../xmlwriter/) usando el TextWriter especificado. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Crea una nueva instancia de [XmlWriter](../xmlwriter/) usando los objetos TextWriter y [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Crea una nueva instancia de [XmlWriter](../xmlwriter/) usando el [Text::StringBuilder](../../system.text/stringbuilder/) especificado. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Crea una nueva instancia de [XmlWriter](../xmlwriter/) usando los objetos [Text::StringBuilder](../../system.text/stringbuilder/) y [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | Crea una nueva instancia de [XmlWriter](../xmlwriter/) usando el objeto [XmlWriter](../xmlwriter/) especificado. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Crea una nueva instancia de [XmlWriter](../xmlwriter/) usando los objetos [XmlWriter](../xmlwriter/) y [XmlWriterSettings](../xmlwritersettings/) especificados. |
| void [Dispose](../xmlwriter/dispose/)() override | Libera todos los recursos usados por la instancia actual de la clase [XmlWriter](../xmlwriter/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica [Object.Equals](../../system/object/equals/) de C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| void [Flush](./flush/)() override | Vacía lo que haya en el búfer a los flujos subyacentes y también vacía el flujo subyacente. |
| [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [get_BaseStream](./get_basestream/)() | Devuelve el objeto de flujo subyacente. |
| [System::Xml::Formatting](../formatting/) [get_Formatting](./get_formatting/)() | Indica cómo se formatea la salida. |
| **int32_t** [get_Indentation](./get_indentation/)() | Devuelve cuántos IndentChars escribir para cada nivel en la jerarquía cuando [XmlTextWriter::set_Formatting](./set_formatting/) está configurado a [Formatting::Indented](../formatting/). |
| char16_t [get_IndentChar](./get_indentchar/)() | Devuelve qué carácter usar para la sangría cuando [XmlTextWriter::set_Formatting](./set_formatting/) está configurado a [Formatting::Indented](../formatting/). |
| **bool** [get_Namespaces](./get_namespaces/)() | Devuelve un valor que indica si se debe habilitar el soporte de espacios de nombres. |
| char16_t [get_QuoteChar](./get_quotechar/)() | Devuelve qué carácter usar para citar valores de atributos. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](../xmlwriter/get_settings/)() | Devuelve el objeto [XmlWriterSettings](../xmlwritersettings/) usado para crear esta instancia de [XmlWriter](../xmlwriter/). |
| [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() override | Devuelve el estado del escritor. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Devuelve el ámbito actual de **xml:lang**. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Devuelve un XmlSpace que representa el ámbito actual de **xml:space**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hashing de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la declaración C# lock(). Llámalo directamente o usa el objeto centinela [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) override | Devuelve el prefijo más cercano definido en el ámbito de espacio de nombres actual para el URI del espacio de nombres. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
| [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. Realmente no copia nada, solo inicializa un nuevo objeto y permite la copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. Realmente no copia nada, solo inicializa un nuevo objeto y permite la copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_Formatting](./set_formatting/)([System::Xml::Formatting](../formatting/)) | Indica cómo se formatea la salida. |
| void [set_Indentation](./set_indentation/)(**int32_t**) | Establece cuántos IndentChars escribir para cada nivel en la jerarquía cuando [XmlTextWriter::set_Formatting](./set_formatting/) está configurado a [Formatting::Indented](../formatting/). |
| void [set_IndentChar](./set_indentchar/)(char16_t) | Establece qué carácter usar para la sangría cuando [XmlTextWriter::set_Formatting](./set_formatting/) está configurado a [Formatting::Indented](../formatting/). |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Establece un valor que indica si se debe habilitar el soporte de espacios de nombres. |
| void [set_QuoteChar](./set_quotechar/)(char16_t) | Establece qué carácter usar para citar valores de atributos. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la declaración C# lock(). Llámalo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual void [WriteAttributes](../xmlwriter/writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Cuando se sobrescribe en una clase derivada, escribe todos los atributos encontrados en la posición actual en el [XmlReader](../xmlreader/). |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Cuando se sobrescribe en una clase derivada, escribe un atributo con el nombre local, URI del espacio de nombres y valor especificados. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Cuando se sobrescribe en una clase derivada, escribe el atributo con el nombre local y valor especificados. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Cuando se sobrescribe en una clase derivada, escribe el atributo con el prefijo, nombre local, URI del espacio de nombres y valor especificados. |
| void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Codifica los bytes binarios especificados como base64 y escribe el texto resultante. |
| void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Codifica los bytes binarios especificados como binhex y escribe el texto resultante. |
| void [WriteCData](./writecdata/)([String](../../system/string/)) override | Escribe un bloque **...** que contiene el texto especificado. |
| void [WriteCharEntity](./writecharentity/)(char16_t) override | Fuerza la generación de una entidad de carácter para el valor Unicode del carácter especificado. |
| void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | Escribe texto un búfer a la vez. |
| void [WriteComment](./writecomment/)([String](../../system/string/)) override | Escribe un comentario **** que contiene el texto especificado. |
| void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Escribe la declaración DOCTYPE con el nombre especificado y atributos opcionales. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Escribe un elemento con el nombre local y valor especificados. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Escribe un elemento con el nombre local, URI del espacio de nombres y valor especificados. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Escribe un elemento con el prefijo, nombre local, URI del espacio de nombres y valor especificados. |
| void [WriteEndAttribute](./writeendattribute/)() override | Cierra la llamada [XmlTextWriter::WriteStartAttribute](./writestartattribute/) anterior. |
| void [WriteEndDocument](./writeenddocument/)() override | Cierra cualquier elemento o atributo abierto y devuelve el escritor al estado Start. |
| void [WriteEndElement](./writeendelement/)() override | Cierra un elemento y elimina la pila del ámbito de espacio de nombres correspondiente. |
| void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) override | Escribe una referencia de entidad como **&name**;. |
| void [WriteFullEndElement](./writefullendelement/)() override | Cierra un elemento y elimina la pila del ámbito de espacio de nombres correspondiente. |
| void [WriteName](./writename/)(const [String](../../system/string/)\&) override | Escribe el nombre especificado, asegurándose de que sea un nombre válido según [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) override | Escribe el nombre especificado, asegurándose de que sea un **NmToken** válido según [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Cuando se sobrescribe en una clase derivada, copia todo del lector al escritor y mueve el lector al inicio del siguiente hermano. |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | Copia todo del objeto XPathNavigator al escritor. La posición del XPathNavigator permanece sin cambios. |
| void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) override | Escribe una instrucción de procesamiento con un espacio entre el nombre y el texto de la siguiente forma: **<?name text?>**. |
| void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Escribe el nombre calificado por espacio de nombres. Este método busca el prefijo que está en alcance para el espacio de nombres dado. |
| void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | Escribe marcado bruto manualmente desde un búfer de caracteres. |
| void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) override | Escribe marcado bruto manualmente desde una cadena. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Escribe el inicio de un atributo. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Escribe el inicio de un atributo con el nombre local y URI del espacio de nombres especificados. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&) | Escribe el inicio de un atributo con el nombre local especificado. |
| void [WriteStartDocument](./writestartdocument/)() override | Escribe la declaración XML con la versión "1.0". |
| void [WriteStartDocument](./writestartdocument/)(**bool**) override | Escribe la declaración XML con la versión "1.0" y el atributo standalone. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Escribe la etiqueta de inicio especificada y la asocia con el espacio de nombres y prefijo dados. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Cuando se sobrescribe en una clase derivada, escribe la etiqueta de inicio especificada y la asocia con el espacio de nombres dado. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&) | Cuando se sobrescribe en una clase derivada, escribe una etiqueta de inicio con el nombre local especificado. |
| void [WriteString](./writestring/)(const [String](../../system/string/)\&) override | Escribe el contenido de texto dado. |
| void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) override | Genera y escribe la entidad de carácter sustituto para el par de caracteres sustitutos. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Escribe el valor del objeto. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(const [String](../../system/string/)\&) | Escribe un valor [String](../../system/string/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**bool**) | Escribe un valor [Boolean](../../system/boolean/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTime](../../system/datetime/)) | Escribe un valor [DateTime](../../system/datetime/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | Escribe un valor [DateTimeOffset](../../system/datetimeoffset/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**double**) | Escribe un valor [Double](../../system/double/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**float**) | Escribe un número de punto flotante de precisión simple. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([Decimal](../../system/decimal/)) | Escribe un valor [Decimal](../../system/decimal/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int32_t**) | Escribe un valor [Int32](../../system/int32/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int64_t**) | Escribe un valor [Int64](../../system/int64/). |
| void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) override | Escribe el espacio en blanco dado. |
| [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Crea una instancia de la clase [XmlTextWriter](./) usando el flujo y la codificación especificados. |
| [XmlTextWriter](./xmltextwriter/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Crea una instancia de la clase [XmlTextWriter](./) usando el archivo especificado. |
| [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Crea una instancia de la clase [XmlTextWriter](./) usando el TextWriter especificado. |
| virtual [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Definiciones de tipos

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para puntero compartido a una instancia de esta clase. |

## Observaciones

Se recomienda usar la clase [XmlWriter](../xmlwriter/) en su lugar.

Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

## Véase también

* Clase [XmlWriter](../xmlwriter/)
* Espacio de nombres [System::Xml](../)
* Biblioteca [Aspose.Slides](../../)