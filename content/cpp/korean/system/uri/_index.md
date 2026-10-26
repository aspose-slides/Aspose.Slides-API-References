---
title: Uri
second_title: Aspose.Slides for C++ API 레퍼런스
description: "통합 리소스 식별자. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하여 인스턴스를 만들지 마십시오. 이렇게 하면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고, 해당 포인터를 함수 인수로 전달하십시오."
type: docs
weight: 1392
url: /ko/system/uri/
---
## Uri 클래스

Unified resource identifier. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Uri : public System::Object
```

## 메서드

| Method | 설명 |
| --- | --- |
| static [UriHostNameType](../urihostnametype/) [CheckHostName](./checkhostname/)([String](../string/)) | 지정된 호스트 이름의 유형을 결정합니다. |
| static **bool** [CheckSchemeName](./checkschemename/)(const [String](../string/)\&) | 지정된 스킴이 유효한지 확인합니다. |
| static **int32_t** [Compare](./compare/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [UriComponents](../uricomponents/), [UriFormat](../uriformat/), [StringComparison](../stringcomparison/)) | 지정된 [Uri](./) 객체를 지정된 비교 규칙을 사용하여 비교합니다. |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override | 현재 객체와 지정된 객체가 나타내는 URI가 같은지 확인합니다. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# [Object.Equals](../object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 취급하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 취급하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static [String](../string/) [EscapeDataString](./escapedatastring/)(const [String](../string/)\&) | 문자열을 이스케이프된 표현으로 변환합니다. |
| static [String](../string/) [EscapeUriString](./escapeuristring/)(const [String](../string/)\&) | URI 문자열을 이스케이프된 표현으로 변환합니다. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| static **int32_t** [FromHex](./fromhex/)(char16_t) | 16진수 자리의 십진값을 반환합니다. |
| [String](../string/) [get_AbsolutePath](./get_absolutepath/)() const | URI의 절대 경로를 반환합니다. |
| [String](../string/) [get_AbsoluteUri](./get_absoluteuri/)() const | 절대 URI를 반환합니다. |
| [String](../string/) [get_Authority](./get_authority/)() const | 서버의 호스트 이름과 포트 번호를 반환합니다. |
| [String](../string/) [get_DnsSafeHost](./get_dnssafehost/)() const | 이스케이프되지 않은 호스트 이름을 반환합니다. |
| [String](../string/) [get_Fragment](./get_fragment/)() const | 이스케이프된 URI 조각을 반환합니다. |
| [String](../string/) [get_Host](./get_host/)() const | 호스트 이름을 반환합니다. |
| [UriHostNameType](../urihostnametype/) [get_HostNameType](./get_hostnametype/)() const | 호스트 이름 유형을 반환합니다. |
| [String](../string/) [get_IdnHost](./get_idnhost/)() const | 호스트의 국제 도메인 이름을 반환합니다. |
| **bool** [get_IsAbsoluteUri](./get_isabsoluteuri/)() const | 현재 객체가 나타내는 URI가 절대 경로인지 확인합니다. |
| **bool** [get_IsDefaultPort](./get_isdefaultport/)() const | 현재 객체가 나타내는 URI가 해당 스킴의 기본 포트를 가지고 있는지 확인합니다. |
| **bool** [get_IsFile](./get_isfile/)() const | 현재 객체가 나타내는 URI가 파일인지 확인합니다. |
| **bool** [get_IsLoopback](./get_isloopback/)() const | 현재 객체가 나타내는 URI가 로컬 호스트를 참조하는지 확인합니다. |
| **bool** [get_IsUnc](./get_isunc/)() const | 현재 객체가 나타내는 URI가 UNC 경로인지 확인합니다. |
| [String](../string/) [get_LocalPath](./get_localpath/)() const | 현재 객체가 나타내는 URI가 참조하는 파일 이름의 운영 체제 표현을 반환합니다. |
| [String](../string/) [get_OriginalString](./get_originalstring/)() const | 현재 객체가 생성될 때 생성자에 전달된 URI 문자열을 반환합니다. |
| [String](../string/) [get_PathAndQuery](./get_pathandquery/)() const | 현재 객체가 나타내는 URI의 절대 경로와 쿼리 구성 요소를 물음표(?) 로 구분하여 반환합니다. |
| **int32_t** [get_Port](./get_port/)() const | 현재 객체가 나타내는 URI의 포트 번호를 반환합니다. |
| [String](../string/) [get_Query](./get_query/)() const | 현재 객체가 나타내는 URI에 포함된 쿼리 정보를 반환합니다. |
| [String](../string/) [get_Scheme](./get_scheme/)() const | 현재 객체가 나타내는 URI의 스킴을 반환합니다. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [get_Segments](./get_segments/)() const | 현재 객체가 나타내는 URI의 경로 세그먼트를 포함하는 문자열 배열을 반환합니다. |
| **bool** [get_UserEscaped](./get_userescaped/)() const | 현재 객체의 생성자에 전달된 URI 문자열이 완전히 이스케이프되었는지 확인합니다. |
| [String](../string/) [get_UserInfo](./get_userinfo/)() const | 현재 객체가 나타내는 URI와 관련된 사용자 이름, 비밀번호 및 기타 사용자 정보를 반환합니다. |
| [String](../string/) [GetComponents](./getcomponents/)([UriComponents](../uricomponents/), [UriFormat](../uriformat/)) const | 지정된 이스케이프 방식을 사용하여 현재 객체가 나타내는 URI의 지정된 구성 요소를 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | URI의 해시 코드를 가져옵니다. |
| [String](../string/) [GetLeftPart](./getleftpart/)([UriPartial](../uripartial/)) | 현재 객체가 나타내는 URI의 지정된 부분을 반환합니다. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../object/gettype/) 호출의 유사 구현입니다. |
| static [String](../string/) [HexEscape](./hexescape/)(char16_t) | 지정된 문자에 대한 16진수 값을 반환합니다. |
| static char16_t [HexUnescape](./hexunescape/)(const [String](../string/)\&, **int32_t**\&) | 문자의 지정된 16진수 표현을 문자로 변환합니다. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | 객체가 targetType이 설명하는 타입의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자의 유사 구현입니다. |
| **bool** [IsBaseOf](./isbaseof/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) const | 현재 [Uri](./) 객체가 나타내는 URI가 지정된 [Uri](./) 객체가 나타내는 URI의 기반인지 확인합니다. |
| static **bool** [IsHexDigit](./ishexdigit/)(char16_t) | 지정된 문자가 유효한 16진수 자리인지 확인합니다. |
| static **bool** [IsHexEncoding](./ishexencoding/)(const [String](../string/)\&, **int32_t**) | 지정된 문자열의 지정된 위치에 있는 문자가 16진수로 인코딩되어 있는지 확인합니다. |
| **bool** [IsWellFormedOriginalString](./iswellformedoriginalstring/)() const | 이 [Uri](./)를 구성하는 데 사용된 문자열이 올바르게 형성되었고 추가 이스케이프가 필요하지 않은지 표시합니다. |
| static **bool** [IsWellFormedUriString](./iswellformeduristring/)(const [String](../string/)\&, [UriKind](../urikind/)) | 지정된 문자열이 올바른 형식의 URI인지 확인합니다. |
| void [Lock](../object/lock/)() | C# lock() 구문의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../lockcontext/) 감시 객체를 사용하십시오. |
| [String](../string/) [MakeRelative](./makerelative/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | 두 [Uri](./) 인스턴스 간의 차이를 결정합니다. |
| [SharedPtr](../sharedptr/)\<[Uri](./)\> [MakeRelativeUri](./makerelativeuri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | 현재 객체와 지정된 [Uri](./) 객체가 나타내는 URI 간의 차이를 결정합니다. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) 메서드의 유사 구현입니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../object/object/)([Object](../object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않으며, 새로운 객체를 초기화하고 서브클래스의 복사 구성을 가능하게 합니다. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않으며, 새로운 객체를 초기화하고 서브클래스의 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 레퍼런스 비교합니다. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/)의 문자열과 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | 'nth' 템플릿 인수를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| [String](../string/) [ToString](./tostring/)() const override | 현재 객체가 나타내는 URI의 문자열 표현을 반환합니다. |
| static **bool** [TryCreate](./trycreate/)(const [String](../string/)\&, [UriKind](../urikind/), [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | 지정된 URI를 나타내는 [Uri](./) 객체를 생성합니다; 인수가 URI 종류를 지정합니다. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | 기본 URI를 나타내는 지정된 [Uri](./) 객체와 상대 URI의 문자열 표현으로부터 [Uri](./) 객체를 생성합니다. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | 지정된 기본 및 상대 URI로부터 [Uri](./) 객체를 생성합니다. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) 구문을 구현합니다. |
| static [String](../string/) [UnescapeDataString](./unescapedatastring/)(const [String](../string/)\&) | 지정된 이스케이프된 문자열의 이스케이프를 해제합니다. |
| void [Unlock](../object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../lockcontext/) 감시 객체를 사용하십시오. |
|  [Uri](./uri/)(const [String](../string/)\&) | 지정된 URI를 나타내는 [Uri](./) 객체를 생성합니다. |
|  [Uri](./uri/)(const [String](../string/)\&, **bool**) | 지정된 URI를 나타내는 [Uri](./) 객체를 생성합니다; 인수는 URI를 이스케이프할지 여부를 지정합니다. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, **bool**) | 기본 URI를 나타내는 지정된 [Uri](./) 객체와 상대 URI의 문자열 표현으로부터 [Uri](./) 객체를 생성합니다; 인수는 URI를 이스케이프할지 여부를 지정합니다. |
|  [Uri](./uri/)(const [String](../string/)\&, [UriKind](../urikind/)) | 지정된 URI를 나타내는 [Uri](./) 객체를 생성합니다; 인수가 URI 종류를 지정합니다. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&) | 지정된 기본 및 상대 URI로부터 [Uri](./) 객체를 생성합니다. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | 지정된 기본 및 상대 URI로부터 [Uri](./) 객체를 생성합니다. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 필드

| 필드 | 설명 |
| --- | --- |
| static [SchemeDelimiter](./schemedelimiter/) | [Uri](./)의 주소 부분과 통신 프로토콜 스킴을 구분하는 문자들을 지정합니다. |
| static [UriSchemeFile](./urischemefile/) | [Uri](./)이 파일에 대한 포인터임을 지정합니다. |
| static [UriSchemeFtp](./urischemeftp/) | [Uri](./)이 파일 전송 프로토콜을 통해 접근됨을 지정합니다. |
| static [UriSchemeGopher](./urischemegopher/) | [Uri](./)이 Gopher 프로토콜을 통해 접근됨을 지정합니다. |
| static [UriSchemeHttp](./urischemehttp/) | [Uri](./)이 하이퍼텍스트 전송 프로토콜을 통해 접근됨을 지정합니다. |
| static [UriSchemeHttps](./urischemehttps/) | [Uri](./)이 보안 하이퍼텍스트 전송 프로토콜을 통해 접근됨을 지정합니다. |
| static [UriSchemeMailto](./urischememailto/) | [Uri](./)이 이메일 주소이며 Simple Mail Transport Protocol을 통해 접근됨을 지정합니다. |
| static [UriSchemeNetPipe](./urischemenetpipe/) | [Uri](./)이 [Windows](../../system.windows/) 통신 기반에서 사용하는 NetPipe 스킴을 통해 접근됨을 지정합니다. |
| static [UriSchemeNetTcp](./urischemenettcp/) | [Uri](./)이 [Windows](../../system.windows/) 통신 기반에서 사용하는 NetTcp 스킷을 통해 접근됨을 지정합니다. |
| static [UriSchemeNews](./urischemenews/) | [Uri](./)가 인터넷 뉴스 그룹이며 Network News Transport Protocol을 통해 접근됨을 지정합니다. |
| static [UriSchemeNntp](./urischemenntp/) | [Uri](./)가 인터넷 뉴스 그룹이며 Network News Transport Protocol을 통해 접근됨을 지정합니다. |

## 비고



```cpp
#include "system/smart_ptr.h"
#include "system/uri.h"
#include <iostream>

int main()
{
  const auto uri = System::MakeObject<System::Uri>(u"https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/");

std::cout <<
  "AbsolutePath: " << uri->get_AbsolutePath() << std::endl <<
  "AbsoluteUri: " << uri->get_AbsoluteUri() << std::endl <<
  "Authority: " << uri->get_Authority() << std::endl <<
  "DnsSafeHost: " << uri->get_DnsSafeHost() << std::endl <<
  "Fragment: " << uri->get_Fragment() << std::endl <<
  "Host: " << uri->get_Host() << std::endl <<
  "IdnHost: " << uri->get_IdnHost() << std::endl <<
  "LocalPath: " << uri->get_LocalPath() << std::endl <<
  "OriginalString: " << uri->get_OriginalString() << std::endl <<
  "PathAndQuery: " << uri->get_PathAndQuery() << std::endl <<
  "Port: " << uri->get_Port() << std::endl <<
  "Query: " << uri->get_Query() << std::endl <<
  "Scheme: " << uri->get_Scheme() << std::endl;

  return 0;
}
/*
이 코드 예제는 다음과 같은 출력을 생성합니다:
AbsolutePath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
AbsoluteUri: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Authority: docs.codeporting.com
DnsSafeHost: docs.codeporting.com
Fragment:
Host: docs.codeporting.com
IdnHost: docs.codeporting.com
LocalPath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
OriginalString: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
PathAndQuery: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Port: 443
Query:
Scheme: https
*/
```

## 참조

* 클래스 [Object](../object/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)