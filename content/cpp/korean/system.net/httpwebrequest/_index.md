---
title: HttpWebRequest
second_title: Aspose.Slides for C++ API 레퍼런스
description: "HTTP 웹 요청을 나타냅니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택에 직접 인스턴스를 만들거나 operator new를 사용하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고, 해당 포인터를 인수로 함수에 전달하십시오."
type: docs
weight: 274
url: /ko/system.net/httpwebrequest/
---
## HttpWebRequest 클래스


HTTP 웹 요청을 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하여 인스턴스를 만들면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고, 해당 포인터를 인수로 함수에 전달하십시오.

```cpp
class HttpWebRequest : public System::Net::WebRequest
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| void [Abort](./abort/)() override | 현재 요청을 중단합니다. |
| virtual void [AddRange](./addrange/)(**int32_t**) | 현재 요청에 '[Range](../../system/range/)' 헤더를 추가합니다. |
| virtual void [AddRange](./addrange/)([System::String](../../system/string/), **int32_t**, **int32_t**) | 현재 요청에 '[Range](../../system/range/)' 헤더를 추가합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetRequestStream](./begingetrequeststream/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 리소스에 데이터를 쓰기 위한 스트림을 얻기 위한 비동기 작업을 시작합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetResponse](./begingetresponse/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 리소스에 대한 비동기 요청을 시작합니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([String](../../system/string/)) | 지정된 URI를 사용하여 [WebRequest](../webrequest/) 클래스의 새 인스턴스를 생성합니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 지정된 URI를 사용하여 [WebRequest](../webrequest/) 클래스의 새 인스턴스를 생성합니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [CreateDefault](../webrequest/createdefault/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 지정된 URI 스킴에 대한 [WebRequest](../webrequest/) 파생 클래스를 생성합니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([String](../../system/string/)) | 지정된 URI를 사용하여 [WebRequest](../webrequest/) 클래스의 새 인스턴스를 생성합니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 지정된 URI를 사용하여 [WebRequest](../webrequest/) 클래스의 새 인스턴스를 생성합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [EndGetRequestStream](./endgetrequeststream/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | 지정된 스트림을 얻는 비동기 작업이 완료될 때까지 기다립니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [EndGetResponse](./endgetresponse/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | 지정된 리소스에 대한 비동기 요청이 완료될 때까지 기다립니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미에 따라 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 타입 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 타입 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일의 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 취급합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일의 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 취급합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| [String](../../system/string/) [get_Accept](./get_accept/)() | 'Accept' HTTP 헤더 값을 가져옵니다. |
| virtual **bool** [get_AllowAutoRedirect](./get_allowautoredirect/)() | 요청이 리디렉션을 따라가야 하는지 여부를 나타내는 값을 가져옵니다. |
| virtual **bool** [get_AllowReadStreamBuffering](./get_allowreadstreambuffering/)() | 리소스에서 받은 데이터를 버퍼링해야 하는지 여부를 나타내는 값을 가져옵니다. |
| virtual **bool** [get_AllowWriteStreamBuffering](./get_allowwritestreambuffering/)() | 데이터 전송을 위해 버퍼링이 활성화되어 있는지 여부를 나타내는 값을 가져옵니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\> [get_CachePolicy](../webrequest/get_cachepolicy/)() | 캐시 정책을 가져옵니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](./get_clientcertificates/)() | 현재 요청과 연결된 인증서 컬렉션을 가져옵니다. |
| [System::String](../../system/string/) [get_ConnectionGroupName](./get_connectiongroupname/)() override | 연결 그룹의 이름을 가져옵니다. |
| **int64_t** [get_ContentLength](./get_contentlength/)() override | 전송될 요청 데이터의 바이트 수를 가져옵니다. |
| [String](../../system/string/) [get_ContentType](./get_contenttype/)() override | 요청의 MIME 타입을 가져옵니다. |
| **int32_t** [get_ContinueTimeout](./get_continuetimeout/)() | 100-Continue 상태 코드가 수신될 때까지 대기할 시간 제한을 가져옵니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\> [get_CookieContainer](./get_cookiecontainer/)() | 현재 웹 요청과 연결된 쿠키 컨테이너를 가져옵니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](./get_credentials/)() override | 현재 요청과 연결된 인증 정보를 가져옵니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_DefaultWebProxy](../webrequest/get_defaultwebproxy/)() | 전역 HTTP 프록시를 가져옵니다. |
| virtual **bool** [get_HaveResponse](./get_haveresponse/)() | 응답이 수신되었는지 여부를 나타내는 값을 반환합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\> [get_Headers](./get_headers/)() override | HTTP 헤더 컬렉션을 가져옵니다. |
| virtual **bool** [get_KeepAlive](./get_keepalive/)() | 현재 요청에 'Keep-Alive' 헤더가 포함되어야 하는지 여부를 나타내는 값을 가져옵니다. |
| virtual int [get_MaximumAutomaticRedirections](./get_maximumautomaticredirections/)() | 허용되는 최대 리디렉션 수를 가져옵니다. |
| [String](../../system/string/) [get_Method](./get_method/)() override | HTTP 메서드를 가져옵니다. |
| **bool** [get_PreAuthenticate](./get_preauthenticate/)() override | 요청이 사전 인증되어야 하는지 여부를 나타내는 값을 가져옵니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\> [get_PrefixList](../webrequest/get_prefixlist/)() | 프리픽스 목록을 가져옵니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_Proxy](./get_proxy/)() override | HTTP 프록시를 가져옵니다. |
| virtual [System::String](../../system/string/) [get_Referer](./get_referer/)() | 'Referer' 헤더 값을 가져옵니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_RequestUri](./get_requesturi/)() override | 요청 URI를 반환합니다. |
| virtual **bool** [get_SendChunked](./get_sendchunked/)() | 데이터가 세그먼트로 전송되어야 하는지 여부를 나타내는 값을 가져옵니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[ServicePoint](../servicepoint/)\> [get_ServicePoint](./get_servicepoint/)() | 리소스에 대한 네트워크 연결을 나타내는 서비스 포인트를 반환합니다. |
| virtual **bool** [get_SupportsCookieContainer](./get_supportscookiecontainer/)() | 현재 요청이 쿠키 컨테이너를 사용할 수 있는지 여부를 나타내는 값을 반환합니다. |
| **int32_t** [get_Timeout](./get_timeout/)() override | 요청이 시간 초과될 때까지의 밀리초 단위 시간을 가져옵니다. |
| **bool** [get_UseDefaultCredentials](./get_usedefaultcredentials/)() override | 'Credential' 속성이 'DefaultCredentials' 속성과 같은지 여부를 나타내는 값을 가져옵니다. |
| virtual [System::String](../../system/string/) [get_UserAgent](./get_useragent/)() | 'User-Agent' 헤더 값을 가져옵니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [GetRequestStream](./getrequeststream/)() override | 리소스에 데이터를 쓰기 위한 스트림을 반환합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [GetResponse](./getresponse/)() override | 현재 웹 요청과 연결된 웹 응답을 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
|  [HttpWebRequest](./httpwebrequest/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 새 인스턴스를 생성합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType이 설명하는 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 구문의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입의 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않고, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무것도 복사하지 않고, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| static **bool** [RegisterPrefix](../webrequest/registerprefix/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IWebRequestCreate](../iwebrequestcreate/)\>) | 지정된 URI에 대한 [WebRequest](../webrequest/) 파생 클래스를 등록합니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| void [set_Accept](./set_accept/)([String](../../system/string/)) | 'Accept' HTTP 헤더 값을 설정합니다. |
| virtual void [set_AllowAutoRedirect](./set_allowautoredirect/)(**bool**) | 요청이 리디렉션을 따라가야 하는지 여부를 나타내는 값을 설정합니다. |
| virtual void [set_AllowReadStreamBuffering](./set_allowreadstreambuffering/)(**bool**) | 리소스에서 받은 데이터를 버퍼링해야 하는지 여부를 나타내는 값을 설정합니다. |
| virtual void [set_AllowWriteStreamBuffering](./set_allowwritestreambuffering/)(**bool**) | 데이터 전송을 위해 버퍼링이 활성화되어 있는지 여부를 나타내는 값을 설정합니다. |
| virtual void [set_CachePolicy](../webrequest/set_cachepolicy/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\>) | 캐시 정책을 설정합니다. |
| virtual void [set_ClientCertificates](./set_clientcertificates/)([System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>) | 현재 요청과 연결된 인증서 컬렉션을 설정합니다. |
| void [set_ConnectionGroupName](./set_connectiongroupname/)([System::String](../../system/string/)) override | 연결 그룹의 이름을 설정합니다. |
| void [set_ContentLength](./set_contentlength/)(**int64_t**) override | 전송될 요청 데이터의 바이트 수를 설정합니다. |
| void [set_ContentType](./set_contenttype/)([String](../../system/string/)) override | 요청의 MIME 타입을 설정합니다. |
| void [set_ContinueTimeout](./set_continuetimeout/)(**int32_t**) | 100-Continue 상태 코드가 수신될 때까지 대기할 시간 제한을 설정합니다. |
| virtual void [set_CookieContainer](./set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\>) | 현재 웹 요청과 연결된 쿠키 컨테이너를 설정합니다. |
| void [set_Credentials](./set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) override | 현재 요청과 연결된 인증 정보를 설정합니다. |
| static void [set_DefaultWebProxy](../webrequest/set_defaultwebproxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | 전역 HTTP 프록시를 설정합니다. |
| void [set_Headers](./set_headers/)([System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\>) override | HTTP 헤더 컬렉션을 설정합니다. |
| virtual void [set_KeepAlive](./set_keepalive/)(**bool**) | 현재 요청에 'Keep-Alive' 헤더가 포함되어야 하는지 여부를 나타내는 값을 설정합니다. |
| virtual void [set_MaximumAutomaticRedirections](./set_maximumautomaticredirections/)(int) | 허용되는 최대 리디렉션 수를 설정합니다. |
| void [set_Method](./set_method/)([String](../../system/string/)) override | HTTP 메서드를 설정합니다. |
| void [set_PreAuthenticate](./set_preauthenticate/)(**bool**) override | 요청이 사전 인증되어야 하는지 여부를 나타내는 값을 설정합니다. |
| static void [set_PrefixList](../webrequest/set_prefixlist/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\>) | 프리픽스 목록을 설정합니다. |
| void [set_ProtocolVersion](./set_protocolversion/)([System::Version](../../system/version/)) | HTTP 버전을 설정합니다. |
| void [set_Proxy](./set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) override | HTTP 프록시를 설정합니다. |
| virtual void [set_Referer](./set_referer/)([System::String](../../system/string/)) | 'Referer' 헤더 값을 설정합니다. |
| virtual void [set_SendChunked](./set_sendchunked/)(**bool**) | 데이터가 세그먼트로 전송되어야 하는지 여부를 나타내는 값을 설정합니다. |
| void [set_Timeout](./set_timeout/)(int) override | 요청이 시간 초과될 때까지의 밀리초 단위 시간을 설정합니다. |
| virtual void [set_Timeout](../webrequest/set_timeout/)(**int32_t**) | 요청이 시간 초과될 때까지의 밀리초 단위 시간을 설정합니다. |
| void [set_UseDefaultCredentials](./set_usedefaultcredentials/)(**bool**) override | 'Credential' 속성이 'DefaultCredentials' 속성과 같은지 여부를 나타내는 값을 설정합니다. |
| virtual void [set_UserAgent](./set_useragent/)([System::String](../../system/string/)) | 'User-Agent' 헤더 값을 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 템플릿 인자 n을 약한 포인터로 설정합니다(공유 대신). 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 레퍼런스 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있습니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [WebRequest](../webrequest/)
* 네임스페이스 [System::Net](../)
* 라이브러리 [Aspose.Slides](../../)