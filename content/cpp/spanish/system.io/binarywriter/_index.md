---
title: BinaryWriter
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa un escritor que escribe valores de tipos primitivos en un flujo de bytes. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento."
type: docs
weight: 105
url: /es/system.io/binarywriter/
---
## BinaryWriter clase

Representa un escritor que escribe valores de tipos primitivos en un flujo de bytes. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y utilice este puntero para pasarlo a funciones como argumento.

```cpp
class BinaryWriter : public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
|  [BinaryWriter](./binarywriter/)(const [StreamPtr](../../system/streamptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | Construye una instancia de la clase [BinaryWriter](./) que escribe datos en el flujo especificado usando la codificación especificada. |
| void [Close](./close/)() | Cierra el objeto [BinaryWriter](./) actual y el flujo de salida subyacente. |
| void [Dispose](./dispose/)() override | Libera todos los recursos usados por el objeto actual y cierra el flujo subyacente. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para propósitos internos. |
| void [Flush](./flush/)() | Vacía el flujo de salida. |
| [StreamPtr](../../system/streamptr/) [get_BaseStream](./get_basestream/)() | Devuelve el flujo de salida. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite generar hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. No copia nada, realmente, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. No copia nada, realmente, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| **int64_t** [Seek](./seek/)(int, [System::IO::SeekOrigin](../seekorigin/)) | Establece la posición del flujo representado por el objeto actual. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual void [Write](./write/)(**uint8_t**) | Escribe el valor entero sin signo de 8 bits especificado en el flujo de salida. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Escribe el subrango especificado de bytes del arreglo de bytes indicado en el flujo de salida. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Escribe el subrango especificado de caracteres UTF-16 del arreglo de caracteres indicado en el flujo de salida. |
| virtual void [Write](./write/)(**bool**) | Escribe un byte único con valor 0 si **value** es 'true' y 1 si **value** es 'false' en el flujo de salida. |
| virtual void [Write](./write/)(char16_t) | Escribe el valor del carácter de ancho 16 bits especificado en el flujo de salida. |
| virtual void [Write](./write/)(**int16_t**) | Escribe el valor entero de 16 bits especificado en el flujo de salida. |
| virtual void [Write](./write/)(int) | Escribe el valor entero de 32 bits especificado en el flujo de salida. |
| virtual void [Write](./write/)(**int64_t**) | Escribe el valor entero de 64 bits especificado en el flujo de salida. |
| virtual void [Write](./write/)(**uint16_t**) | Escribe el valor entero sin signo de 16 bits especificado en el flujo de salida. |
| virtual void [Write](./write/)(**uint32_t**) | Escribe el valor entero sin signo de 32 bits especificado en el flujo de salida. |
| virtual void [Write](./write/)(**uint64_t**) | Escribe el valor entero sin signo de 64 bits especificado en el flujo de salida. |
| virtual void [Write](./write/)(**float**) | Escribe el valor de punto flotante de precisión simple especificado en el flujo de salida. |
| virtual void [Write](./write/)(**double**) | Escribe el valor de punto flotante de doble precisión especificado en el flujo de salida. |
| virtual void [Write](./write/)(const [Decimal](../../system/decimal/)\&) | Escribe la representación en bytes del valor [Decimal](../../system/decimal/) especificado en el flujo de salida. |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | Escribe una cadena con prefijo de longitud en la codificación actual al flujo de salida. |
| virtual void [Write](./write/)(const char_t *) | Escribe una cadena con prefijo de longitud en la codificación actual al flujo de salida. |
|  [~BinaryWriter](./~binarywriter/)() | Destructor. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [IDisposable](../../system/idisposable/)
* Espacio de nombres [System::IO](../)
* Biblioteca [Aspose.Slides](../../)