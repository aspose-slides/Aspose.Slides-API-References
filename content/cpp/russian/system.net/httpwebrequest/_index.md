---
title: HttpWebRequest
second_title: Справка API Aspose.Slides для C++
description: "Представляет HTTP запрос. Объекты этого класса следует создавать только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 274
url: /ru/system.net/httpwebrequest/
---
## HttpWebRequest класс

Представляет HTTP веб-запрос. Объекты этого класса следует создавать только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class HttpWebRequest : public System::Net::WebRequest
```

## Методы

| Метод | Описание |
| --- | --- |
| void [Abort](./abort/)() override | Прерывает текущий запрос. |
| virtual void [AddRange](./addrange/)(**int32_t**) | Добавляет заголовок 'Range' к текущему запросу. |
| virtual void [AddRange](./addrange/)([System::String](../../system/string/), **int32_t**, **int32_t**) | Добавляет заголовок 'Range' к текущему запросу. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetRequestStream](./begingetrequeststream/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Инициирует асинхронную операцию получения потока для записи данных в ресурс. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetResponse](./begingetresponse/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Инициирует асинхронный запрос к ресурсу. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([String](../../system/string/)) | Создаёт новый экземпляр класса [WebRequest](../webrequest/) с использованием указанного URI. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Создаёт новый экземпляр класса [WebRequest](../webrequest/) с использованием указанного URI. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [CreateDefault](../webrequest/createdefault/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Создаёт наследника [WebRequest](../webrequest/) для указанной схемы URI. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([String](../../system/string/)) | Создаёт новый экземпляр класса [WebRequest](../webrequest/) с использованием указанного URI. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Создаёт новый экземпляр класса [WebRequest](../webrequest/) с использованием указанного URI. |
| [System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [EndGetRequestStream](./endgetrequeststream/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Ожидает завершения указанной асинхронной операции получения потока. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [EndGetResponse](./endgetresponse/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Ожидает завершения указанного асинхронного запроса к ресурсу. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типо значений в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| [String](../../system/string/) [get_Accept](./get_accept/)() | Получает значение заголовка HTTP 'Accept'. |
| virtual **bool** [get_AllowAutoRedirect](./get_allowautoredirect/)() | Получает значение, указывающее, следует ли запросу следовать перенаправлениям. |
| virtual **bool** [get_AllowReadStreamBuffering](./get_allowreadstreambuffering/)() | Получает значение, указывающее, должны ли полученные от ресурса данные буферизоваться. |
| virtual **bool** [get_AllowWriteStreamBuffering](./get_allowwritestreambuffering/)() | Получает значение, указывающее, включено ли буферизование при отправке данных. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\> [get_CachePolicy](../webrequest/get_cachepolicy/)() | Получает политику кэширования. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](./get_clientcertificates/)() | Получает коллекцию сертификатов, связанных с текущим запросом. |
| [System::String](../../system/string/) [get_ConnectionGroupName](./get_connectiongroupname/)() override | Получает имя группы соединений. |
| **int64_t** [get_ContentLength](./get_contentlength/)() override | Получает количество байтов данных запроса для отправки. |
| [String](../../system/string/) [get_ContentType](./get_contenttype/)() override | Получает MIME-тип запроса. |
| **int32_t** [get_ContinueTimeout](./get_continuetimeout/)() | Получает тайм-аут ожидания получения кода состояния 100-Continue. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\> [get_CookieContainer](./get_cookiecontainer/)() | Получает контейнер cookie, связанный с текущим веб-запросом. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](./get_credentials/)() override | Получает информацию об аутентификации, связанную с текущим запросом. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_DefaultWebProxy](../webrequest/get_defaultwebproxy/)() | Получает глобальный HTTP-прокси. |
| virtual **bool** [get_HaveResponse](./get_haveresponse/)() | Возвращает значение, указывающее, получен ли ответ. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\> [get_Headers](./get_headers/)() override | Получает коллекцию заголовков HTTP. |
| virtual **bool** [get_KeepAlive](./get_keepalive/)() | Получает значение, указывающее, должен ли текущий запрос содержать заголовок 'Keep-Alive'. |
| virtual int [get_MaximumAutomaticRedirections](./get_maximumautomaticredirections/)() | Получает максимальное количество разрешённых перенаправлений. |
| [String](../../system/string/) [get_Method](./get_method/)() override | Получает HTTP-метод. |
| **bool** [get_PreAuthenticate](./get_preauthenticate/)() override | Получает значение, указывающее, должен ли запрос быть предварительно аутентифицирован. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\> [get_PrefixList](../webrequest/get_prefixlist/)() | Получает список префиксов. |
| [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_Proxy](./get_proxy/)() override | Получает HTTP-прокси. |
| virtual [System::String](../../system/string/) [get_Referer](./get_referer/)() | Получает значение заголовка 'Referer'. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_RequestUri](./get_requesturi/)() override | Возвращает URI запроса. |
| virtual **bool** [get_SendChunked](./get_sendchunked/)() | Получает значение, указывающее, должны ли данные отправляться сегментами. |
| [System::SharedPtr](../../system/sharedptr/)\<[ServicePoint](../servicepoint/)\> [get_ServicePoint](./get_servicepoint/)() | Возвращает объект service point, представляющий сетевое соединение с ресурсом. |
| virtual **bool** [get_SupportsCookieContainer](./get_supportscookiecontainer/)() | Возвращает значение, указывающее, может ли текущий запрос использовать контейнер cookie. |
| **int32_t** [get_Timeout](./get_timeout/)() override | Получает период времени в миллисекундах, после которого запрос завершится с тайм-аутом. |
| **bool** [get_UseDefaultCredentials](./get_usedefaultcredentials/)() override | Получает значение, указывающее, равно ли свойство 'Credential' свойству 'DefaultCredentials'. |
| virtual [System::String](../../system/string/) [get_UserAgent](./get_useragent/)() | Получает значение заголовка 'User-Agent'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [GetRequestStream](./getrequeststream/)() override | Возвращает поток для записи данных в ресурс. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [GetResponse](./getresponse/)() override | Возвращает веб-ответ, связанный с текущим веб-запросом. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
|  [HttpWebRequest](./httpwebrequest/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Создаёт новый экземпляр. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, а просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, а просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типо значений со ссылкой nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| static **bool** [RegisterPrefix](../webrequest/registerprefix/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IWebRequestCreate](../iwebrequestcreate/)\>) | Регистрирует наследника [WebRequest](../webrequest/) для указанного URI. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| void [set_Accept](./set_accept/)([String](../../system/string/)) | Устанавливает значение заголовка HTTP 'Accept'. |
| virtual void [set_AllowAutoRedirect](./set_allowautoredirect/)(**bool**) | Устанавливает значение, указывающее, следует ли запросу следовать перенаправлениям. |
| virtual void [set_AllowReadStreamBuffering](./set_allowreadstreambuffering/)(**bool**) | Устанавливает значение, указывающее, должны ли полученные от ресурса данные буферизоваться. |
| virtual void [set_AllowWriteStreamBuffering](./set_allowwritestreambuffering/)(**bool**) | Устанавливает значение, указывающее, включено ли буферизование при отправке данных. |
| virtual void [set_CachePolicy](../webrequest/set_cachepolicy/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\>) | Устанавливает политику кэширования. |
| virtual void [set_ClientCertificates](./set_clientcertificates/)([System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>) | Устанавливает коллекцию сертификатов, связанных с текущим запросом. |
| void [set_ConnectionGroupName](./set_connectiongroupname/)([System::String](../../system/string/)) override | Устанавливает имя группы соединений. |
| void [set_ContentLength](./set_contentlength/)(**int64_t**) override | Устанавливает количество байтов данных запроса для отправки. |
| void [set_ContentType](./set_contenttype/)([String](../../system/string/)) override | Устанавливает MIME-тип запроса. |
| void [set_ContinueTimeout](./set_continuetimeout/)(**int32_t**) | Устанавливает тайм-аут ожидания получения кода состояния 100-Continue. |
| virtual void [set_CookieContainer](./set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\>) | Устанавливает контейнер cookie, связанный с текущим веб-запросом. |
| void [set_Credentials](./set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) override | Устанавливает информацию об аутентификации, связанную с текущим запросом. |
| static void [set_DefaultWebProxy](../webrequest/set_defaultwebproxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | Устанавливает глобальный HTTP-прокси. |
| void [set_Headers](./set_headers/)([System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\>) override | Устанавливает коллекцию заголовков HTTP. |
| virtual void [set_KeepAlive](./set_keepalive/)(**bool**) | Устанавливает значение, указывающее, должен ли текущий запрос содержать заголовок 'Keep-Alive'. |
| virtual void [set_MaximumAutomaticRedirections](./set_maximumautomaticredirections/)(int) | Устанавливает максимальное количество разрешённых перенаправлений. |
| void [set_Method](./set_method/)([String](../../system/string/)) override | Устанавливает HTTP-метод. |
| void [set_PreAuthenticate](./set_preauthenticate/)(**bool**) override | Устанавливает значение, указывающее, должен ли запрос быть предварительно аутентифицирован. |
| static void [set_PrefixList](../webrequest/set_prefixlist/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\>) | Устанавливает список префиксов. |
| void [set_ProtocolVersion](./set_protocolversion/)([System::Version](../../system/version/)) | Устанавливает версию HTTP. |
| void [set_Proxy](./set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) override | Устанавливает HTTP-прокси. |
| virtual void [set_Referer](./set_referer/)([System::String](../../system/string/)) | Устанавливает значение заголовка 'Referer'. |
| virtual void [set_SendChunked](./set_sendchunked/)(**bool**) | Устанавливает значение, указывающее, должны ли данные отправляться сегментами. |
| void [set_Timeout](./set_timeout/)(int) override | Устанавливает период времени в миллисекундах, после которого запрос будет завершён с тайм-аутом. |
| virtual void [set_Timeout](../webrequest/set_timeout/)(**int32_t**) | Устанавливает период времени в миллисекундах, после которого запрос будет завершён с тайм-аутом. |
| void [set_UseDefaultCredentials](./set_usedefaultcredentials/)(**bool**) override | Устанавливает значение, указывающее, равно ли свойство 'Credential' свойству 'DefaultCredentials'. |
| virtual void [set_UserAgent](./set_useragent/)([System::String](../../system/string/)) | Устанавливает значение заголовка 'User-Agent'. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й параметр шаблона как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает значение счётчика общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [WebRequest](../webrequest/)
* Пространство имён [System::Net](../)
* Библиотека [Aspose.Slides](../../)