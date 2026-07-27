---
title: FileStream
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa un flujo de archivo que admite operaciones de lectura y escritura síncronas y asíncronas. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a las funciones como argumento."
type: docs
weight: 287
url: /es/system.io/filestream/
---
## FileStream clase

Representa una secuencia de archivo que admite operaciones de lectura y escritura síncronas y asíncronas. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a las funciones como argumento.

```cpp
class FileStream : public System::IO::Stream
```

## Métodos

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inicia una operación de lectura asíncrona. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inicia una operación de escritura asíncrona. |
| void [Close](./close/)() override | Cierra el objeto [FileStream](./) actual. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Copia bytes al flujo especificado. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Copia bytes al flujo especificado, usando el tamaño del búfer especificado. |
| void [Dispose](../stream/dispose/)() override | Libera todos los recursos utilizados por el objeto actual y cierra el flujo. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Espera hasta que la operación de lectura asíncrona especificada se complete. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Finaliza una operación de escritura asíncrona. Espera hasta que la operación de escritura asíncrona especificada se complete. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aun cuando según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aun cuando según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para usos internos. |
|  [FileStream](./filestream/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | Construye una nueva instancia de la clase [FileStream](./) y la inicializa con los parámetros especificados. |
|  [FileStream](./filestream/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/), **int32_t**, [FileOptions](../fileoptions/)) | Construye una nueva instancia de la clase [FileStream](./) y la inicializa con los parámetros especificados. |
|  [FileStream](./filestream/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/), **int32_t**, **bool**) | Construye una nueva instancia de la clase [FileStream](./) y la inicializa con los parámetros especificados. |
|  [FileStream](./filestream/)(const [FileStream](./)\&) |  |
| void [Flush](./flush/)() override | Borra los búferes de este flujo y escribe todos los datos almacenados en el archivo subyacente. |
| void [Flush](./flush/)(**bool**) | Borra los búferes de este flujo y escribe todos los datos almacenados en el archivo subyacente. Sinónimo del método [Flush()](./flush/). |
| [TaskPtr](../../system/taskptr/) [FlushAsync](./flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) override | La borra asíncronamente todos los búferes de este flujo, hace que cualquier dato almacenado se escriba en el dispositivo subyacente y supervisa las solicitudes de cancelación. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | La borra asíncronamente todos los búferes de este flujo, hace que cualquier dato almacenado se escriba en el dispositivo subyacente y supervisa las solicitudes de cancelación. |
| **bool** [get_CanRead](./get_canread/)() const override | Determina si el flujo es legible. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Determina si el flujo admite búsqueda. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Obtiene un valor que determina si el flujo actual puede expirar. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Determina si el flujo es escribible. |
| **int64_t** [get_Length](./get_length/)() const override | Devuelve la longitud del flujo en bytes. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Devuelve el nombre del archivo encapsulado por el objeto [FileStream](./) actual. |
| **int64_t** [get_Position](./get_position/)() const override | Devuelve la posición actual del flujo. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Obtiene un valor, en milisegundos, que determina cuánto tiempo intentará el flujo leer antes de expirar. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Obtiene un valor, en milisegundos, que determina cuánto tiempo intentará el flujo escribir antes de expirar. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite generar hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [FileStream](./)\& [operator=](./operator_equal/)(const [FileStream](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Lee el número especificado de bytes del flujo y los escribe en la matriz de bytes especificada. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Lee el número especificado de bytes del flujo y los escribe en la matriz de bytes especificada. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Lee el número especificado de bytes del flujo y los escribe en la matriz de bytes especificada. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Lee el número especificado de bytes del flujo y los escribe en el span de bytes especificado. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](./readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) override | Lee de forma asíncrona una secuencia de bytes del flujo actual, avanza la posición dentro del flujo en la cantidad de bytes leídos y supervisa las solicitudes de cancelación. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Lee de forma asíncrona una secuencia de bytes del flujo actual, avanza la posición dentro del flujo en la cantidad de bytes leídos y supervisa las solicitudes de cancelación. |
| **int32_t** [ReadByte](./readbyte/)() override | Lee un solo byte del flujo y devuelve un valor entero de 32 bits equivalente al valor del byte leído. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Establece la posición del flujo representado por el objeto actual. |
| void [set_Position](./set_position/)(**int64_t**) override | Vacía el flujo y luego establece la posición del flujo. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Establece un valor que determina si el flujo actual puede expirar. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Establece un valor, en milisegundos, que determina cuánto tiempo intentará el flujo leer antes de expirar. |
| void [SetLength](./setlength/)(**int64_t**) override | Establece la longitud del flujo representado por el objeto actual. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores al modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Escribe el subrango especificado de bytes del arreglo de bytes especificado al flujo. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Escribe el subrango especificado de bytes del arreglo de bytes especificado al flujo. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Escribe el subrango especificado de bytes del arreglo de bytes especificado al flujo. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Escribe el subrango especificado de bytes del span de bytes especificado al flujo. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](./writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) override | Escribe de forma asíncrona una secuencia de bytes al flujo actual, avanza la posición actual dentro de este flujo en la cantidad de bytes escritos y supervisa las solicitudes de cancelación. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Escribe de forma asíncrona una secuencia de bytes al flujo actual, avanza la posición actual dentro de este flujo en la cantidad de bytes escritos y supervisa las solicitudes de cancelación. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | Escribe el valor entero sin signo de 8 bits especificado al flujo. |
|  [~FileStream](./~filestream/)() | Destructor. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Campos

| Field | Description |
| --- | --- |
| static constexpr [DefaultBufferSize](./defaultbuffersize/) | Valor predeterminado del número de bytes almacenados en búfer durante las operaciones de lectura y escritura. |
| static [Null](../stream/null/) | Un flujo sin almacenamiento subyacente. |

## Ver también

* Clase [Stream](../stream/)
* Espacio de nombres [System::IO](../)
* Biblioteca [Aspose.Slides](../../)