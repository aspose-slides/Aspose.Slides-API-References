---
title: StreamReader
second_title: Referencia de la API de Aspose.Slides para C++
description: "Representa un lector que lee caracteres de un flujo de bytes. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento."
type: docs
weight: 378
url: /es/system.io/streamreader/
---
## StreamReader clase

Representa un lector que lee caracteres de un flujo de bytes. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class StreamReader : public System::IO::TextReader
```

## Métodos

| Método | Descripción |
| --- | --- |
| void [Close](./close/)() override | Cierra los flujos actual y subyacente. |
| virtual void [Dispose](./dispose/)(**bool**) | Libera todos los recursos utilizados por el objeto actual y cierra el flujo subyacente. |
| void [Dispose](./dispose/)() override | Libera todos los recursos utilizados por el objeto actual y cierra el flujo subyacente. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | Devuelve un puntero compartido a un objeto que representa el flujo subyacente. |
| [EncodingPtr](../../system/encodingptr/) [get_CurrentEncoding](./get_currentencoding/)() | Devuelve la codificación actualmente usada. |
| **bool** [get_EndOfStream](./get_endofstream/)() | Devuelve un valor que indica si se ha alcanzado el final del flujo. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| int [Peek](./peek/)() override | Lee un solo carácter del flujo sin cambiar el cursor de lectura del flujo. |
| int [Read](./read/)() override | Lee un solo carácter del flujo. |
| int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) override | Lee el número especificado de caracteres del flujo, los convierte a codificación UTF-16 y escribe los caracteres UTF-16 resultantes en el arreglo de caracteres especificado comenzando en la posición indicada. |
| virtual int [ReadBlock](../textreader/readblock/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Lee el número máximo especificado de caracteres del lector de texto actual y escribe los datos en un búfer, comenzando en el índice especificado. |
| [String](../../system/string/) [ReadLine](./readline/)() override | Lee caracteres del flujo hasta el final de la línea actual. |
| [String](../../system/string/) [ReadToEnd](./readtoend/)() override | Lee caracteres del flujo hasta el final del flujo. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Construye una instancia del objeto [StreamReader](./) que lee caracteres del flujo subyacente especificado usando codificación UTF-8 y un búfer con tamaño predeterminado de 1024 bytes. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **bool**) | Construye una instancia del objeto [StreamReader](./) que lee caracteres del flujo subyacente especificado usando codificación UTF-8 y un búfer con tamaño predeterminado de 1024 bytes. Un parámetro especifica si debe habilitarse la detección de marca de orden de bytes. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Construye una instancia del objeto [StreamReader](./) que lee caracteres del flujo subyacente especificado usando la codificación especificada y un búfer con tamaño predeterminado de 1024 bytes. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | Construye una instancia del objeto [StreamReader](./) que lee caracteres del flujo subyacente especificado usando la codificación especificada y un búfer con tamaño predeterminado de 1024 bytes. Un parámetro especifica si debe habilitarse la detección de marca de orden de bytes. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | Construye una instancia del objeto [StreamReader](./) que lee caracteres del flujo subyacente especificado usando la codificación especificada y un búfer del tamaño especificado. Un parámetro especifica si debe habilitarse la detección de marca de orden de bytes. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&) | Construye una instancia del objeto [StreamReader](./) que lee caracteres del archivo especificado usando codificación UTF-8 y un búfer con tamaño predeterminado de 4096 bytes. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, **bool**) | Construye una instancia del objeto [StreamReader](./) que lee caracteres del archivo especificado usando codificación UTF-8 y un búfer con tamaño predeterminado de 4096 bytes. Un parámetro especifica si debe habilitarse la detección de marca de orden de bytes. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Construye una instancia del objeto [StreamReader](./) que lee caracteres del archivo especificado usando la codificación especificada y un búfer con tamaño predeterminado de 4096 bytes. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | Construye una instancia del objeto [StreamReader](./) que lee caracteres del flujo subyacente especificado usando la codificación especificada y un búfer con tamaño predeterminado de 4096 bytes. Un parámetro especifica si debe habilitarse la detección de marca de orden de bytes. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | Construye una instancia del objeto [StreamReader](./) que lee caracteres del archivo especificado usando la codificación especificada y un búfer del tamaño especificado. Un parámetro especifica si debe habilitarse la detección de marca de orden de bytes. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa el constructo C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |
|  [~StreamReader](./~streamreader/)() | Destructor. |

## Ver también

* Clase [TextReader](../textreader/)
* Espacio de nombres [System::IO](../)
* Biblioteca [Aspose.Slides](../../)