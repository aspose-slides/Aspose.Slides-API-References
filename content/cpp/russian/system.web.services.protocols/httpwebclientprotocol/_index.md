---
title: HttpWebClientProtocol
second_title: Справочник API Aspose.Slides для C++
description: "Этот базовый класс используется во всех прокси-клиентах XML-веб-служб, которые используют HTTP. Объекты этого класса должны быть выделены только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или нарушениям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 14
url: /ru/system.web.services.protocols/httpwebclientprotocol/
---
## HttpWebClientProtocol класс


This base class is used in all XML [Web](../../system.web/) service client proxies that use HTTP. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HttpWebClientProtocol : public System::Web::Services::Protocols::WebClientProtocol
```

## Методы

| Method | Description |
| --- | --- |
| virtual void [Abort](../webclientprotocol/abort/)() | Отменяет запрос. |
| virtual void [CheckForCookies](./checkforcookies/)([System::SharedPtr](../../system/sharedptr/)\<[Net::HttpWebResponse](../../system.net/httpwebresponse/)\>) | Добавляет cookie из указанного запроса во внутренний контейнер cookie. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение плавающих точек в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение плавающих точек в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| **bool** [get_AllowAutoRedirect](./get_allowautoredirect/)() | Возвращает значение, указывающее, следует ли клиент перенаправлениям сервера. |
| [System::SharedPtr](../../system/sharedptr/)\<[Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](./get_clientcertificates/)() | Возвращает коллекцию клиентских сертификатов. |
| [String](../../system/string/) [get_ConnectionGroupName](../webclientprotocol/get_connectiongroupname/)() | Возвращает имя группы соединений. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../../system.net/cookiecontainer/)\> [get_CookieContainer](./get_cookiecontainer/)() | Возвращает контейнер, используемый для хранения cookie. |
| [System::SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\> [get_Credentials](../webclientprotocol/get_credentials/)() | Возвращает информацию аутентификации. |
| **bool** [get_EnableDecompression](./get_enabledecompression/)() | Возвращает значение, указывающее, включено ли распаковка. |
| **bool** [get_PreAuthenticate](../webclientprotocol/get_preauthenticate/)() | Возвращает значение, указывающее, включена ли предварительная аутентификация. |
| [System::SharedPtr](../../system/sharedptr/)\<[Net::IWebProxy](../../system.net/iwebproxy/)\> [get_Proxy](./get_proxy/)() | Возвращает информацию о прокси. |
| [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_RequestEncoding](../webclientprotocol/get_requestencoding/)() | Возвращает кодировку, используемую для запросов клиента. |
| **int32_t** [get_Timeout](../webclientprotocol/get_timeout/)() | Возвращает промежуток времени ожидания до истечения тайм-аута запроса. |
| **bool** [get_UnsafeAuthenticatedConnectionSharing](./get_unsafeauthenticatedconnectionsharing/)() | Возвращает значение, указывающее, включено ли совместное использование соединений при использовании клиентом аутентификации NTLM. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Uri](../webclientprotocol/get_uri/)() | Возвращает URI XML-службы [Web](../../system.web/). |
| [String](../../system/string/) [get_Url](../webclientprotocol/get_url/)() | Возвращает URL XML-службы [Web](../../system.web/). |
| **bool** [get_UseDefaultCredentials](../webclientprotocol/get_usedefaultcredentials/)() | Возвращает значение, указывающее, равно ли свойство 'Credential' свойству 'DefaultCredentials'. |
| [String](../../system/string/) [get_UserAgent](./get_useragent/)() | Возвращает значение заголовка 'User-Agent'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Возвращает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Возвращает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| void [set_AllowAutoRedirect](./set_allowautoredirect/)(**bool**) | Устанавливает значение, указывающее, следует ли клиент перенаправлениям сервера. |
| void [set_ConnectionGroupName](../webclientprotocol/set_connectiongroupname/)([String](../../system/string/)) | Устанавливает имя группы соединений. |
| void [set_CookieContainer](./set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../../system.net/cookiecontainer/)\>) | Устанавливает контейнер, используемый для хранения cookie. |
| void [set_Credentials](../webclientprotocol/set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\>) | Устанавливает информацию аутентификации. |
| void [set_EnableDecompression](./set_enabledecompression/)(**bool**) | Устанавливает значение, указывающее, включена ли распаковка. |
| void [set_PreAuthenticate](../webclientprotocol/set_preauthenticate/)(**bool**) | Устанавливает значение, указывающее, включена ли предварительная аутентификация. |
| void [set_Proxy](./set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[Net::IWebProxy](../../system.net/iwebproxy/)\>) | Устанавливает информацию о прокси. |
| void [set_RequestEncoding](../webclientprotocol/set_requestencoding/)([System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>) | Устанавливает кодировку, используемую для запросов клиента. |
| void [set_Timeout](../webclientprotocol/set_timeout/)(**int32_t**) | Устанавливает промежуток времени ожидания до истечения тайм-аута запроса. |
| void [set_UnsafeAuthenticatedConnectionSharing](./set_unsafeauthenticatedconnectionsharing/)(**bool**) | Устанавливает значение, указывающее, включено ли совместное использование соединений при использовании клиентом аутентификации NTLM. |
| void [set_Uri](../webclientprotocol/set_uri/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Устанавливает URI XML-службы [Web](../../system.web/). |
| void [set_Url](../webclientprotocol/set_url/)([String](../../system/string/)) | Устанавливает URL XML-службы [Web](../../system.web/). |
| void [set_UseDefaultCredentials](../webclientprotocol/set_usedefaultcredentials/)(**bool**) | Устанавливает значение, указывающее, равно ли свойство 'Credential' свойству 'DefaultCredentials'. |
| void [set_UserAgent](./set_useragent/)([String](../../system/string/)) | Устанавливает значение заголовка 'User-Agent'. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим слабого. |
| int [SharedCount](../../system/object/sharedcount/)() const | Возвращает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| void [UnregisterMapping](./unregistermapping/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) |  |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [WebClientProtocol](../webclientprotocol/)
* Пространство имён [System::Web::Services::Protocols](../)
* Библиотека [Aspose.Slides](../../)