---
title: XmlWriterSettings
second_title: Referencia de la API de Aspose.Slides para C++
description: "Especifica un conjunto de características para admitir en el objeto XmlWriter creado por el método XmlWriter::Create."
type: docs
weight: 586
url: /es/system.xml/xmlwritersettings/
---
## XmlWriterSettings clase

Especifica un conjunto de características para admitir en el objeto [XmlWriter](../xmlwriter/) creado por el método [XmlWriter::Create](../xmlwriter/create/).

```cpp
class XmlWriterSettings : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](./)\> [Clone](./clone/)() | Crea una copia de la instancia [XmlWriterSettings](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | Devuelve un valor que indica si el escritor XML debe verificar que todos los caracteres del documento cumplan con la sección "2.2 Characters" del W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets). |
| **bool** [get_CloseOutput](./get_closeoutput/)() | Devuelve un valor que indica si el [XmlWriter](../xmlwriter/) también debe cerrar el flujo subyacente o TextWriter cuando se llama al método [XmlWriter::Close](../xmlwriter/close/). |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | Devuelve el nivel de conformidad que el escritor XML verifica en la salida XML. |
| **bool** [get_DoNotEscapeUriAttributes](./get_donotescapeuriattributes/)() | Devuelve un valor que indica si el [XmlWriter](../xmlwriter/) no escapa los atributos URI. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Devuelve el tipo de codificación de texto a usar. |
| **bool** [get_Indent](./get_indent/)() | Devuelve un valor que indica si se deben sangrar los elementos. |
| [String](../../system/string/) [get_IndentChars](./get_indentchars/)() | Devuelve la cadena de caracteres a usar al sangrar. Esta configuración se utiliza cuando el valor [XmlWriterSettings::set_Indent](./set_indent/) está establecido en **true**. |
| [System::Xml::NamespaceHandling](../namespacehandling/) [get_NamespaceHandling](./get_namespacehandling/)() | Devuelve un valor que indica si el [XmlWriter](../xmlwriter/) debe eliminar declaraciones de espacio de nombres duplicadas al escribir contenido XML. El comportamiento predeterminado es que el escritor emita todas las declaraciones de espacio de nombres presentes en el resolvedor de espacios de nombres del escritor. |
| [String](../../system/string/) [get_NewLineChars](./get_newlinechars/)() | Devuelve la cadena de caracteres a usar para saltos de línea. |
| [System::Xml::NewLineHandling](../newlinehandling/) [get_NewLineHandling](./get_newlinehandling/)() | Devuelve un valor que indica si se deben normalizar los saltos de línea en la salida. |
| **bool** [get_NewLineOnAttributes](./get_newlineonattributes/)() | Devuelve un valor que indica si se deben escribir los atributos en una nueva línea. |
| **bool** [get_OmitXmlDeclaration](./get_omitxmldeclaration/)() | Devuelve un valor que indica si se debe omitir una declaración XML. |
| [XmlOutputMethod](../xmloutputmethod/) [get_OutputMethod](./get_outputmethod/)() | Devuelve el método usado para serializar la salida [XmlWriter](../xmlwriter/). |
| **bool** [get_WriteEndDocumentOnClose](./get_writeenddocumentonclose/)() | Devuelve un valor que indica si el [XmlWriter](../xmlwriter/) añadirá etiquetas de cierre a todas las etiquetas de elemento sin cerrar cuando se llame al método [XmlWriter::Close](../xmlwriter/close/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
| [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias en subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias en subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [Reset](./reset/)() | Restablece los miembros de la clase de configuración a sus valores predeterminados. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | Establece un valor que indica si el escritor XML debe verificar que todos los caracteres del documento cumplan con la sección "2.2 Characters" del W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets). |
| void [set_CloseOutput](./set_closeoutput/)(**bool**) | Establece un valor que indica si el [XmlWriter](../xmlwriter/) también debe cerrar el flujo subyacente o TextWriter cuando se llama al método [XmlWriter::Close](../xmlwriter/close/). |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | Establece el nivel de conformidad que el escritor XML verifica en la salida XML. |
| void [set_DoNotEscapeUriAttributes](./set_donotescapeuriattributes/)(**bool**) | Establece un valor que indica si el [XmlWriter](../xmlwriter/) no escapa los atributos URI. |
| void [set_Encoding](./set_encoding/)(const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | Establece el tipo de codificación de texto a usar. |
| void [set_Indent](./set_indent/)(**bool**) | Establece un valor que indica si se deben sangrar los elementos. |
| void [set_IndentChars](./set_indentchars/)(const [String](../../system/string/)\&) | Establece la cadena de caracteres a usar al sangrar. Esta configuración se utiliza cuando el valor [XmlWriterSettings::set_Indent](./set_indent/) está establecido en **true**. |
| void [set_NamespaceHandling](./set_namespacehandling/)([System::Xml::NamespaceHandling](../namespacehandling/)) | Establece un valor que indica si el [XmlWriter](../xmlwriter/) debe eliminar declaraciones de espacio de nombres duplicadas al escribir contenido XML. El comportamiento predeterminado es que el escritor emita todas las declaraciones de espacio de nombres presentes en el resolvedor de espacios de nombres del escritor. |
| void [set_NewLineChars](./set_newlinechars/)(const [String](../../system/string/)\&) | Establece la cadena de caracteres a usar para saltos de línea. |
| void [set_NewLineHandling](./set_newlinehandling/)([System::Xml::NewLineHandling](../newlinehandling/)) | Establece un valor que indica si se deben normalizar los saltos de línea en la salida. |
| void [set_NewLineOnAttributes](./set_newlineonattributes/)(**bool**) | Establece un valor que indica si se deben escribir los atributos en una nueva línea. |
| void [set_OmitXmlDeclaration](./set_omitxmldeclaration/)(**bool**) | Establece un valor que indica si se debe omitir una declaración XML. |
| void [set_WriteEndDocumentOnClose](./set_writeenddocumentonclose/)(**bool**) | Establece un valor que indica si el [XmlWriter](../xmlwriter/) añadirá etiquetas de cierre a todas las etiquetas de elemento sin cerrar cuando se llame al método [XmlWriter::Close](../xmlwriter/close/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| [XmlWriterSettings](./xmlwritersettings/)() | Inicializa una nueva instancia de la clase [XmlWriterSettings](./). |
| virtual [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Tipos definidos

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |

## Comentarios

Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. 

## Ver también

* Clase [Object](../../system/object/)
* Espacio de nombres [System::Xml](../)
* Biblioteca [Aspose.Slides](../../)