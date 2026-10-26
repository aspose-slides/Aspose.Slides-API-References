---
title: XmlWriter
second_title: Referencia de la API de Aspose.Slides para C++
description: Representa un escritor que proporciona una forma rápida, sin caché y solo de avance, de generar flujos o archivos que contienen datos XML.
type: docs
weight: 573
url: /es/system.xml/xmlwriter/
---
## XmlWriter clase

Representa un escritor que proporciona una manera rápida, sin caché, solo de avance, de generar flujos o archivos que contengan datos XML.

```cpp
class XmlWriter : public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual void [Close](./close/)() | Cuando se sobrescribe en una clase derivada, cierra este flujo y el flujo subyacente. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Crea una nueva instancia de [XmlWriter](./) usando el nombre de archivo especificado. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Crea una nueva instancia de [XmlWriter](./) usando el nombre de archivo y el objeto [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Crea una nueva instancia de [XmlWriter](./) usando el flujo especificado. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Crea una nueva instancia de [XmlWriter](./) usando el flujo y el objeto [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Crea una nueva instancia de [XmlWriter](./) usando el TextWriter especificado. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Crea una nueva instancia de [XmlWriter](./) usando el TextWriter y los objetos [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Crea una nueva instancia de [XmlWriter](./) usando el [Text::StringBuilder](../../system.text/stringbuilder/) especificado. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Crea una nueva instancia de [XmlWriter](./) usando los objetos [Text::StringBuilder](../../system.text/stringbuilder/) y [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&) | Crea una nueva instancia de [XmlWriter](./) usando el objeto [XmlWriter](./) especificado. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Crea una nueva instancia de [XmlWriter](./) usando los objetos [XmlWriter](./) y [XmlWriterSettings](../xmlwritersettings/) especificados. |
| void [Dispose](./dispose/)() override | Libera todos los recursos usados por la instancia actual de la clase [XmlWriter](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo de C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo de C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo de C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo de C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo con fines internos. |
| virtual void [Flush](./flush/)() | Cuando se sobrescribe en una clase derivada, vacía lo que haya en el búfer a los flujos subyacentes y también vacía el flujo subyacente. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](./get_settings/)() | Devuelve el objeto [XmlWriterSettings](../xmlwritersettings/) usado para crear esta instancia de [XmlWriter](./). |
| virtual [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() | Cuando se sobrescribe en una clase derivada, obtiene el estado del escritor. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Cuando se sobrescribe en una clase derivada, obtiene el alcance actual de **xml:lang**. |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | Cuando se sobrescribe en una clase derivada, obtiene un XmlSpace que representa el alcance actual de **xml:space**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Analogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Analogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) | Cuando se sobrescribe en una clase derivada, devuelve el prefijo más cercano definido en el alcance actual del espacio de nombres para el URI del espacio de nombres. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. Realmente no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. Realmente no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debería llamarse directamente; use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debería llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debería llamarse directamente; use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debería llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual void [WriteAttributes](./writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Cuando se sobrescribe en una clase derivada, escribe todos los atributos encontrados en la posición actual del [XmlReader](../xmlreader/). |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Cuando se sobrescribe en una clase derivada, escribe un atributo con el nombre local, URI del espacio de nombres y valor especificados. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Cuando se sobrescribe en una clase derivada, escribe el atributo con el nombre local y valor especificados. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Cuando se sobrescribe en una clase derivada, escribe el atributo con el prefijo, nombre local, URI del espacio de nombres y valor especificados. |
| virtual void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Cuando se sobrescribe en una clase derivada, codifica los bytes binarios especificados como Base64 y escribe el texto resultante. |
| virtual void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Cuando se sobrescribe en una clase derivada, codifica los bytes binarios especificados como **BinHex** y escribe el texto resultante. |
| virtual void [WriteCData](./writecdata/)([String](../../system/string/)) | Cuando se sobrescribe en una clase derivada, escribe un bloque **...** que contiene el texto especificado. |
| virtual void [WriteCharEntity](./writecharentity/)(char16_t) | Cuando se sobrescribe en una clase derivada, fuerza la generación de una entidad de carácter para el valor Unicode especificado. |
| virtual void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Cuando se sobrescribe en una clase derivada, escribe texto un búfer a la vez. |
| virtual void [WriteComment](./writecomment/)([String](../../system/string/)) | Cuando se sobrescribe en una clase derivada, escribe un comentario **** que contiene el texto especificado. |
| virtual void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Cuando se sobrescribe en una clase derivada, escribe la declaración DOCTYPE con el nombre especificado y atributos opcionales. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Escribe un elemento con el nombre local y valor especificados. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Escribe un elemento con el nombre local, URI del espacio de nombres y valor especificados. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Escribe un elemento con el prefijo, nombre local, URI del espacio de nombres y valor especificados. |
| virtual void [WriteEndAttribute](./writeendattribute/)() | Cuando se sobrescribe en una clase derivada, cierra la llamada anterior a XmlWriter::WriteStartAttribute(String,String). |
| virtual void [WriteEndDocument](./writeenddocument/)() | Cuando se sobrescribe en una clase derivada, cierra cualquier elemento o atributo abierto y devuelve el escritor al estado Start. |
| virtual void [WriteEndElement](./writeendelement/)() | Cuando se sobrescribe en una clase derivada, cierra un elemento y elimina el alcance del espacio de nombres correspondiente. |
| virtual void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) | Cuando se sobrescribe en una clase derivada, escribe una referencia de entidad como **&name**;. |
| virtual void [WriteFullEndElement](./writefullendelement/)() | Cuando se sobrescribe en una clase derivada, cierra un elemento y elimina el alcance del espacio de nombres correspondiente. |
| virtual void [WriteName](./writename/)(const [String](../../system/string/)\&) | Cuando se sobrescribe en una clase derivada, escribe el nombre especificado, asegurando que sea un nombre válido según la recomendación W3C XML 1.0 ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) | Cuando se sobrescribe en una clase derivada, escribe el nombre especificado, asegurando que sea un NmToken válido según la recomendación W3C XML 1.0 ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Cuando se sobrescribe en una clase derivada, copia todo del lector al escritor y mueve el lector al inicio del siguiente hermano. |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | Copia todo del objeto XPathNavigator al escritor. La posición del XPathNavigator permanece sin cambios. |
| virtual void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) | Cuando se sobrescribe en una clase derivada, escribe una instrucción de procesamiento con un espacio entre el nombre y el texto de la siguiente manera: **<?name text?>**. |
| virtual void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Cuando se sobrescribe en una clase derivada, escribe el nombre calificado por espacio de nombres. Este método busca el prefijo que está en alcance para el espacio de nombres dado. |
| virtual void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Cuando se sobrescribe en una clase derivada, escribe marcado bruto manualmente desde un búfer de caracteres. |
| virtual void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) | Cuando se sobrescribe en una clase derivada, escribe marcado bruto manualmente desde una cadena. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Escribe el inicio de un atributo con el nombre local y URI del espacio de nombres especificados. |
| virtual void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Cuando se sobrescribe en una clase derivada, escribe el inicio de un atributo con el prefijo, nombre local y URI del espacio de nombres especificados. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&) | Escribe el inicio de un atributo con el nombre local especificado. |
| virtual void [WriteStartDocument](./writestartdocument/)() | Cuando se sobrescribe en una clase derivada, escribe la declaración XML con la versión "1.0". |
| virtual void [WriteStartDocument](./writestartdocument/)(**bool**) | Cuando se sobrescribe en una clase derivada, escribe la declaración XML con la versión "1.0" y el atributo standalone. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Cuando se sobrescribe en una clase derivada, escribe la etiqueta de inicio especificada y la asocia con el espacio de nombres dado. |
| virtual void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Cuando se sobrescribe en una clase derivada, escribe la etiqueta de inicio especificada y la asocia con el espacio de nombres y prefijo dados. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&) | Cuando se sobrescribe en una clase derivada, escribe una etiqueta de inicio con el nombre local especificado. |
| virtual void [WriteString](./writestring/)(const [String](../../system/string/)\&) | Cuando se sobrescribe en una clase derivada, escribe el contenido de texto dado. |
| virtual void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) | Cuando se sobrescribe en una clase derivada, genera y escribe la entidad de carácter sustituto para el par de caracteres sustitutos. |
| virtual void [WriteValue](./writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Escribe el valor del objeto. |
| virtual void [WriteValue](./writevalue/)(const [String](../../system/string/)\&) | Escribe un valor [String](../../system/string/). |
| virtual void [WriteValue](./writevalue/)(**bool**) | Escribe un valor [Boolean](../../system/boolean/). |
| virtual void [WriteValue](./writevalue/)([DateTime](../../system/datetime/)) | Escribe un valor [DateTime](../../system/datetime/). |
| virtual void [WriteValue](./writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | Escribe un valor [DateTimeOffset](../../system/datetimeoffset/). |
| virtual void [WriteValue](./writevalue/)(**double**) | Escribe un valor [Double](../../system/double/). |
| virtual void [WriteValue](./writevalue/)(**float**) | Escribe un número de coma flotante de precisión simple. |
| virtual void [WriteValue](./writevalue/)([Decimal](../../system/decimal/)) | Escribe un valor [Decimal](../../system/decimal/). |
| virtual void [WriteValue](./writevalue/)(**int32_t**) | Escribe un valor [Int32](../../system/int32/). |
| virtual void [WriteValue](./writevalue/)(**int64_t**) | Escribe un valor [Int64](../../system/int64/). |
| virtual void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) | Cuando se sobrescribe en una clase derivada, escribe el espacio en blanco dado. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Definiciones de tipo

| Alias de tipo | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |

## Ver también

* Clase [IDisposable](../../system/idisposable/)
* Espacio de nombres [System::Xml](../)
* Biblioteca [Aspose.Slides](../../)