---
title: XmlSchemaSet
second_title: Referencia de la API de Aspose.Slides para C++
description: Contiene una caché de esquemas del lenguaje de definición XML (XSD).
type: docs
weight: 781
url: /es/system.xml.schema/xmlschemaset/
---
## Métodos

Contiene una caché de esquemas de lenguaje de definición XML [Schema](../) (XSD).

```cpp
class XmlSchemaSet : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Add](./add/)([String](../../system/string/), const [String](../../system/string/)\&) | Agrega el esquema de lenguaje de definición XML [Schema](../) (XSD) en la URL especificada al [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Add](./add/)([String](../../system/string/), const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&) | Agrega el esquema de lenguaje de definición XML [Schema](../) (XSD) contenido en el [XmlReader](../../system.xml/xmlreader/) al [XmlSchemaSet](./). |
| void [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSet](./)\>\&) | Agrega todos los esquemas de lenguaje de definición XML [Schema](../) (XSD) en el [XmlSchemaSet](./) dado al [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | Agrega el [XmlSchema](../xmlschema/) proporcionado al [XmlSchemaSet](./). |
| void [Compile](./compile/)() | Compila los esquemas de lenguaje de definición XML [Schema](../) (XSD) añadidos al [XmlSchemaSet](./) en un único esquema lógico. |
| **bool** [Contains](./contains/)([String](../../system/string/)) | Indica si un esquema de lenguaje de definición XML [Schema](../) (XSD) con el URI del espacio de nombres objetivo especificado está en el [XmlSchemaSet](./). |
| **bool** [Contains](./contains/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | Indica si el objeto [XmlSchema](../xmlschema/) de lenguaje de definición XML [Schema](../) (XSD) especificado está en el [XmlSchemaSet](./). |
| void [CopyTo](./copyto/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\>\&, **int32_t**) | Copia todos los objetos [XmlSchema](../xmlschema/) del [XmlSchemaSet](./) al array dado, comenzando en el índice especificado. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Sólo para uso interno. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaCompilationSettings](../xmlschemacompilationsettings/)\> [get_CompilationSettings](./get_compilationsettings/)() | Devuelve el [XmlSchemaCompilationSettings](../xmlschemacompilationsettings/) para el [XmlSchemaSet](./). |
| **int32_t** [get_Count](./get_count/)() | Devuelve el número de esquemas lógicos de lenguaje de definición XML [Schema](../) (XSD) en el [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_GlobalAttributes](./get_globalattributes/)() | Devuelve todos los atributos globales en todos los esquemas de lenguaje de definición XML [Schema](../) (XSD) en el [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_GlobalElements](./get_globalelements/)() | Devuelve todos los elementos globales en todos los esquemas de lenguaje de definición XML [Schema](../) (XSD) en el [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_GlobalTypes](./get_globaltypes/)() | Devuelve todos los tipos simples y complejos globales en todos los esquemas de lenguaje de definición XML [Schema](../) (XSD) en el [XmlSchemaSet](./). |
| **bool** [get_IsCompiled](./get_iscompiled/)() | Devuelve un valor que indica si los esquemas de lenguaje de definición XML [Schema](../) (XSD) en el [XmlSchemaSet](./) han sido compilados. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | Devuelve el [XmlNameTable](../../system.xml/xmlnametable/) predeterminado utilizado por el [XmlSchemaSet](./) al cargar nuevos esquemas de lenguaje de definición XML [Schema](../) (XSD). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la instrucción C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Remove](./remove/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | Elimina el esquema de lenguaje de definición XML [Schema](../) (XSD) especificado del [XmlSchemaSet](./). |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| **bool** [RemoveRecursive](./removerecursive/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | Elimina el esquema de lenguaje de definición XML [Schema](../) (XSD) especificado y todos los esquemas que importa del [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Reprocess](./reprocess/)([SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>) | Reprocesa un esquema de lenguaje de definición XML [Schema](../) (XSD) que ya existe en el [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\>\> [Schemas](./schemas/)() | Devuelve una colección de todos los esquemas de lenguaje de definición XML [Schema](../) (XSD) en el [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\>\> [Schemas](./schemas/)([String](../../system/string/)) | Devuelve una colección de todos los esquemas de lenguaje de definición XML [Schema](../) (XSD) en el [XmlSchemaSet](./) que pertenecen al espacio de nombres dado. |
| void [set_CompilationSettings](./set_compilationsettings/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaCompilationSettings](../xmlschemacompilationsettings/)\>\&) | Establece el [XmlSchemaCompilationSettings](../xmlschemacompilationsettings/) para el [XmlSchemaSet](./). |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Establece el [XmlResolver](../../system.xml/xmlresolver/) usado para resolver espacios de nombres o ubicaciones referenciadas en los elementos include e import de un esquema. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la instrucción C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../../system/lockcontext/). |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Agrega un controlador de eventos para recibir información sobre errores de validación de esquemas de lenguaje de definición XML [Schema](../) (XSD). |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Elimina un controlador de eventos para recibir información sobre errores de validación de esquemas de lenguaje de definición XML [Schema](../) (XSD). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
|  [XmlSchemaSet](./xmlschemaset/)() | Inicializa una nueva instancia de la clase [XmlSchemaSet](./). |
|  [XmlSchemaSet](./xmlschemaset/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\>\&) | Inicializa una nueva instancia de la clase [XmlSchemaSet](./) con el [XmlNameTable](../../system.xml/xmlnametable/) especificado. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Tipos definidos

| Tipo | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |

## Observaciones

Los objetos de esta clase sólo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. 

## Ver también

* Clase [Object](../../system/object/)
* Espacio de nombres [System::Xml::Schema](../)
* Biblioteca [Aspose.Slides](../../)