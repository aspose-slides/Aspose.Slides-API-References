---
title: ServicePointManager
second_title: Aspose.Slides for C++ API 레퍼런스
description: "ServicePoint 클래스 인스턴스의 수명 주기 단계(생성, 유지 및 삭제)를 관리합니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용해 인스턴스를 만들면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고, 해당 포인터를 함수 인수로 전달하십시오."
type: docs
weight: 430
url: /ko/system.net/servicepointmanager/
---
## ServicePointManager 클래스

[ServicePoint](../servicepoint/) 클래스 인스턴스의 수명 주기 단계(생성, 유지 및 삭제)를 관리합니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용해 인스턴스를 만들면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고, 해당 포인터를 함수 인수로 전달하십시오.

```cpp
class ServicePointManager : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동소수점 비교에서 두 NaN을 동일하게 취급합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동소수점 비교에서 두 NaN을 동일하게 취급합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\> [get_CertificatePolicy](./get_certificatepolicy/)() | 인증서 정책을 가져옵니다. |
| static **bool** [get_CheckCertificateRevocationList](./get_checkcertificaterevocationlist/)() | 인증서를 인증서 권한 철회 목록과 확인해야 하는지를 나타내는 값을 가져옵니다. |
| static **int32_t** [get_DefaultConnectionLimit](./get_defaultconnectionlimit/)() | ServicePoint 클래스 인스턴스가 허용하는 최대 동시 연결 수를 가져옵니다. |
| static **int32_t** [get_DnsRefreshTimeout](./get_dnsrefreshtimeout/)() | DNS 해석이 유효하다고 간주되는 시간(밀리초)을 가져옵니다. |
| static **bool** [get_EnableDnsRoundRobin](./get_enablednsroundrobin/)() | DNS 해석이 적용 가능한 IP 주소 사이에서 순환되는지를 나타내는 값을 가져옵니다. |
| static [System::Net::Security::EncryptionPolicy](../../system.net.security/encryptionpolicy/) [get_EncryptionPolicy](./get_encryptionpolicy/)() | 현재 인스턴스에서 사용하는 암호화 정책을 반환합니다. |
| static **bool** [get_Expect100Continue](./get_expect100continue/)() | ServicePoint 클래스 인스턴스가 100-Continue 동작을 사용하는지를 나타내는 값을 가져옵니다. |
| static **int32_t** [get_MaxServicePointIdleTime](./get_maxservicepointidletime/)() | ServicePoint 클래스 인스턴스의 최대 유휴 시간을 가져옵니다. |
| static **int32_t** [get_MaxServicePoints](./get_maxservicepoints/)() | 현재 인스턴스가 관리할 수 있는 ServicePoint 클래스 인스턴스의 최대 수를 가져옵니다. |
| static **bool** [get_ReusePort](./get_reuseport/)() | 출력 연결 소켓이 'SO_REUSE_UNICASTPORT' 옵션을 사용하는지를 나타내는 값을 가져옵니다. |
| static [SecurityProtocolType](../securityprotocoltype/) [get_SecurityProtocol](./get_securityprotocol/)() | 현재 인스턴스가 관리하는 ServicePoint 클래스 인스턴스에서 사용되는 보안 프로토콜 유형을 가져옵니다. |
| static [Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/) [get_ServerCertificateValidationCallback](./get_servercertificatevalidationcallback/)() | 서버 인증서를 검증하는 콜백을 가져옵니다. |
| static **bool** [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | ServicePoint 클래스 인스턴스가 Nagle 알고리즘을 사용하는지를 나타내는 값을 가져옵니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 동일합니다. 사용자 정의 객체의 해싱을 지원합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 동일합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 지정된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 동일합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시자를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 동일합니다. 사용자 정의 타입 복제를 지원합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며, 하위 클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며, 하위 클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체와 nullptr를 참조 기준으로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 문자열과 nullptr 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 문자열 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| static void [set_CertificatePolicy](./set_certificatepolicy/)([System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\>) | 인증서 정책을 설정합니다. |
| static void [set_CheckCertificateRevocationList](./set_checkcertificaterevocationlist/)(**bool**) | 인증서를 인증서 권한 철회 목록과 확인해야 하는지를 나타내는 값을 설정합니다. |
| static void [set_DefaultConnectionLimit](./set_defaultconnectionlimit/)(**int32_t**) | ServicePoint 클래스 인스턴스가 허용하는 최대 동시 연결 수를 설정합니다. |
| static void [set_DnsRefreshTimeout](./set_dnsrefreshtimeout/)(**int32_t**) | DNS 해석이 유효하다고 간주되는 시간(밀리초)을 설정합니다. |
| static void [set_EnableDnsRoundRobin](./set_enablednsroundrobin/)(**bool**) | DNS 해석이 적용 가능한 IP 주소 사이에서 순환되는지를 나타내는 값을 설정합니다. |
| static void [set_Expect100Continue](./set_expect100continue/)(**bool**) | ServicePoint 클래스 인스턴스가 100-Continue 동작을 사용하는지를 설정합니다. |
| static void [set_MaxServicePointIdleTime](./set_maxservicepointidletime/)(**int32_t**) | ServicePoint 클래스 인스턴스의 최대 유휴 시간을 설정합니다. |
| static void [set_MaxServicePoints](./set_maxservicepoints/)(**int32_t**) | 현재 인스턴스가 관리할 수 있는 ServicePoint 클래스 인스턴스의 최대 수를 설정합니다. |
| static void [set_ReusePort](./set_reuseport/)(**bool**) | 출력 연결 소켓이 'SO_REUSE_UNICASTPORT' 옵션을 사용하는지를 설정합니다. |
| static void [set_SecurityProtocol](./set_securityprotocol/)([SecurityProtocolType](../securityprotocoltype/)) | 현재 인스턴스가 관리하는 ServicePoint 클래스 인스턴스에서 사용되는 보안 프로토콜 유형을 설정합니다. |
| static void [set_ServerCertificateValidationCallback](./set_servercertificatevalidationcallback/)([Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/)) | 서버 인증서를 검증하는 콜백을 설정합니다. |
| static void [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(**bool**) | ServicePoint 클래스 인스턴스가 Nagle 알고리즘을 사용하는지를 설정합니다. |
| static void [SetTcpKeepAlive](./settcpkeepalive/)(**bool**, **int32_t**, **int32_t**) | 'Keep-Alive' 옵션이 활성화되어 있는지를 나타내는 값을 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터로 설정합니다(공유 대신). 컨테이너에서 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 동일합니다. 사용자 정의 객체를 문자열로 변환할 수 있습니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시자를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 필드

| 필드 | 설명 |
| --- | --- |
| static [DefaultNonPersistentConnectionLimit](./defaultnonpersistentconnectionlimit/) | 비영구 연결의 기본 수입니다. |
| static [DefaultPersistentConnectionLimit](./defaultpersistentconnectionlimit/) | 영구 연결의 기본 수입니다. |

## 참조

* 클래스 [Object](../../system/object/)
* 네임스페이스 [System::Net](../)
* 라이브러리 [Aspose.Slides](../../)