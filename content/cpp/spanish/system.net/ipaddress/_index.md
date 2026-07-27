---
title: IPAddress
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa la dirección IP. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use dicho puntero para pasarlo a funciones como argumento."
type: docs
weight: 326
url: /es/system.net/ipaddress/
---
## IPAddress clase

Representa la dirección IP. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use dicho puntero para pasarlo a funciones como argumento.

```cpp
class IPAddress : public System::Object
```

## Métodos

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para fines internos. |
| [System::Net::Sockets::AddressFamily](../../system.net.sockets/addressfamily/) [get_AddressFamily](./get_addressfamily/)() | Devuelve la familia de direcciones. |
| **bool** [get_IsIPv4MappedToIPv6](./get_isipv4mappedtoipv6/)() | Devuelve un valor que indica si la dirección es una dirección IPv4 y está mapeada a una dirección IPv6. |
| **bool** [get_IsIPv6LinkLocal](./get_isipv6linklocal/)() | Devuelve un valor que indica si la dirección es una dirección link-local IPv6. |
| **bool** [get_IsIPv6Multicast](./get_isipv6multicast/)() | Devuelve un valor que indica si la dirección es una dirección multicast IPv6 global. |
| **bool** [get_IsIPv6SiteLocal](./get_isipv6sitelocal/)() | Devuelve un valor que indica si la dirección es una dirección site-local IPv6. |
| **bool** [get_IsIPv6Teredo](./get_isipv6teredo/)() | Devuelve un valor que indica si la dirección es una dirección Teredo IPv6. |
| **int64_t** [get_ScopeId](./get_scopeid/)() | Obtiene el identificador de ámbito de la dirección IPv6. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetAddressBytes](./getaddressbytes/)() | Devuelve una matriz de bytes de la dirección IP. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| [ImplPtr](./implptr/) [GetImpl](./getimpl/)() const | Devuelve un puntero a la implementación. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Analogo de la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| static **int64_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int64_t**) | Convierte el orden de bytes del host especificado al correspondiente orden de bytes de red. |
| static **int32_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int32_t**) | Convierte el orden de bytes del host especificado al correspondiente orden de bytes de red. |
| static **int16_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int16_t**) | Convierte el orden de bytes del host especificado al correspondiente orden de bytes de red. |
|  [IPAddress](./ipaddress/)(**int64_t**) | Construye una nueva instancia. |
|  [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int64_t**) | Construye una nueva instancia. |
|  [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Construye una nueva instancia. |
|  [IPAddress](./ipaddress/)() | Construye una nueva instancia. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Analogo del operador C# 'is'. |
| static **bool** [IsLoopback](./isloopback/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>) | Devuelve un valor que indica si la dirección especificada es una dirección loopback. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la instrucción C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv4](./maptoipv4/)() | Mapea la dirección a la dirección IPv4. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv6](./maptoipv6/)() | Mapea la dirección a la dirección IPv6. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
| static **int64_t** [NetworkToHostOrder](./networktohostorder/)(**int64_t**) | Convierte el orden de bytes de red especificado al correspondiente orden de bytes del host. |
| static **int32_t** [NetworkToHostOrder](./networktohostorder/)(**int32_t**) | Convierte el orden de bytes de red especificado al correspondiente orden de bytes del host. |
| static **int16_t** [NetworkToHostOrder](./networktohostorder/)(**int16_t**) | Convierte el orden de bytes de red especificado al correspondiente orden de bytes del host. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la copia de construcción de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la copia de construcción de subclases. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [Parse](./parse/)([String](../../system/string/)) | Convierte una cadena pasada a una instancia de la clase [IPAddress](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_ScopeId](./set_scopeid/)(**int64_t**) | Establece el identificador de ámbito de la dirección IPv6. |
| void [SetImpl](./setimpl/)([ImplPtr](./implptr/)) | Establece un puntero a la implementación. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>\&) | Intenta convertir una cadena pasada a una instancia de la clase [IPAddress](./). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la instrucción C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Campos

| Field | Description |
| --- | --- |
| static [Any](./any/) | La dirección IPv4 que indica si el servidor debe escuchar todas las interfaces de red. |
| static [Broadcast](./broadcast/) | La dirección de broadcast IPv4. |
| static [IPv6Any](./ipv6any/) | La dirección IPv6 que indica si el servidor debe escuchar todas las interfaces de red. |
| static [IPv6Loopback](./ipv6loopback/) | La dirección loopback IPv6. |
| static [IPv6None](./ipv6none/) | La dirección IPv6 que indica que el servidor no debe escuchar ninguna interfaz de red. |
| static [Loopback](./loopback/) | La dirección loopback IPv4. |
| static [None](./none/) | La dirección IPv4 que indica que el servidor no debe escuchar ninguna interfaz de red. |

## Definiciones de tipos

| Typedef | Description |
| --- | --- |
| [ImplPtr](./implptr/) | Un puntero al tipo de implementación. |

## Ver también

* Clase [Object](../../system/object/)
* Espacio de nombres [System::Net](../)
* Biblioteca [Aspose.Slides](../../)