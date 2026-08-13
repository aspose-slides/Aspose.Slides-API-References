---
title: TcpClient
second_title: Aspose.Slides for C++ API 레퍼런스
description: "TCP 네트워크 서비스용 클라이언트를 나타냅니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택이나 operator new를 사용해 이 유형의 인스턴스를 생성하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고 해당 포인터를 함수 인수로 전달하십시오."
type: docs
weight: 66
url: /ko/system.net.sockets/tcpclient/
---
## TcpClient 클래스

TCP 네트워크 서비스용 클라이언트를 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여 할당해야 합니다. 스택이나 operator new를 사용하여 이 유형의 인스턴스를 생성하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고 해당 포인터를 함수 인수로 전달하십시오.

```cpp
class TcpClient : public System::IDisposable
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([String](../../system/string/), **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 비동기 연결 작업을 시작합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 비동기 연결 작업을 시작합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 비동기 연결 작업을 시작합니다. |
| void [Close](./close/)() | 연결을 닫고 현재 인스턴스를 해제합니다. |
| void [Connect](./connect/)([String](../../system/string/), **int32_t**) | 지정된 원격 호스트에 연결을 설정합니다. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**) | 지정된 원격 호스트에 연결을 설정합니다. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | 지정된 원격 호스트에 연결을 설정합니다. |
| void [Connect](./connect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**) | 지정된 원격 호스트에 연결을 설정합니다. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | 아무 작업도 하지 않습니다. |
| void [EndConnect](./endconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | 지정된 비동기 연결 작업이 완료될 때까지 대기합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| **int32_t** [get_Available](./get_available/)() | 수신되어 읽을 준비가 된 바이트 수를 반환합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\> [get_Client](./get_client/)() | 소켓을 가져옵니다. |
| **bool** [get_Connected](./get_connected/)() | 소켓이 원격 호스트에 연결되어 있는지를 나타내는 값을 반환합니다. |
| **bool** [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | 현재 인스턴스가 포트를 하나의 클라이언트만 사용할 수 있도록 허용하는지를 나타내는 값을 가져옵니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\> [get_LingerState](./get_lingerstate/)() | 소켓이 보류 중인 모든 데이터를 전송하려고 닫기를 지연시킬지 여부를 나타내는 값을 가져옵니다. |
| **bool** [get_NoDelay](./get_nodelay/)() | 현재 인스턴스가 Nagle 알고리즘을 사용하고 있는지를 나타내는 값을 가져옵니다. |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | 데이터 수신에 사용되는 버퍼 크기를 가져옵니다. |
| **int32_t** [get_ReceiveTimeout](./get_receivetimeout/)() | 데이터 수신이 시간 초과될 시간량을 나타내는 값을 가져옵니다. |
| **int32_t** [get_SendBufferSize](./get_sendbuffersize/)() | 데이터 전송에 사용되는 버퍼 크기를 가져옵니다. |
| **int32_t** [get_SendTimeout](./get_sendtimeout/)() | 데이터 전송이 시간 초과될 시간량을 나타내는 값을 가져옵니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드의 유사 버전입니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[NetworkStream](../networkstream/)\> [GetStream](./getstream/)() | 데이터 송수신에 사용되는 스트림을 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사 버전입니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType이 설명하는 타입의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자의 유사 버전입니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 구문의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시자 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드의 유사 버전입니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사를 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사를 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값형 객체를 nullptr와 레퍼런스 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| void [set_Client](./set_client/)([System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\>) | 소켓을 설정합니다. |
| void [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(**bool**) | 현재 인스턴스가 포트를 하나의 클라이언트만 사용할 수 있도록 허용하는지를 나타내는 값을 설정합니다. |
| void [set_LingerState](./set_lingerstate/)([System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\>) | 소켓이 보류 중인 모든 데이터를 전송하려고 닫기를 지연시킬지 여부를 나타내는 값을 설정합니다. |
| void [set_NoDelay](./set_nodelay/)(**bool**) | 현재 인스턴스가 Nagle 알고리즘을 사용하고 있는지를 나타내는 값을 설정합니다. |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | 데이터 수신에 사용되는 버퍼 크기를 설정합니다. |
| void [set_ReceiveTimeout](./set_receivetimeout/)(**int32_t**) | 데이터 수신이 시간 초과될 시간량을 나타내는 값을 설정합니다. |
| void [set_SendBufferSize](./set_sendbuffersize/)(**int32_t**) | 데이터 전송에 사용되는 버퍼 크기를 설정합니다. |
| void [set_SendTimeout](./set_sendtimeout/)(**int32_t**) | 데이터 전송이 시간 초과될 시간량을 나타내는 값을 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 공유 포인터 대신 약한 포인터로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 레퍼런스 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
|  [TcpClient](./tcpclient/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | 새 인스턴스를 생성합니다. |
|  [TcpClient](./tcpclient/)() | 새 인스턴스를 생성합니다. |
|  [TcpClient](./tcpclient/)([AddressFamily](../addressfamily/)) | 새 인스턴스를 생성합니다. |
|  [TcpClient](./tcpclient/)([String](../../system/string/), **int32_t**) | 새 인스턴스를 생성합니다. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드의 유사 버전입니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시자 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
| virtual  [~TcpClient](./~tcpclient/)() | 현재 인스턴스를 파괴합니다. |

## 참고

* 클래스 [IDisposable](../../system/idisposable/)
* 네임스페이스 [System::Net::Sockets](../)
* 라이브러리 [Aspose.Slides](../../)