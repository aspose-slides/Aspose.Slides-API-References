---
title: CacheControlHeaderValue
second_title: Aspose.Slides for C++ API 레퍼런스
description: "'Cache-Control' 헤더의 값을 나타냅니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택이나 operator new를 사용하여 이 유형의 인스턴스를 생성하지 마십시오. 그렇지 않으면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 이 클래스를 항상 System::SmartPtr 포인터로 감싸고, 해당 포인터를 함수의 인자로 전달하십시오."
type: docs
weight: 14
url: /ko/system.net.http.headers/cachecontrolheadervalue/
---
## CacheControlHeaderValue 클래스


‘Cache-Control’ 헤더의 값을 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여 할당해야 합니다. 스택이나 operator new를 사용하여 이 유형의 인스턴스를 생성하지 마십시오. 그렇지 않으면 런타임 오류 또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고, 해당 포인터를 함수 인자로 전달하십시오.

```cpp
class CacheControlHeaderValue : public System::ICloneable
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  [CacheControlHeaderValue](./cachecontrolheadervalue/)() | 새 인스턴스를 생성합니다. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | C# [Object.Equals](../../system/object/equals/) 시맨틱을 사용하여 객체를 비교합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 시맨틱을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 타입 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 두 NaN을 동일하게 간주하는 C#-style 부동 소수점 비교를 에뮬레이션합니다. 이는 IEC 60559:1989에 따르면 NaN은 어떤 값(또 NaN 포함)과도 같지 않음에도 불구하고 적용됩니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 두 NaN을 동일하게 간주하는 C#-style 부동 소수점 비교를 에뮬레이션합니다. 이는 IEC 60559:1989에 따르면 NaN은 어떤 값(또 NaN 포함)과도 같지 않음에도 불구하고 적용됩니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Extensions](./get_extensions/)() | 캐시 확장 토큰 컬렉션을 반환합니다. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxAge](./get_maxage/)() | 클라이언트가 응답을 허용하는 시간을 결정하는 최대 연령 값을 초 단위로 가져옵니다. |
| **bool** [get_MaxStale](./get_maxstale/)() | 클라이언트가 만료된 응답을 허용할지 여부를 나타내는 값을 가져옵니다. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxStaleLimit](./get_maxstalelimit/)() | 클라이언트가 만료된 응답을 허용하는 시간을 초 단위로 나타내는 값을 가져옵니다. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MinFresh](./get_minfresh/)() | 신선도 수명을 결정하는 값을 가져옵니다. |
| **bool** [get_MustRevalidate](./get_mustrevalidate/)() | 서버가 캐시 항목이 오래될 때 재검증을 요구하는지 여부를 나타내는 값을 가져옵니다. |
| **bool** [get_NoCache](./get_nocache/)() | 클라이언트가 캐시된 응답을 허용하는지 여부를 나타내는 값을 가져옵니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_NoCacheHeaders](./get_nocacheheaders/)() | ‘Cache-Control’ 헤더의 'no-cache' 지시어에 포함된 필드 이름 컬렉션을 가져옵니다. |
| **bool** [get_NoStore](./get_nostore/)() | 캐시가 HTTP 요청 또는 응답의 어느 부분도 저장하지 않아야 하는지를 나타내는 값을 가져옵니다. |
| **bool** [get_NoTransform](./get_notransform/)() | 캐시 또는 프록시가 엔터티 본문의 어느 부분도 변경하지 않아야 하는지를 나타내는 값을 가져옵니다. |
| **bool** [get_OnlyIfCached](./get_onlyifcached/)() | 클라이언트가 오직 캐시된 항목만 사용해야 하는지를 나타내는 값을 가져옵니다. |
| **bool** [get_Private](./get_private/)() | HTTP 응답 메시지 또는 그 일부가 단일 사용자용이며 공유 캐시에서 캐시되지 않아야 하는지를 나타내는 값을 가져옵니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_PrivateHeaders](./get_privateheaders/)() | ‘Cache-Control’ 헤더의 'private' 지시어에 포함된 필드 이름 컬렉션을 가져옵니다. |
| **bool** [get_ProxyRevalidate](./get_proxyrevalidate/)() | 서버가 공유 사용자 에이전트 캐시에서 캐시 항목이 오래될 때 재검증을 요구하는지를 나타내는 값을 가져옵니다. |
| **bool** [get_Public](./get_public/)() | HTTP 응답이 모든 캐시에서 캐시될 수 있는지를 나타내는 값을 가져옵니다. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_SharedMaxAge](./get_sharedmaxage/)() | 공유 캐시에서 'Cache-Control'의 'max-age' 지시어 또는 'Expires' 헤더를 재정의하는 공유 최대 연령 값을 초 단위로 가져옵니다. |
| static **int32_t** [GetCacheControlLength](./getcachecontrollength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | 지정된 인덱스부터 전달된 문자열을 [CacheControlHeaderValue](./) 클래스 인스턴스로 변환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType이 설명하는 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현한 잠금입니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | 전달된 문자열을 [CacheControlHeaderValue](./) 클래스 인스턴스로 변환합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 레퍼런스로 값 타입 객체와 nullptr를 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 문자열과 nullptr 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| void [set_MaxAge](./set_maxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | 클라이언트가 응답을 허용하는 시간을 결정하는 최대 연령 값을 초 단위로 설정합니다. |
| void [set_MaxStale](./set_maxstale/)(**bool**) | 클라이언트가 만료된 응답을 허용하는지를 설정합니다. |
| void [set_MaxStaleLimit](./set_maxstalelimit/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | 클라이언트가 만료된 응답을 허용하는 시간을 초 단위로 설정합니다. |
| void [set_MinFresh](./set_minfresh/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | 신선도 수명을 설정합니다. |
| void [set_MustRevalidate](./set_mustrevalidate/)(**bool**) | 서버가 캐시 항목이 오래될 때 재검증을 요구하는지를 설정합니다. |
| void [set_NoCache](./set_nocache/)(**bool**) | 클라이언트가 캐시된 응답을 허용하는지를 설정합니다. |
| void [set_NoStore](./set_nostore/)(**bool**) | 캐시가 HTTP 요청 또는 응답의 어느 부분도 저장하지 않도록 설정합니다. |
| void [set_NoTransform](./set_notransform/)(**bool**) | 캐시 또는 프록시가 엔터티 본문의 어느 부분도 변경하지 않도록 설정합니다. |
| void [set_OnlyIfCached](./set_onlyifcached/)(**bool**) | 클라이언트가 오직 캐시된 항목만 사용하도록 설정합니다. |
| void [set_Private](./set_private/)(**bool**) | HTTP 응답 메시지 또는 그 일부가 단일 사용자용이며 공유 캐시에서 캐시되지 않도록 설정합니다. |
| void [set_ProxyRevalidate](./set_proxyrevalidate/)(**bool**) | 서버가 공유 사용자 에이전트 캐시에서 캐시 항목이 오래될 때 재검증을 요구하도록 설정합니다. |
| void [set_Public](./set_public/)(**bool**) | HTTP 응답이 모든 캐시에서 캐시될 수 있도록 설정합니다. |
| void [set_SharedMaxAge](./set_sharedmaxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | 공유 캐시에서 'Cache-Control'의 'max-age' 지시어 또는 'Expires' 헤더를 재정의하는 공유 최대 연령 값을 초 단위로 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 weak 포인터(공유가 아닌)로 설정합니다. 컨테이너의 포인터를 weak 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 레퍼런스 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출하면 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출하면 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| [String](../../system/string/) [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환합니다. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | 전달된 문자열을 [CacheControlHeaderValue](./) 클래스 인스턴스로 변환을 시도합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문을 풀이하는 구현입니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak 레퍼런스 카운트를 증가시킵니다. 직접 호출하면 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak 레퍼런스 카운트를 감소시킵니다. 직접 호출하면 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [ICloneable](../../system/icloneable/)
* 네임스페이스 [System::Net::Http::Headers](../)
* 라이브러리 [Aspose.Slides](../../)