---
title: AuthenticatedStream
second_title: Referencia de API de Aspose.Slides para C++
description: "Contiene los métodos para pasar credenciales a través de un flujo. Los objetos de esta clase sólo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento."
type: docs
weight: 1
url: /es/system.net.security/authenticatedstream/
---
## AuthenticatedStream clase

Contiene los métodos para pasar credenciales a través de un flujo. Los objetos de esta clase sólo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class AuthenticatedStream : public System::IO::Stream
```

## Métodos

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inicia una operación de lectura asíncrona. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inicia una operación de escritura asíncrona. |
| virtual void [Close](../../system.io/stream/close/)() | Cierra el flujo. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | Copia bytes al flujo especificado. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | Copia bytes al flujo especificado, usando el tamaño de búfer especificado. |
| void [Dispose](../../system.io/stream/dispose/)() override | Libera todos los recursos usados por el objeto actual y cierra el flujo. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Espera hasta que la operación de lectura asíncrona especificada finalice. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Finaliza una operación de escritura asíncrona. Espera hasta que la operación de escritura asíncrona especificada finalice. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de números de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de números de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| virtual void [Flush](../../system.io/stream/flush/)() | Limpia los búferes de este flujo y escribe todos los datos almacenados en búfer en el almacenamiento subyacente. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Limpia asíncronamente todos los búferes de este flujo, hace que los datos almacenados en búfer se escriban en el dispositivo subyacente y supervisa las solicitudes de cancelación. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | Limpia asíncronamente todos los búferes de este flujo, hace que los datos almacenados en búfer se escriban en el dispositivo subyacente y supervisa las solicitudes de cancelación. |
| virtual **bool** [get_CanRead](../../system.io/stream/get_canread/)() const | Determina si el flujo es legible. |
| virtual **bool** [get_CanSeek](../../system.io/stream/get_canseek/)() const | Determina si el flujo soporta búsqueda. |
| virtual **bool** [get_CanTimeout](../../system.io/stream/get_cantimeout/)() const | Obtiene un valor que determina si el flujo actual puede caducar. |
| virtual **bool** [get_CanWrite](../../system.io/stream/get_canwrite/)() const | Determina si el flujo es escribible. |
| virtual **bool** [get_IsAuthenticated](./get_isauthenticated/)() const | Devuelve un valor que indica si la autenticación se ha pasado con éxito. |
| virtual **bool** [get_IsEncrypted](./get_isencrypted/)() const | Devuelve un valor que indica si los datos enviados mediante este flujo están cifrados. |
| virtual **bool** [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const | Devuelve un valor que indica si un servidor y un cliente están autenticados. |
| virtual **bool** [get_IsServer](./get_isserver/)() const | Devuelve un valor que indica si el lado local de la conexión es el servidor. |
| virtual **bool** [get_IsSigned](./get_issigned/)() const | Devuelve un valor que indica si los datos enviados mediante este flujo están firmados. |
| **bool** [get_LeaveInnerStreamOpen](./get_leaveinnerstreamopen/)() const | Devuelve el flujo que es usado por las instancias actuales de la clase para enviar y recibir datos. |
| virtual **int64_t** [get_Length](../../system.io/stream/get_length/)() const | Devuelve la longitud del flujo en bytes. |
| virtual **int64_t** [get_Position](../../system.io/stream/get_position/)() const | Devuelve la posición actual del flujo. |
| virtual int [get_ReadTimeout](../../system.io/stream/get_readtimeout/)() const | Obtiene un valor, en milisegundos, que determina cuánto tiempo intentará el flujo leer antes de caducar. |
| virtual int [get_WriteTimeout](../../system.io/stream/get_writetimeout/)() const | Obtiene un valor, en milisegundos, que determina cuánto tiempo intentará el flujo escribir antes de caducar. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador 'is' de C#. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. Realmente no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. Realmente no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Lee la cantidad especificada de bytes del flujo y los escribe en el arreglo de bytes especificado. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Lee la cantidad especificada de bytes del flujo y los escribe en el arreglo de bytes especificado. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Lee la cantidad especificada de bytes del flujo y los escribe en el arreglo de bytes especificado. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Lee la cantidad especificada de bytes del flujo y los escribe en el segmento de bytes especificado. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Lee de forma asíncrona una secuencia de bytes del flujo actual, avanza la posición dentro del flujo por la cantidad de bytes leídos y supervisa las solicitudes de cancelación. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Lee de forma asíncrona una secuencia de bytes del flujo actual, avanza la posición dentro del flujo por la cantidad de bytes leídos y supervisa las solicitudes de cancelación. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | Lee un solo byte del flujo y devuelve un valor entero de 32 bits equivalente al valor del byte leído. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual **int64_t** [Seek](../../system.io/stream/seek/)(**int64_t**, [SeekOrigin](../../system.io/seekorigin/)) | Establece la posición del flujo representado por el objeto actual. |
| virtual void [set_Position](../../system.io/stream/set_position/)(**int64_t**) | Establece la posición del flujo. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | Establece un valor que determina si el flujo actual puede caducar. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | Establece un valor, en milisegundos, que determina cuánto tiempo intentará el flujo leer antes de caducar. |
| virtual void [SetLength](../../system.io/stream/setlength/)(**int64_t**) | Establece la longitud del flujo representado por el objeto actual. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual void [Write](../../system.io/stream/write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Escribe el subrango especificado de bytes del arreglo de bytes especificado al flujo. |
| virtual void [Write](../../system.io/stream/write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Escribe el subrango especificado de bytes del arreglo de bytes especificado al flujo. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Escribe el subrango especificado de bytes del arreglo de bytes especificado al flujo. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Escribe el subrango especificado de bytes del segmento de bytes especificado al flujo. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Escribe de forma asíncrona una secuencia de bytes al flujo actual, avanza la posición actual dentro de este flujo por la cantidad de bytes escritos y supervisa las solicitudes de cancelación. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Escribe de forma asíncrona una secuencia de bytes al flujo actual, avanza la posición actual dentro de este flujo por la cantidad de bytes escritos y supervisa las solicitudes de cancelación. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | Escribe el valor entero sin signo de 8 bits especificado al flujo. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Campos

| Field | Description |
| --- | --- |
| static [Null](../../system.io/stream/null/) | Un flujo sin almacenamiento subyacente. |

## Ver también

* Clase [Stream](../../system.io/stream/)
* Espacio de nombres [System::Net::Security](../)
* Biblioteca [Aspose.Slides](../../)