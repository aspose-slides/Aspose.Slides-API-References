---
title: ServicePoint
second_title: Aspose.Slides for C++ API 참조
description: "HTTP 연결 관리를 제공합니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여만 할당해야 합니다. 스택이나 operator new를 사용하여 이 타입의 인스턴스를 생성하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 System::SmartPtr 포인터로 래핑하고 해당 포인터를 인수로 함수에 전달하십시오."
type: docs
weight: 417
url: /ko/system.net/servicepoint/
---
## ServicePoint 클래스

HTTP 연결 관리를 제공합니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여만 할당되어야 합니다. 스택에 인스턴스를 만들거나 operator new를 사용해 생성하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 래핑하고 해당 포인터를 인수로 함수에 전달하십시오.

```cpp
class ServicePoint : public System::Object
```

## 메서드

| Method | Description |
| --- | --- |
| **bool** [CloseConnectionGroup](./closeconnectiongroup/)([String](../../system/string/)) | 지정된 연결 그룹에 속하는 연결을 닫고 제거합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Address](./get_address/)() | 현재 인스턴스가 연결되는 서버 URI를 반환합니다. |
| [BindIPEndPoint](../bindipendpoint/) [get_BindIPEndPointDelegate](./get_bindipendpointdelegate/)() | 현재 인스턴스와 로컬 [IPEndPoint](../ipendpoint/)를 연결하는 데 사용되는 대리자를 가져옵니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_Certificate](./get_certificate/)() | 현재 인스턴스가 사용하는 인증서를 반환합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_ClientCertificate](./get_clientcertificate/)() | 마지막 클라이언트 인증서를 반환합니다. |
| **int32_t** [get_ConnectionLeaseTimeout](./get_connectionleasetimeout/)() | 활성 [ServicePoint](./)가 닫히는 시간(밀리초) 초과값을 가져옵니다. |
| **int32_t** [get_ConnectionLimit](./get_connectionlimit/)() | 현재 인스턴스가 허용하는 최대 연결 수를 가져옵니다. |
| [String](../../system/string/) [get_ConnectionName](./get_connectionname/)() | 연결 이름을 반환합니다. |
| **int32_t** [get_CurrentConnections](./get_currentconnections/)() | 열린 연결 수를 반환합니다. |
| **bool** [get_Expect100Continue](./get_expect100continue/)() | 100-Continue 동작이 사용되는지를 나타내는 값을 가져옵니다. |
| [DateTime](../../system/datetime/) [get_IdleSince](./get_idlesince/)() | 호스트에 대한 최신 연결의 날짜와 시간을 반환합니다. |
| **int32_t** [get_MaxIdleTime](./get_maxidletime/)() | 유휴 연결이 닫히는 시간(밀리초) 값을 가져옵니다. |
| virtual [Version](../../system/version/) [get_ProtocolVersion](./get_protocolversion/)() | HTTP 버전을 반환합니다. |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | 수신 버퍼의 크기를 가져옵니다. |
| **bool** [get_SupportsPipelining](./get_supportspipelining/)() | 현재 인스턴스가 파이프라인 연결을 지원하는지를 나타내는 값을 반환합니다. |
| **bool** [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | 현재 인스턴스가 관리하는 연결에서 Nagle 알고리즘이 사용되는지를 나타내는 값을 가져옵니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
| [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 서브클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 서브클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값형 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열과 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| void [set_BindIPEndPointDelegate](./set_bindipendpointdelegate/)([BindIPEndPoint](../bindipendpoint/)) | 현재 인스턴스와 로컬 [IPEndPoint](../ipendpoint/)를 연결하는 데 사용되는 대리자를 설정합니다. |
| void [set_ConnectionLeaseTimeout](./set_connectionleasetimeout/)(**int32_t**) | 활성 [ServicePoint](./)가 닫히는 시간(밀리초) 초과값을 설정합니다. |
| void [set_ConnectionLimit](./set_connectionlimit/)(**int32_t**) | 현재 인스턴스가 허용하는 최대 연결 수를 설정합니다. |
| void [set_Expect100Continue](./set_expect100continue/)(**bool**) | 100-Continue 동작이 사용되는지를 나타내는 값을 설정합니다. |
| void [set_MaxIdleTime](./set_maxidletime/)(**int32_t**) | 유휴 연결이 닫히는 시간(밀리초) 값을 설정합니다. |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | 수신 버퍼의 크기를 설정합니다. |
| void [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(**bool**) | 현재 인스턴스가 관리하는 연결에서 Nagle 알고리즘이 사용되는지를 나타내는 값을 설정합니다. |
| void [SetTcpKeepAlive](./settcpkeepalive/)(**bool**, **int32_t**, **int32_t**) | 'Keep-Alive' 옵션이 활성화되는지를 나타내는 값을 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유 포인터가 아닌 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 레퍼런스 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용해야 합니다. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용해야 합니다. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용해야 합니다. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용해야 합니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 참고

* 클래스 [Object](../../system/object/)
* 네임스페이스 [System::Net](../)
* 라이브러리 [Aspose.Slides](../../)