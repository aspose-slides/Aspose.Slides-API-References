---
title: HttpWebRequest
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa la solicitud web HTTP. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento."
type: docs
weight: 274
url: /es/system.net/httpwebrequest/
---
## HttpWebRequest clase

Representa la solicitud web HTTP. Objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class HttpWebRequest : public System::Net::WebRequest
```

## Métodos

| Método | Descripción |
| --- | --- |
| void [Abort](./abort/)() override | Aborta la solicitud actual. |
| virtual void [AddRange](./addrange/)(**int32_t**) | Agrega el encabezado '[Range](../../system/range/)' a la solicitud actual. |
| virtual void [AddRange](./addrange/)([System::String](../../system/string/), **int32_t**, **int32_t**) | Agrega el encabezado '[Range](../../system/range/)' a la solicitud actual. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetRequestStream](./begingetrequeststream/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Inicia una operación asincrónica para obtener un flujo para escribir datos en el recurso. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetResponse](./begingetresponse/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Inicia una solicitud asincrónica para el recurso. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([String](../../system/string/)) | Crea una nueva instancia de la clase [WebRequest](../webrequest/) usando el URI especificado. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Crea una nueva instancia de la clase [WebRequest](../webrequest/) usando el URI especificado. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [CreateDefault](../webrequest/createdefault/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Crea un descendiente [WebRequest](../webrequest/) para el esquema de URI especificado. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([String](../../system/string/)) | Crea una nueva instancia de la clase [WebRequest](../webrequest/) usando el URI especificado. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Crea una nueva instancia de la clase [WebRequest](../webrequest/) usando el URI especificado. |
| [System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [EndGetRequestStream](./endgetrequeststream/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Espera hasta que la operación asincrónica especificada para obtener un flujo se complete. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [EndGetResponse](./endgetresponse/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Espera hasta que la solicitud asincrónica especificada para el recurso se complete. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| [String](../../system/string/) [get_Accept](./get_accept/)() | Obtiene el valor del encabezado HTTP 'Accept'. |
| virtual **bool** [get_AllowAutoRedirect](./get_allowautoredirect/)() | Obtiene un valor que indica si la solicitud debe seguir redirecciones. |
| virtual **bool** [get_AllowReadStreamBuffering](./get_allowreadstreambuffering/)() | Obtiene un valor que indica si los datos recibidos del recurso deben almacenarse en búfer. |
| virtual **bool** [get_AllowWriteStreamBuffering](./get_allowwritestreambuffering/)() | Obtiene un valor que indica si el almacenamiento en búfer está habilitado para enviar datos. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\> [get_CachePolicy](../webrequest/get_cachepolicy/)() | Obtiene la política de caché. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](./get_clientcertificates/)() | Obtiene la colección de certificados asociados con la solicitud actual. |
| [System::String](../../system/string/) [get_ConnectionGroupName](./get_connectiongroupname/)() override | Obtiene el nombre del grupo de conexión. |
| **int64_t** [get_ContentLength](./get_contentlength/)() override | Obtiene el número de bytes de los datos de la solicitud a enviar. |
| [String](../../system/string/) [get_ContentType](./get_contenttype/)() override | Obtiene el tipo MIME de la solicitud. |
| **int32_t** [get_ContinueTimeout](./get_continuetimeout/)() | Obtiene un tiempo de espera para esperar hasta que se reciba el código de estado 100-Continue. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\> [get_CookieContainer](./get_cookiecontainer/)() | Obtiene un contenedor de cookies asociado con la solicitud web actual. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](./get_credentials/)() override | Obtiene la información de autenticación asociada con la solicitud actual. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_DefaultWebProxy](../webrequest/get_defaultwebproxy/)() | Obtiene el proxy HTTP global. |
| virtual **bool** [get_HaveResponse](./get_haveresponse/)() | Devuelve un valor que indica si se recibió una respuesta. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\> [get_Headers](./get_headers/)() override | Obtiene la colección de encabezados HTTP. |
| virtual **bool** [get_KeepAlive](./get_keepalive/)() | Obtiene un valor que indica si la solicitud actual debe contener el encabezado 'Keep-Alive'. |
| virtual int [get_MaximumAutomaticRedirections](./get_maximumautomaticredirections/)() | Obtiene el número máximo de redirecciones permitidas. |
| [String](../../system/string/) [get_Method](./get_method/)() override | Obtiene el método HTTP. |
| **bool** [get_PreAuthenticate](./get_preauthenticate/)() override | Obtiene un valor que indica si la solicitud debe estar preautenticada. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\> [get_PrefixList](../webrequest/get_prefixlist/)() | Obtiene la lista de prefijos. |
| [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_Proxy](./get_proxy/)() override | Obtiene el proxy HTTP. |
| virtual [System::String](../../system/string/) [get_Referer](./get_referer/)() | Obtiene el valor del encabezado 'Referer'. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_RequestUri](./get_requesturi/)() override | Devuelve el URI de la solicitud. |
| virtual **bool** [get_SendChunked](./get_sendchunked/)() | Obtiene un valor que indica si los datos deben enviarse en segmentos. |
| [System::SharedPtr](../../system/sharedptr/)\<[ServicePoint](../servicepoint/)\> [get_ServicePoint](./get_servicepoint/)() | Devuelve un punto de servicio que representa la conexión de red al recurso. |
| virtual **bool** [get_SupportsCookieContainer](./get_supportscookiecontainer/)() | Devuelve un valor que indica si la solicitud actual puede usar un contenedor de cookies. |
| **int32_t** [get_Timeout](./get_timeout/)() override | Obtiene una cantidad de tiempo en milisegundos después de la cual la solicitud expirará. |
| **bool** [get_UseDefaultCredentials](./get_usedefaultcredentials/)() override | Obtiene un valor que indica si la propiedad 'Credential' es igual a la propiedad 'DefaultCredentials'. |
| virtual [System::String](../../system/string/) [get_UserAgent](./get_useragent/)() | Obtiene el valor del encabezado 'User-Agent'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [GetRequestStream](./getrequeststream/)() override | Devuelve el flujo para escribir datos en el recurso. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [GetResponse](./getresponse/)() override | Devuelve la respuesta web asociada con la solicitud web actual. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| [HttpWebRequest](./httpwebrequest/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Construye una nueva instancia. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
| [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias en subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias en subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| static **bool** [RegisterPrefix](../webrequest/registerprefix/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IWebRequestCreate](../iwebrequestcreate/)\>) | Registra el descendiente [WebRequest](../webrequest/) para el URI especificado. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_Accept](./set_accept/)([String](../../system/string/)) | Establece el valor del encabezado HTTP 'Accept'. |
| virtual void [set_AllowAutoRedirect](./set_allowautoredirect/)(**bool**) | Establece un valor que indica si la solicitud debe seguir redirecciones. |
| virtual void [set_AllowReadStreamBuffering](./set_allowreadstreambuffering/)(**bool**) | Establece un valor que indica si los datos recibidos del recurso deben almacenarse en búfer. |
| virtual void [set_AllowWriteStreamBuffering](./set_allowwritestreambuffering/)(**bool**) | Establece un valor que indica si el almacenamiento en búfer está habilitado para enviar datos. |
| virtual void [set_CachePolicy](../webrequest/set_cachepolicy/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\>) | Establece la política de caché. |
| virtual void [set_ClientCertificates](./set_clientcertificates/)([System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>) | Establece la colección de certificados asociados con la solicitud actual. |
| void [set_ConnectionGroupName](./set_connectiongroupname/)([System::String](../../system/string/)) override | Establece el nombre del grupo de conexión. |
| void [set_ContentLength](./set_contentlength/)(**int64_t**) override | Establece el número de bytes de los datos de la solicitud a enviar. |
| void [set_ContentType](./set_contenttype/)([String](../../system/string/)) override | Establece el tipo MIME de la solicitud. |
| void [set_ContinueTimeout](./set_continuetimeout/)(**int32_t**) | Establece un tiempo de espera para esperar hasta que se reciba el código de estado 100-Continue. |
| virtual void [set_CookieContainer](./set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\>) | Establece un contenedor de cookies asociado con la solicitud web actual. |
| void [set_Credentials](./set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) override | Establece la información de autenticación asociada con la solicitud actual. |
| static void [set_DefaultWebProxy](../webrequest/set_defaultwebproxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | Establece el proxy HTTP global. |
| void [set_Headers](./set_headers/)([System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\>) override | Establece la colección de encabezados HTTP. |
| virtual void [set_KeepAlive](./set_keepalive/)(**bool**) | Establece un valor que indica si la solicitud actual debe contener el encabezado 'Keep-Alive'. |
| virtual void [set_MaximumAutomaticRedirections](./set_maximumautomaticredirections/)(int) | Establece un número máximo de redirecciones permitidas. |
| void [set_Method](./set_method/)([String](../../system/string/)) override | Establece el método HTTP. |
| void [set_PreAuthenticate](./set_preauthenticate/)(**bool**) override | Establece un valor que indica si la solicitud debe estar preautenticada. |
| static void [set_PrefixList](../webrequest/set_prefixlist/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\>) | Establece la lista de prefijos. |
| void [set_ProtocolVersion](./set_protocolversion/)([System::Version](../../system/version/)) | Establece la versión del HTTP. |
| void [set_Proxy](./set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) override | Establece el proxy HTTP. |
| virtual void [set_Referer](./set_referer/)([System::String](../../system/string/)) | Establece el valor del encabezado 'Referer'. |
| virtual void [set_SendChunked](./set_sendchunked/)(**bool**) | Establece un valor que indica si los datos deben enviarse en segmentos. |
| void [set_Timeout](./set_timeout/)(int) override | Establece una cantidad de tiempo en milisegundos después de la cual la solicitud expirará. |
| virtual void [set_Timeout](../webrequest/set_timeout/)(**int32_t**) | Establece una cantidad de tiempo en milisegundos después de la cual la solicitud expirará. |
| void [set_UseDefaultCredentials](./set_usedefaultcredentials/)(**bool**) override | Establece un valor que indica si la propiedad 'Credential' es igual a la propiedad 'DefaultCredentials'. |
| virtual void [set_UserAgent](./set_useragent/)([System::String](../../system/string/)) | Establece el valor del encabezado 'User-Agent'. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [WebRequest](../webrequest/)
* Espacio de nombres [System::Net](../)
* Biblioteca [Aspose.Slides](../../)