---
title: CacheControlHeaderValue
second_title: Referencia de la API de Aspose.Slides para C++
description: "Representa un valor del encabezado 'Cache-Control'. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento."
type: docs
weight: 14
url: /es/system.net.http.headers/cachecontrolheadervalue/
---
## CacheControlHeaderValue clase


Representa un valor del encabezado 'Cache-Control'. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class CacheControlHeaderValue : public System::ICloneable
```

## Métodos

| Método | Descripción |
| --- | --- |
|  [CacheControlHeaderValue](./cachecontrolheadervalue/)() | Construye una nueva instancia. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Extensions](./get_extensions/)() | Devuelve la colección de tokens de extensión de caché. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxAge](./get_maxage/)() | Obtiene el valor de edad máxima en segundos que determina el tiempo durante el cual el cliente aceptará una respuesta. |
| **bool** [get_MaxStale](./get_maxstale/)() | Obtiene el valor que determina si el cliente aceptará las respuestas expiradas. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxStaleLimit](./get_maxstalelimit/)() | Obtiene el valor en segundos que determina el tiempo durante el cual el cliente aceptará las respuestas expiradas. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MinFresh](./get_minfresh/)() | Obtiene el valor que determina la vida útil de frescura. |
| **bool** [get_MustRevalidate](./get_mustrevalidate/)() | Obtiene el valor que determina si el servidor requiere revalidación de una entrada de caché cuando esta se vuelve obsoleta. |
| **bool** [get_NoCache](./get_nocache/)() | Obtiene el valor que determina si el cliente aceptará una respuesta almacenada en caché. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_NoCacheHeaders](./get_nocacheheaders/)() | Obtiene la colección de nombres de campo en la directiva 'no-cache' del encabezado 'Cache-Control'. |
| **bool** [get_NoStore](./get_nostore/)() | Obtiene el valor que determina si una caché no debe almacenar ninguna parte de una solicitud o respuesta HTTP. |
| **bool** [get_NoTransform](./get_notransform/)() | Obtiene el valor que determina si una caché o proxy no debe cambiar ninguna parte del cuerpo de la entidad. |
| **bool** [get_OnlyIfCached](./get_onlyifcached/)() | Obtiene el valor que determina si el cliente debe usar solo entradas almacenadas en caché. |
| **bool** [get_Private](./get_private/)() | Obtiene el valor que determina si el mensaje de respuesta HTTP o su parte está destinado a un solo usuario y no debe ser almacenado en caché por una caché compartida. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_PrivateHeaders](./get_privateheaders/)() | Obtiene la colección de nombres de campo en la directiva 'private' del encabezado 'Cache-Control'. |
| **bool** [get_ProxyRevalidate](./get_proxyrevalidate/)() | Obtiene el valor que determina si el servidor requiere revalidación de una entrada de caché cuando se vuelve obsoleta para las cachés de agentes de usuario compartidos. |
| **bool** [get_Public](./get_public/)() | Obtiene el valor que determina si una respuesta HTTP puede ser almacenada en caché por cualquier caché. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_SharedMaxAge](./get_sharedmaxage/)() | Obtiene el valor de edad máxima compartida en segundos que sobrescribe la directiva 'max-age' del encabezado 'Cache-Control' o el encabezado 'Expires' para una caché compartida. |
| static **int32_t** [GetCacheControlLength](./getcachecontrollength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | Convierte una cadena pasada desde el índice especificado a una instancia de la clase [CacheControlHeaderValue](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hashing de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa la instrucción C# lock() bloqueando. Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. No copia nada, realmente, solo inicializa un nuevo objeto y permite la construcción de copias de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. No copia nada, realmente, solo inicializa un nuevo objeto y permite la construcción de copias de subclases. |
| static [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | Convierte una cadena pasada a una instancia de la clase [CacheControlHeaderValue](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_MaxAge](./set_maxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Establece el valor de edad máxima en segundos que determina el tiempo durante el cual el cliente aceptará una respuesta. |
| void [set_MaxStale](./set_maxstale/)(**bool**) | Establece el valor que determina si el cliente aceptará las respuestas expiradas. |
| void [set_MaxStaleLimit](./set_maxstalelimit/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Establece el valor en segundos que determina el tiempo durante el cual el cliente aceptará las respuestas expiradas. |
| void [set_MinFresh](./set_minfresh/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Establece el valor que determina la vida útil de frescura. |
| void [set_MustRevalidate](./set_mustrevalidate/)(**bool**) | Establece el valor que determina si el servidor requiere revalidación de una entrada de caché cuando esta se vuelve obsoleta. |
| void [set_NoCache](./set_nocache/)(**bool**) | Establece el valor que determina si el cliente aceptará una respuesta almacenada en caché. |
| void [set_NoStore](./set_nostore/)(**bool**) | Establece el valor que determina si una caché no debe almacenar ninguna parte de una solicitud o respuesta HTTP. |
| void [set_NoTransform](./set_notransform/)(**bool**) | Establece el valor que determina si una caché o proxy no debe cambiar ninguna parte del cuerpo de la entidad. |
| void [set_OnlyIfCached](./set_onlyifcached/)(**bool**) | Establece el valor que determina si el cliente debe usar solo entradas almacenadas en caché. |
| void [set_Private](./set_private/)(**bool**) | Establece el valor que determina si el mensaje de respuesta HTTP o su parte está destinado a un solo usuario y no debe ser almacenado en caché por una caché compartida. |
| void [set_ProxyRevalidate](./set_proxyrevalidate/)(**bool**) | Establece el valor que determina si el servidor requiere revalidación de una entrada de caché cuando se vuelve obsoleta para las cachés de agentes de usuario compartidos. |
| void [set_Public](./set_public/)(**bool**) | Establece el valor que determina si una respuesta HTTP puede ser almacenada en caché por cualquier caché. |
| void [set_SharedMaxAge](./set_sharedmaxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Establece el valor de edad máxima compartida en segundos que sobrescribe la directiva 'max-age' del encabezado 'Cache-Control' o el encabezado 'Expires' para una caché compartida. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | Intenta convertir una cadena pasada a una instancia de la clase [CacheControlHeaderValue](./). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa la instrucción C# lock() desbloqueando. Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [ICloneable](../../system/icloneable/)
* Espacio de nombres [System::Net::Http::Headers](../)
* Biblioteca [Aspose.Slides](../../)