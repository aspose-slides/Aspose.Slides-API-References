---
title: IPAddress
second_title: Aspose.Slides for C++ API 참조
description: "IP 주소를 나타냅니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여만 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하여 인스턴스를 만들지 마십시오. 이렇게 하면 런타임 오류 및/또는 단언 오류가 발생할 수 있습니다. 항상 이 클래스를 System::SmartPtr 포인터에 래핑하고 해당 포인터를 함수 인자로 전달하십시오."
type: docs
weight: 326
url: /ko/system.net/ipaddress/
---
## IPAddress 클래스

IP 주소를 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하여 인스턴스를 만들지 마십시오. 이렇게 하면 런타임 오류 및/또는 단언 오류가 발생할 수 있습니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터에 래핑하고 해당 포인터를 함수 인자로 전달하십시오.

```cpp
class IPAddress : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | C# [Object.Equals](../../system/object/equals/) 구문을 사용하여 객체를 비교합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 구문을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, C# 스타일 부동소수점 비교를 흉내 내어 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, C# 스타일 부동소수점 비교를 흉내 내어 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| [System::Net::Sockets::AddressFamily](../../system.net.sockets/addressfamily/) [get_AddressFamily](./get_addressfamily/)() | 주소 패밀리를 반환합니다. |
| **bool** [get_IsIPv4MappedToIPv6](./get_isipv4mappedtoipv6/)() | 주소가 IPv4 주소이며 IPv6 주소에 매핑되는지를 나타내는 값을 반환합니다. |
| **bool** [get_IsIPv6LinkLocal](./get_isipv6linklocal/)() | 주소가 IPv6 링크 로컬 주소인지 여부를 나타내는 값을 반환합니다. |
| **bool** [get_IsIPv6Multicast](./get_isipv6multicast/)() | 주소가 전역 IPv6 멀티캐스트 주소인지 여부를 나타내는 값을 반환합니다. |
| **bool** [get_IsIPv6SiteLocal](./get_isipv6sitelocal/)() | 주소가 IPv6 사이트 로컬 주소인지 여부를 나타내는 값을 반환합니다. |
| **bool** [get_IsIPv6Teredo](./get_isipv6teredo/)() | 주소가 IPv6 Teredo 주소인지 여부를 나타내는 값을 반환합니다. |
| **int64_t** [get_ScopeId](./get_scopeid/)() | IPv6 주소의 스코프 식별자를 가져옵니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetAddressBytes](./getaddressbytes/)() | IP 주소의 바이트 배열을 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| [ImplPtr](./implptr/) [GetImpl](./getimpl/)() const | 구현에 대한 포인터를 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| static **int64_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int64_t**) | 지정된 호스트 바이트 순서를 해당 네트워크 바이트 순서로 변환합니다. |
| static **int32_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int32_t**) | 지정된 호스트 바이트 순서를 해당 네트워크 바이트 순서로 변환합니다. |
| static **int16_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int16_t**) | 지정된 호스트 바이트 순서를 해당 네트워크 바이트 순서로 변환합니다. |
|  [IPAddress](./ipaddress/)(**int64_t**) | 새 인스턴스를 생성합니다. |
|  [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int64_t**) | 새 인스턴스를 생성합니다. |
|  [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 새 인스턴스를 생성합니다. |
|  [IPAddress](./ipaddress/)() | 새 인스턴스를 생성합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| static **bool** [IsLoopback](./isloopback/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>) | 지정된 주소가 루프백 주소인지 여부를 나타내는 값을 반환합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현한 잠금입니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv4](./maptoipv4/)() | 주소를 IPv4 주소로 매핑합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv6](./maptoipv6/)() | 주소를 IPv6 주소로 매핑합니다. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
| static **int64_t** [NetworkToHostOrder](./networktohostorder/)(**int64_t**) | 지정된 네트워크 바이트 순서를 해당 호스트 바이트 순서로 변환합니다. |
| static **int32_t** [NetworkToHostOrder](./networktohostorder/)(**int32_t**) | 지정된 네트워크 바이트 순서를 해당 호스트 바이트 순서로 변환합니다. |
| static **int16_t** [NetworkToHostOrder](./networktohostorder/)(**int16_t**) | 지정된 네트워크 바이트 순서를 해당 호스트 바이트 순서로 변환합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않고, 새 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않고, 새 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [Parse](./parse/)([String](../../system/string/)) | 전달된 문자열을 [IPAddress](./) 클래스의 인스턴스로 변환합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체와 nullptr을 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_ScopeId](./set_scopeid/)(**int64_t**) | IPv6 주소의 스코프 식별자를 설정합니다. |
| void [SetImpl](./setimpl/)([ImplPtr](./implptr/)) | 구현에 대한 포인터를 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유가 아닌 약한 포인터로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| [String](../../system/string/) [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>\&) | 전달된 문자열을 [IPAddress](./) 클래스의 인스턴스로 변환하려 시도합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제 구현입니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 필드

| 필드 | 설명 |
| --- | --- |
| static [Any](./any/) | 서버가 모든 네트워크 인터페이스를 수신해야 함을 나타내는 IPv4 주소. |
| static [Broadcast](./broadcast/) | IPv4 브로드캐스트 주소. |
| static [IPv6Any](./ipv6any/) | 서버가 모든 네트워크 인터페이스를 수신해야 함을 나타내는 IPv6 주소. |
| static [IPv6Loopback](./ipv6loopback/) | IPv6 루프백 주소. |
| static [IPv6None](./ipv6none/) | 서버가 어떤 네트워크 인터페이스도 수신하지 않아야 함을 나타내는 IPv6 주소. |
| static [Loopback](./loopback/) | IPv4 루프백 주소. |
| static [None](./none/) | 서버가 어떤 네트워크 인터페이스도 수신하지 않아야 함을 나타내는 IPv4 주소. |

## 타입정의

| 타입정의 | 설명 |
| --- | --- |
| [ImplPtr](./implptr/) | 구현 타입에 대한 포인터. |

## 참고

* 클래스 [Object](../../system/object/)
* 네임스페이스 [System::Net](../)
* 라이브러리 [Aspose.Slides](../../)