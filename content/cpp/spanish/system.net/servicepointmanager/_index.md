---
title: ServicePointManager
second_title: Referencia de la API de Aspose.Slides para C++
description: "Gestiona las etapas del ciclo de vida (creación, mantenimiento y eliminación) de las instancias de la clase ServicePoint. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use dicho puntero para pasarlo a las funciones como argumento."
type: docs
weight: 430
url: /es/system.net/servicepointmanager/
---
## ServicePointManager clase


Gestiona las etapas del ciclo de vida (creación, mantenimiento y eliminación) de las instancias de la clase [ServicePoint](../servicepoint/). Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y utilice este puntero para pasarlo a funciones como argumento.

```cpp
class ServicePointManager : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo de C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo de C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo de C# donde dos NaNs se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo de C# donde dos NaNs se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| static [System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\> [get_CertificatePolicy](./get_certificatepolicy/)() | Obtiene una política de certificado. |
| static **bool** [get_CheckCertificateRevocationList](./get_checkcertificaterevocationlist/)() | Obtiene un valor que indica si el certificado debe verificarse contra la lista de revocación de la autoridad certificadora. |
| static **int32_t** [get_DefaultConnectionLimit](./get_defaultconnectionlimit/)() | Obtiene el número máximo de conexiones concurrentes que están permitidas por las instancias de ServicePoint-class. |
| static **int32_t** [get_DnsRefreshTimeout](./get_dnsrefreshtimeout/)() | Obtiene un tiempo de espera en milisegundos durante el cual una resolución DNS se considera válida. |
| static **bool** [get_EnableDnsRoundRobin](./get_enablednsroundrobin/)() | Obtiene un valor que indica si una resolución DNS rota entre las direcciones IP aplicables. |
| static [System::Net::Security::EncryptionPolicy](../../system.net.security/encryptionpolicy/) [get_EncryptionPolicy](./get_encryptionpolicy/)() | Devuelve la política de cifrado que utiliza la instancia actual. |
| static **bool** [get_Expect100Continue](./get_expect100continue/)() | Obtiene un valor que indica si las instancias de ServicePoint-class usan el comportamiento 100-Continue. |
| static **int32_t** [get_MaxServicePointIdleTime](./get_maxservicepointidletime/)() | Obtiene el tiempo máximo inactivo de las instancias de ServicePoint-class. |
| static **int32_t** [get_MaxServicePoints](./get_maxservicepoints/)() | Obtiene el número máximo de instancias de ServicePoint-class que pueden ser gestionadas por la instancia actual. |
| static **bool** [get_ReusePort](./get_reuseport/)() | Obtiene un valor que indica si los sockets de conexiones de salida usan la opción 'SO_REUSE_UNICASTPORT'. |
| static [SecurityProtocolType](../securityprotocoltype/) [get_SecurityProtocol](./get_securityprotocol/)() | Obtiene el tipo de protocolo de seguridad usado por las instancias de ServicePoint-class que son gestionadas por la instancia actual. |
| static [Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/) [get_ServerCertificateValidationCallback](./get_servercertificatevalidationcallback/)() | Obtiene la función de devolución de llamada que se usa para validar un certificado de servidor. |
| static **bool** [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | Obtiene un valor que indica si las instancias de ServicePoint-class usan el algoritmo Nagle. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas por el valor especificado. |
| static void [set_CertificatePolicy](./set_certificatepolicy/)([System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\>) | Establece una política de certificado. |
| static void [set_CheckCertificateRevocationList](./set_checkcertificaterevocationlist/)(**bool**) | Establece un valor que indica si el certificado debe verificarse contra la lista de revocación de la autoridad certificadora. |
| static void [set_DefaultConnectionLimit](./set_defaultconnectionlimit/)(**int32_t**) | Establece el número máximo de conexiones concurrentes que están permitidas por las instancias de ServicePoint-class. |
| static void [set_DnsRefreshTimeout](./set_dnsrefreshtimeout/)(**int32_t**) | Establece un tiempo de espera en milisegundos durante el cual una resolución DNS se considera válida. |
| static void [set_EnableDnsRoundRobin](./set_enablednsroundrobin/)(**bool**) | Establece un valor que indica si una resolución DNS rota entre las direcciones IP aplicables. |
| static void [set_Expect100Continue](./set_expect100continue/)(**bool**) | Establece un valor que indica si las instancias de ServicePoint-class usan el comportamiento 100-Continue. |
| static void [set_MaxServicePointIdleTime](./set_maxservicepointidletime/)(**int32_t**) | Establece el tiempo máximo inactivo de las instancias de ServicePoint-class. |
| static void [set_MaxServicePoints](./set_maxservicepoints/)(**int32_t**) | Establece el número máximo de instancias de ServicePoint-class que pueden ser gestionadas por la instancia actual. |
| static void [set_ReusePort](./set_reuseport/)(**bool**) | Establece un valor que indica si los sockets de conexiones de salida usan la opción 'SO_REUSE_UNICASTPORT'. |
| static void [set_SecurityProtocol](./set_securityprotocol/)([SecurityProtocolType](../securityprotocoltype/)) | Establece el tipo de protocolo de seguridad usado por las instancias de ServicePoint-class que son gestionadas por la instancia actual. |
| static void [set_ServerCertificateValidationCallback](./set_servercertificatevalidationcallback/)([Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/)) | Establece la función de devolución de llamada que se usa para validar un certificado de servidor. |
| static void [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(**bool**) | Establece un valor que indica si las instancias de ServicePoint-class usan el algoritmo Nagle. |
| static void [SetTcpKeepAlive](./settcpkeepalive/)(**bool**, **int32_t**, **int32_t**) | Establece el valor que indica si la opción 'Keep-Alive' está habilitada. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Campos

| Campo | Descripción |
| --- | --- |
| static [DefaultNonPersistentConnectionLimit](./defaultnonpersistentconnectionlimit/) | El número predeterminado de conexiones no persistentes. |
| static [DefaultPersistentConnectionLimit](./defaultpersistentconnectionlimit/) | El número predeterminado de conexiones persistentes. |

## Véase también

* Clase [Object](../../system/object/)
* Espacio de nombres [System::Net](../)
* Biblioteca [Aspose.Slides](../../)