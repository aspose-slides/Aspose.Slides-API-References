---
title: BinaryReader
second_title: Referencia de la API de Aspose.Slides para C++
description: "Representa un lector que lee tipos de datos primitivos como datos binarios en una codificación concreta. Los objetos de esta clase sólo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento."
type: docs
weight: 92
url: /es/system.io/binaryreader/
---
## Clase BinaryReader

Representa un lector que lee tipos de datos primitivos como datos binarios en una codificación específica. Los objetos de esta clase sólo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class BinaryReader : public System::IDisposable
```

## Métodos

| Method | Description |
| --- | --- |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Construye una instancia de la clase [BinaryReader](./) que lee datos del flujo especificado usando codificación UTF-8. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Construye una instancia de la clase [BinaryReader](./) que lee datos del flujo especificado usando la codificación especificada. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&, **bool**) | Construye una instancia de la clase [BinaryReader](./) que lee datos del flujo especificado usando la codificación especificada. |
| virtual void [Close](./close/)() | Cierra el objeto [BinaryReader](./) actual y el flujo de entrada subyacente. |
| void [Dispose](./dispose/)() override | Libera todos los recursos usados por el objeto actual y cierra el flujo subyacente. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica [Object.Equals](../../system/object/equals/) de C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() | Devuelve el flujo de entrada. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada con el objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método [Object.GetHashCode()](../../system/object/gethashcode/) de C#. Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada [System.Object.GetType()](../../system/object/gettype/) de C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador 'is' de C#. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método [Object.MemberwiseClone()](../../system/object/memberwiseclone/) de C#. Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| virtual int [PeekChar](./peekchar/)() | Lee un solo carácter del flujo de entrada sin cambiar el cursor de lectura del flujo. |
| virtual int [Read](./read/)() | Lee un solo carácter del flujo de entrada. |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Lee el número especificado de bytes del flujo de entrada y los escribe en la matriz de bytes especificada. |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Lee el número especificado de caracteres del flujo de entrada, los convierte a codificación UTF-16 y escribe los caracteres UTF-16 resultantes en la matriz de caracteres especificada comenzando en la posición indicada. |
| virtual **bool** [ReadBoolean](./readboolean/)() | Lee un solo byte del flujo de entrada y devuelve su representación booleana. |
| virtual **uint8_t** [ReadByte](./readbyte/)() | Lee un solo byte del flujo de entrada. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadBytes](./readbytes/)(int) | Lee el número especificado de bytes del flujo de entrada. |
| virtual char_t [ReadChar](./readchar/)() | Lee un solo carácter del flujo de entrada. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [ReadChars](./readchars/)(int) | Lee el número especificado de caracteres del flujo de entrada y los devuelve en codificación UTF-16. |
| virtual [Decimal](../../system/decimal/) [ReadDecimal](./readdecimal/)() | NO IMPLEMENTADO. |
| virtual **double** [ReadDouble](./readdouble/)() | Lee 8 bytes del flujo de entrada y los devuelve como un valor de punto flotante de doble precisión. |
| virtual **int16_t** [ReadInt16](./readint16/)() | Lee 2 bytes del flujo de entrada y los devuelve como un valor entero de 16 bits. |
| virtual int [ReadInt32](./readint32/)() | Lee 4 bytes del flujo de entrada y los devuelve como un valor entero de 32 bits. |
| virtual **int64_t** [ReadInt64](./readint64/)() | Lee 8 bytes del flujo de entrada y los devuelve como un valor entero de 64 bits. |
| virtual **int8_t** [ReadSByte](./readsbyte/)() | Lee un solo byte del flujo de entrada y lo devuelve como un valor entero con signo de 8 bits. |
| virtual **float** [ReadSingle](./readsingle/)() | Lee 4 bytes del flujo de entrada y los devuelve como un valor de punto flotante de precisión simple. |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | Lee una cadena del flujo actual. La cadena está precedida por su longitud, codificada como un entero de siete bits a la vez. |
| virtual **uint16_t** [ReadUInt16](./readuint16/)() | Lee 2 bytes del flujo de entrada y los devuelve como un valor entero sin signo de 16 bits. |
| virtual **uint32_t** [ReadUInt32](./readuint32/)() | Lee 4 bytes del flujo de entrada y los devuelve como un valor entero sin signo de 32 bits. |
| virtual **uint64_t** [ReadUInt64](./readuint64/)() | Lee 8 bytes del flujo de entrada y los devuelve como un valor entero sin signo de 64 bits. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas por el valor especificado. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores al modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método [Object.ToString()](../../system/object/tostring/) de C#. Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~BinaryReader](./~binaryreader/)() | Destructor. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [IDisposable](../../system/idisposable/)
* Espacio de nombres [System::IO](../)
* Biblioteca [Aspose.Slides](../../)