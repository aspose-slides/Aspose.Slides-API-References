---
title: HttpWebRequest
second_title: Aspose.Slides for C++ – odniesienie do API
description: "Reprezentuje żądanie HTTP. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz egzemplarza tego typu na stosie ani przy użyciu operatora new, ponieważ może to spowodować błędy w czasie wykonywania i/lub awarie asercji. Zawsze opakowuj tę klasę w wskaźnik System::SmartPtr i używaj tego wskaźnika do przekazywania go jako argumentu do funkcji."
type: docs
weight: 274
url: /pl/system.net/httpwebrequest/
---
## HttpWebRequest klasa

Reprezentuje żądanie sieciowe HTTP. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz egzemplarza tego typu na stosie ani przy użyciu operatora new, ponieważ może to spowodować błędy czasu wykonania i/lub awarie asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument.

```cpp
class HttpWebRequest : public System::Net::WebRequest
```

## Metody

| Metoda | Opis |
| --- | --- |
| void [Abort](./abort/)() override | Anuluje bieżące żądanie. |
| virtual void [AddRange](./addrange/)(**int32_t**) | Dodaje nagłówek '[Range](../../system/range/)' do bieżącego żądania. |
| virtual void [AddRange](./addrange/)([System::String](../../system/string/), **int32_t**, **int32_t**) | Dodaje nagłówek '[Range](../../system/range/)' do bieżącego żądania. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetRequestStream](./begingetrequeststream/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Inicjuje asynchroniczną operację pobierania strumienia do zapisu danych w zasobie. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetResponse](./begingetresponse/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Inicjuje asynchroniczne żądanie zasobu. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([String](../../system/string/)) | Tworzy nową instancję klasy [WebRequest](../webrequest/) przy użyciu określonego URI. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Tworzy nową instancję klasy [WebRequest](../webrequest/) przy użyciu określonego URI. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [CreateDefault](../webrequest/createdefault/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Tworzy potomka [WebRequest](../webrequest/) dla określonego schematu URI. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([String](../../system/string/)) | Tworzy nową instancję klasy [WebRequest](../webrequest/) przy użyciu określonego URI. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Tworzy nową instancję klasy [WebRequest](../webrequest/) przy użyciu określonego URI. |
| [System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [EndGetRequestStream](./endgetrequeststream/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Czeka, aż określona asynchroniczna operacja pobierania strumienia zostanie zakończona. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [EndGetResponse](./endgetresponse/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Czeka, aż określone asynchroniczne żądanie zasobu zostanie zakończone. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że według IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że według IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [String](../../system/string/) [get_Accept](./get_accept/)() | Pobiera wartość nagłówka HTTP 'Accept'. |
| virtual **bool** [get_AllowAutoRedirect](./get_allowautoredirect/)() | Pobiera wartość określającą, czy żądanie powinno podążać za przekierowaniami. |
| virtual **bool** [get_AllowReadStreamBuffering](./get_allowreadstreambuffering/)() | Pobiera wartość wskazującą, czy dane odebrane z zasobu muszą być buforowane. |
| virtual **bool** [get_AllowWriteStreamBuffering](./get_allowwritestreambuffering/)() | Pobiera wartość określającą, czy buforowanie jest włączone przy wysyłaniu danych. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\> [get_CachePolicy](../webrequest/get_cachepolicy/)() | Pobiera politykę pamięci podręcznej. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](./get_clientcertificates/)() | Pobiera kolekcję certyfikatów powiązanych z bieżącym żądaniem. |
| [System::String](../../system/string/) [get_ConnectionGroupName](./get_connectiongroupname/)() override | Pobiera nazwę grupy połączeń. |
| **int64_t** [get_ContentLength](./get_contentlength/)() override | Pobiera liczbę bajtów danych żądania do wysłania. |
| [String](../../system/string/) [get_ContentType](./get_contenttype/)() override | Pobiera typ MIME żądania. |
| **int32_t** [get_ContinueTimeout](./get_continuetimeout/)() | Pobiera limit czasu oczekiwania na kod statusu 100-Continue. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\> [get_CookieContainer](./get_cookiecontainer/)() | Pobiera kontener ciasteczek powiązany z bieżącym żądaniem sieciowym. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](./get_credentials/)() override | Pobiera informacje uwierzytelniania powiązane z bieżącym żądaniem. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_DefaultWebProxy](../webrequest/get_defaultwebproxy/)() | Pobiera globalny serwer proxy HTTP. |
| virtual **bool** [get_HaveResponse](./get_haveresponse/)() | Zwraca wartość wskazującą, czy odpowiedź została otrzymana. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\> [get_Headers](./get_headers/)() override | Pobiera kolekcję nagłówków HTTP. |
| virtual **bool** [get_KeepAlive](./get_keepalive/)() | Pobiera wartość wskazującą, czy bieżące żądanie musi zawierać nagłówek 'Keep-Alive'. |
| virtual int [get_MaximumAutomaticRedirections](./get_maximumautomaticredirections/)() | Pobiera maksymalną liczbę dozwolonych przekierowań. |
| [String](../../system/string/) [get_Method](./get_method/)() override | Pobiera metodę HTTP. |
| **bool** [get_PreAuthenticate](./get_preauthenticate/)() override | Pobiera wartość wskazującą, czy żądanie musi być wstępnie uwierzytelnione. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\> [get_PrefixList](../webrequest/get_prefixlist/)() | Pobiera listę prefiksów. |
| [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_Proxy](./get_proxy/)() override | Pobiera serwer proxy HTTP. |
| virtual [System::String](../../system/string/) [get_Referer](./get_referer/)() | Pobiera wartość nagłówka 'Referer'. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_RequestUri](./get_requesturi/)() override | Zwraca URI żądania. |
| virtual **bool** [get_SendChunked](./get_sendchunked/)() | Pobiera wartość wskazującą, czy dane muszą być wysyłane w segmentach. |
| [System::SharedPtr](../../system/sharedptr/)\<[ServicePoint](../servicepoint/)\> [get_ServicePoint](./get_servicepoint/)() | Zwraca punkt usługi reprezentujący połączenie sieciowe z zasobem. |
| virtual **bool** [get_SupportsCookieContainer](./get_supportscookiecontainer/)() | Zwraca wartość wskazującą, czy bieżące żądanie może używać kontenera ciasteczek. |
| **int32_t** [get_Timeout](./get_timeout/)() override | Pobiera czas w milisekundach, po którym żądanie zostanie przerwane z powodu upływu czasu. |
| **bool** [get_UseDefaultCredentials](./get_usedefaultcredentials/)() override | Pobiera wartość wskazującą, czy właściwość 'Credential' jest równa właściwości 'DefaultCredentials'. |
| virtual [System::String](../../system/string/) [get_UserAgent](./get_useragent/)() | Pobiera wartość nagłówka 'User-Agent'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [GetRequestStream](./getrequeststream/)() override | Zwraca strumień do zapisu danych w zasobie. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [GetResponse](./getresponse/)() override | Zwraca odpowiedź sieciową powiązaną z bieżącym żądaniem sieciowym. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
|  [HttpWebRequest](./httpwebrequest/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Tworzy nową instancję. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt reprezentuje instancję typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu wartownika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie w podklasach. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie w podklasach. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| static **bool** [RegisterPrefix](../webrequest/registerprefix/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IWebRequestCreate](../iwebrequestcreate/)\>) | Rejestruje potomka [WebRequest](../webrequest/) dla określonego URI. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o określoną wartość. |
| void [set_Accept](./set_accept/)([String](../../system/string/)) | Ustawia wartość nagłówka HTTP 'Accept'. |
| virtual void [set_AllowAutoRedirect](./set_allowautoredirect/)(**bool**) | Ustawia wartość określającą, czy żądanie powinno podążać za przekierowaniami. |
| virtual void [set_AllowReadStreamBuffering](./set_allowreadstreambuffering/)(**bool**) | Ustawia wartość wskazującą, czy dane odebrane z zasobu muszą być buforowane. |
| virtual void [set_AllowWriteStreamBuffering](./set_allowwritestreambuffering/)(**bool**) | Ustawia wartość określającą, czy buforowanie jest włączone przy wysyłaniu danych. |
| virtual void [set_CachePolicy](../webrequest/set_cachepolicy/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\>) | Ustawia politykę pamięci podręcznej. |
| virtual void [set_ClientCertificates](./set_clientcertificates/)([System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>) | Ustawia kolekcję certyfikatów powiązanych z bieżącym żądaniem. |
| void [set_ConnectionGroupName](./set_connectiongroupname/)([System::String](../../system/string/)) override | Ustawia nazwę grupy połączeń. |
| void [set_ContentLength](./set_contentlength/)(**int64_t**) override | Ustawia liczbę bajtów danych żądania do wysłania. |
| void [set_ContentType](./set_contenttype/)([String](../../system/string/)) override | Ustawia typ MIME żądania. |
| void [set_ContinueTimeout](./set_continuetimeout/)(**int32_t**) | Ustawia limit czasu oczekiwania na kod statusu 100-Continue. |
| virtual void [set_CookieContainer](./set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\>) | Ustawia kontener ciasteczek powiązany z bieżącym żądaniem sieciowym. |
| void [set_Credentials](./set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) override | Ustawia informacje uwierzytelniania powiązane z bieżącym żądaniem. |
| static void [set_DefaultWebProxy](../webrequest/set_defaultwebproxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | Ustawia globalny serwer proxy HTTP. |
| void [set_Headers](./set_headers/)([System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\>) override | Ustawia kolekcję nagłówków HTTP. |
| virtual void [set_KeepAlive](./set_keepalive/)(**bool**) | Ustawia wartość określającą, czy bieżące żądanie musi zawierać nagłówek 'Keep-Alive'. |
| virtual void [set_MaximumAutomaticRedirections](./set_maximumautomaticredirections/)(int) | Ustawia maksymalną liczbę dozwolonych przekierowań. |
| void [set_Method](./set_method/)([String](../../system/string/)) override | Ustawia metodę HTTP. |
| void [set_PreAuthenticate](./set_preauthenticate/)(**bool**) override | Ustawia wartość określającą, czy żądanie musi być wstępnie uwierzytelnione. |
| static void [set_PrefixList](../webrequest/set_prefixlist/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\>) | Ustawia listę prefiksów. |
| void [set_ProtocolVersion](./set_protocolversion/)([System::Version](../../system/version/)) | Ustawia wersję HTTP. |
| void [set_Proxy](./set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) override | Ustawia serwer proxy HTTP. |
| virtual void [set_Referer](./set_referer/)([System::String](../../system/string/)) | Ustawia wartość nagłówka 'Referer'. |
| virtual void [set_SendChunked](./set_sendchunked/)(**bool**) | Ustawia wartość określającą, czy dane muszą być wysyłane w segmentach. |
| void [set_Timeout](./set_timeout/)(int) override | Ustawia czas w milisekundach, po którym żądanie zostanie przerwane z powodu upływu czasu. |
| virtual void [set_Timeout](../webrequest/set_timeout/)(**int32_t**) | Ustawia czas w milisekundach, po którym żądanie zostanie przerwane z powodu upływu czasu. |
| void [set_UseDefaultCredentials](./set_usedefaultcredentials/)(**bool**) override | Ustawia wartość wskazującą, czy właściwość 'Credential' jest równa właściwości 'DefaultCredentials'. |
| virtual void [set_UserAgent](./set_useragent/)([System::String](../../system/string/)) | Ustawia wartość nagłówka 'User-Agent'. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowywanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu wartownika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [WebRequest](../webrequest/)
* Przestrzeń nazw [System::Net](../)
* Biblioteka [Aspose.Slides](../../)