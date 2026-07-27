---
title: Dns
second_title: Referencia de API de Aspose.Slides para C++
description: Proporciona métodos para trabajar con DNS.
type: docs
weight: 105
url: /es/system.net/dns/
---
## Dns clase

Proporciona métodos para trabajar con DNS.

```cpp
class Dns : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetHostAddresses](./begingethostaddresses/)([String](../../system/string/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Inicia una operación asíncrona para crear una nueva instancia de IPHostEntry-clase utilizando la cadena especificada que contiene un nombre de host o una dirección IP. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetHostByName](./begingethostbyname/)([String](../../system/string/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Inicia una operación asíncrona para crear una nueva instancia de IPHostEntry-clase utilizando el nombre de host especificado. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetHostEntry](./begingethostentry/)([String](../../system/string/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Inicia una operación asíncrona para crear una nueva instancia de IPHostEntry-clase utilizando la cadena especificada que contiene un nombre de host o una dirección IP. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetHostEntry](./begingethostentry/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../ipaddress/)\>, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Inicia una operación asíncrona para crear una nueva instancia de IPHostEntry-clase utilizando la dirección IP especificada. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginResolve](./beginresolve/)([String](../../system/string/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Inicia una operación asíncrona para crear una nueva instancia de IPHostEntry-clase utilizando el nombre de host especificado. |
|  [Dns](./dns/)() | El constructor predeterminado eliminado. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../ipaddress/)\>\> [EndGetHostAddresses](./endgethostaddresses/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Espera hasta que la operación asíncrona especificada para crear una nueva instancia de IPHostEntry-clase se complete. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [EndGetHostByName](./endgethostbyname/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Espera hasta que la operación asíncrona especificada para crear una nueva instancia de IPHostEntry-clase se complete. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [EndGetHostEntry](./endgethostentry/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Espera hasta que la operación asíncrona especificada para crear una nueva instancia de IPHostEntry-clase se complete. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [EndResolve](./endresolve/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Espera hasta que la operación asíncrona especificada para crear una nueva instancia de IPHostEntry-clase se complete. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../ipaddress/)\>\> [GetHostAddresses](./gethostaddresses/)([String](../../system/string/)) | Devuelve una colección de direcciones IP del nombre de host o dirección IP especificados. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [GetHostByAddress](./gethostbyaddress/)([String](../../system/string/)) | Crea una nueva instancia de IPHostEntry-clase utilizando la representación en cadena especificada de una dirección IP. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [GetHostByAddress](./gethostbyaddress/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../ipaddress/)\>) | Crea una nueva instancia de IPHostEntry-clase utilizando la dirección IP especificada. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [GetHostByName](./gethostbyname/)([String](../../system/string/)) | Crea una nueva instancia de IPHostEntry-clase utilizando el nombre de host especificado. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [GetHostEntry](./gethostentry/)([String](../../system/string/)) | Crea una nueva instancia de IPHostEntry-clase utilizando la cadena especificada que contiene un nombre de host o una dirección IP. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [GetHostEntry](./gethostentry/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../ipaddress/)\>) | Crea una nueva instancia de IPHostEntry-clase utilizando la dirección IP especificada. |
| static [String](../../system/string/) [GetHostName](./gethostname/)() | Devuelve el nombre de host de la máquina local. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [Resolve](./resolve/)([String](../../system/string/)) | Crea una nueva instancia de IPHostEntry-clase utilizando el nombre de host especificado. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en los contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [Object](../../system/object/)
* Espacio de nombres [System::Net](../)
* Biblioteca [Aspose.Slides](../../)