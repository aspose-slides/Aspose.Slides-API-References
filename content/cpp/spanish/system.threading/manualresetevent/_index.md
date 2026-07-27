---
title: ManualResetEvent
second_title: Referencia de API de Aspose.Slides para C++
description: "Evento para notificar al hilo en espera que no se restablece automáticamente. Los objetos de esta clase deben asignarse solo mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento."
type: docs
weight: 144
url: /es/system.threading/manualresetevent/
---
## ManualResetEvent clase


Event to notify waiting thread that does not reset automatically. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ManualResetEvent : public System::Threading::EventWaitHandle
```


## Métodos

| Método | Descripción |
| --- | --- |
| virtual void [Close](../waithandle/close/)() | Libera cualquier recurso asociado al manejador. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo de C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo de C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
|  [EventWaitHandle](../eventwaithandle/eventwaithandle/)(**bool**, [EventResetMode](../eventresetmode/)) | Constructor. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| [wait_handle_t](../wait_handle_t/) [get_Handle](../waithandle/get_handle/)() | Obtiene el manejador. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método [Object.GetHashCode()](../../system/object/gethashcode/) de C#. Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada [System.Object.GetType()](../../system/object/gettype/) de C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador 'is' de C#. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../../system/lockcontext/). |
|  [ManualResetEvent](./manualresetevent/)(**bool**) | Constructor. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método [Object.MemberwiseClone()](../../system/object/memberwiseclone/) de C#. Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la copia de construcción de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la copia de construcción de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual **bool** [Reset](../eventwaithandle/reset/)() | Establece el evento en estado no señalizador. |
| virtual **bool** [Set](../eventwaithandle/set/)() | Establece el evento en estado señalizador. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Disminuye y devuelve el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método [Object.ToString()](../../system/object/tostring/) de C#. Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../../system/lockcontext/). |
| static **bool** [WaitAll](../waithandle/waitall/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[WaitHandle](../waithandle/)\>\>\&, int) | Espera a que todos los manejadores se activen. |
| static **bool** [WaitAll](../waithandle/waitall/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[WaitHandle](../waithandle/)\>\>\&, [TimeSpan](../../system/timespan/)) | Espera a que todos los manejadores se activen. |
| static **bool** [WaitAll](../waithandle/waitall/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[WaitHandle](../waithandle/)\>\>\&) | Espera a que todos los manejadores se activen. |
| static int [WaitAny](../waithandle/waitany/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[WaitHandle](../waithandle/)\>\>\&, int) | Espera a que cualquiera de los manejadores se active. |
| static int [WaitAny](../waithandle/waitany/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[WaitHandle](../waithandle/)\>\>\&, [TimeSpan](../../system/timespan/)) | Espera a que cualquiera de los manejadores se active. |
| static int [WaitAny](../waithandle/waitany/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[WaitHandle](../waithandle/)\>\>\&) | Espera a que cualquiera de los manejadores se active. |
| virtual **bool** [WaitOne](../waithandle/waitone/)() | Espera a que el manejador se active durante un período ilimitado. |
| virtual **bool** [WaitOne](../waithandle/waitone/)(int) | Espera a que el manejador se active. |
| virtual **bool** [WaitOne](../waithandle/waitone/)([TimeSpan](../../system/timespan/)) | Espera a que el manejador se active. |
| virtual **bool** [WaitOne](../waithandle/waitone/)(int, **bool**) | Espera a que el manejador se active. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Disminuye el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
|  [~EventWaitHandle](../eventwaithandle/~eventwaithandle/)() | Destructor. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |
| virtual  [~WaitHandle](../waithandle/~waithandle/)() | Destructor. |

## Campos

| Campo | Descripción |
| --- | --- |
| static [WaitTimeout](../waithandle/waittimeout/) | Valor especial que debe devolver la función, en caso contrario devuelve el índice del objeto señalizado en el arreglo, si el tiempo de espera supera el límite y nada señaliza. |

## Ver también

* Clase [EventWaitHandle](../eventwaithandle/)
* Espacio de nombres [System::Threading](../)
* Biblioteca [Aspose.Slides](../../)