---
title: Socket
second_title: Aspose.Slides for C++ API 레퍼런스
description: Socket 클래스는 Berkeley 소켓 인터페이스를 구현합니다.
type: docs
weight: 53
url: /ko/system.net.sockets/socket/
---
## Socket 클래스

[Socket](./) 클래스는 Berkeley 소켓 인터페이스를 구현합니다.

```cpp
class Socket : public System::IDisposable
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Socket](./)\> [Accept](./accept/)() | 새로 생성된 연결을 위해 새 소켓을 만듭니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 비동기 연결 작업을 시작합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([String](../../system/string/), **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 비동기 연결 작업을 시작합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 비동기 연결 작업을 시작합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 비동기 연결 작업을 시작합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginReceive](./beginreceive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 비동기 쓰기 작업을 시작합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginSend](./beginsend/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 비동기 전송 작업을 시작합니다. |
| void [Bind](./bind/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | 소켓을 지정된 로컬 엔드포인트에 바인딩합니다. |
| void [Close](./close/)() | 소켓 연결을 닫습니다. |
| void [Close](./close/)(int) | 대기 중인 데이터를 전송할 수 있도록 지정된 시간 제한으로 소켓 연결을 닫습니다. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | 지정된 원격 엔드포인트에 연결을 설정합니다. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**) | 지정된 원격 엔드포인트에 연결을 설정합니다. |
| void [Connect](./connect/)([String](../../system/string/), **int32_t**) | 지정된 원격 엔드포인트에 연결을 설정합니다. |
| void [Connect](./connect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**) | 지정된 원격 엔드포인트에 연결을 설정합니다. |
| void [Dispose](./dispose/)() override | 아무 동작도 하지 않습니다. |
| void [EndConnect](./endconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | 지정된 비동기 연결 작업이 완료될 때까지 대기합니다. |
| **int32_t** [EndReceive](./endreceive/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | 지정된 비동기 수신 작업이 완료될 때까지 대기합니다. |
| **int32_t** [EndReceive](./endreceive/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>, [SocketError](../socketerror/)\&) | 지정된 비동기 수신 작업이 완료될 때까지 대기합니다. |
| **int32_t** [EndSend](./endsend/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | 지정된 비동기 전송 작업이 완료될 때까지 대기합니다. |
| **int32_t** [EndSend](./endsend/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>, [SocketError](../socketerror/)\&) | 지정된 비동기 전송 작업이 완료될 때까지 대기합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| [System::Net::Sockets::AddressFamily](../addressfamily/) [get_AddressFamily](./get_addressfamily/)() | 주소 패밀리를 반환합니다. |
| **int32_t** [get_Available](./get_available/)() | 네트워크에서 수신된 바이트 수와 읽을 수 있는 바이트 수를 가져옵니다. |
| **bool** [get_Blocking](./get_blocking/)() | 소켓이 차단 모드인지 여부를 나타내는 값을 가져옵니다. |
| **bool** [get_Connected](./get_connected/)() | 소켓이 원격 호스트에 연결되어 있는지 여부를 나타내는 값을 반환합니다. |
| **bool** [get_DontFragment](./get_dontfragment/)() | 소켓이 IP 데이터그램을 분할하도록 허용하는지 여부를 나타내는 값을 가져옵니다. |
| **bool** [get_DualMode](./get_dualmode/)() | 소켓이 이중 모드인지 여부를 나타내는 값을 가져옵니다. |
| **bool** [get_EnableBroadcast](./get_enablebroadcast/)() | 소켓이 브로드캐스트 패킷을 허용하는지 여부를 나타내는 값을 가져옵니다. |
| **bool** [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | 소켓을 포트에 바인딩할 수 있는 프로세스가 하나인지 여부를 나타내는 값을 가져옵니다. |
| **bool** [get_IsBound](./get_isbound/)() | 소켓이 특정 로컬 포트에 바인딩되어 있는지 여부를 나타내는 값을 반환합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\> [get_LingerState](./get_lingerstate/)() | 소켓이 모든 대기 중인 데이터를 전송하려고 닫기를 지연시킬지 여부를 나타내는 값을 가져옵니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\> [get_LocalEndPoint](./get_localendpoint/)() | 로컬 엔드포인트를 반환합니다. |
| **bool** [get_MulticastLoopback](./get_multicastloopback/)() | 소켓이 나가는 멀티캐스트 패킷을 수신하는지 여부를 나타내는 값을 가져옵니다. |
| **bool** [get_NoDelay](./get_nodelay/)() | 소켓이 Nagle 알고리즘을 사용하는지 여부를 나타내는 값을 가져옵니다. |
| static **bool** [get_OSSupportsIPv4](./get_ossupportsipv4/)() | 운영 체제와 네트워크 어댑터가 IPv4를 지원하는지 여부를 나타내는 값을 반환합니다. |
| static **bool** [get_OSSupportsIPv6](./get_ossupportsipv6/)() | 운영 체제와 네트워크 어댑터가 IPv6를 지원하는지 여부를 나타내는 값을 반환합니다. |
| [System::Net::Sockets::ProtocolType](../protocoltype/) [get_ProtocolType](./get_protocoltype/)() | 프로토콜 유형을 반환합니다. |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | 수신 버퍼 크기를 가져옵니다. |
| **int32_t** [get_ReceiveTimeout](./get_receivetimeout/)() | 'Receive' 호출이 시간 초과되는 기간을 가져옵니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\> [get_RemoteEndPoint](./get_remoteendpoint/)() | 원격 엔드포인트를 반환합니다. |
| **int32_t** [get_SendBufferSize](./get_sendbuffersize/)() | 전송 버퍼 크기를 가져옵니다. |
| **int32_t** [get_SendTimeout](./get_sendtimeout/)() | 'Send' 호출이 시간 초과되는 기간을 가져옵니다. |
| [System::Net::Sockets::SocketType](../sockettype/) [get_SocketType](./get_sockettype/)() | 소켓 유형을 반환합니다. |
| static **bool** [get_SupportsIPv4](./get_supportsipv4/)() | 현재 호스트가 IPv4를 지원하는지 여부를 나타내는 값을 반환합니다. |
| **int16_t** [get_Ttl](./get_ttl/)() | TTL 값을 가져옵니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| [ImplPtr](./implptr/) [GetImpl](./getimpl/)() const | 구현에 대한 포인터를 반환합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/)) | 지정된 옵션 이름에 해당하는 값을 반환합니다. |
| void [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 지정된 옵션 이름에 해당하는 값을 가져옵니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **int32_t**) | 지정된 옵션 이름에 해당하는 값을 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| **int32_t** [IOControl](./iocontrol/)(**int32_t**, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 소켓에 대한 저수준 운영 모드를 설정합니다. |
| **int32_t** [IOControl](./iocontrol/)([IOControlCode](../iocontrolcode/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 소켓에 대한 저수준 운영 모드를 설정합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Listen](./listen/)(**int32_t**) | 소켓 상태를 'listen'으로 변경합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문 구문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하세요. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스 복사를 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스 복사를 가능하게 합니다. |
| **bool** [Poll](./poll/)(**int32_t**, [SelectMode](../selectmode/)) | 지정된 폴링 모드에 따라 소켓의 상태를 반환합니다. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | 소켓으로부터 데이터를 수신하여 지정된 바이트 배열에 씁니다. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | 소켓으로부터 데이터를 수신하여 지정된 바이트 배열에 씁니다. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/)) | 소켓으로부터 데이터를 수신하여 지정된 바이트 배열에 씁니다. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/)) | 소켓으로부터 데이터를 수신하여 지정된 바이트 배열에 씁니다. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/)) | 소켓으로부터 데이터를 수신하여 지정된 바이트 배열에 씁니다. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/)) | 소켓으로부터 데이터를 수신하여 지정된 바이트 배열에 씁니다. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 소켓으로부터 데이터를 수신하여 지정된 바이트 배열에 씁니다. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>) | 소켓으로부터 데이터를 수신하여 지정된 바이트 배열에 씁니다. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&) | 소켓으로부터 데이터를 수신하여 지정된 바이트 배열에 씁니다. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | 소켓으로부터 데이터를 수신하여 지정된 바이트 배열에 씁니다. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | 소켓으로부터 데이터를 수신하여 지정된 바이트 배열에 씁니다. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | 소켓으로부터 데이터를 수신하여 지정된 바이트 배열에 씁니다. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | 소켓으로부터 데이터를 수신하여 지정된 바이트 배열에 씁니다. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | 소켓으로부터 데이터를 수신하여 지정된 바이트 배열에 씁니다. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | 소켓으로부터 데이터를 수신하여 지정된 바이트 배열에 씁니다. |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>) | 소켓으로부터 데이터를 수신하여 지정된 바이트 배열에 씁니다. |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/)) | 소켓으로부터 데이터를 수신하여 지정된 바이트 배열에 씁니다. |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | 소켓으로부터 데이터를 수신하여 지정된 바이트 배열에 씁니다. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | 지정된 엔드포인트로부터 데이터를 수신하여 지정된 바이트 배열에 씁니다. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | 지정된 엔드포인트로부터 데이터를 수신하여 지정된 바이트 배열에 씁니다. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | 지정된 엔드포인트로부터 데이터를 수신하여 지정된 바이트 배열에 씁니다. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | 지정된 엔드포인트로부터 데이터를 수신하여 지정된 바이트 배열에 씁니다. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | 지정된 엔드포인트로부터 데이터를 수신하여 지정된 바이트 배열에 씁니다. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | 지정된 엔드포인트에서 데이터를 수신하고 지정된 바이트 배열에 씁니다. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | 지정된 엔드포인트에서 데이터를 수신하고 지정된 바이트 배열에 씁니다. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | 지정된 엔드포인트에서 데이터를 수신하고 지정된 바이트 배열에 씁니다. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | 지정된 엔드포인트에서 데이터를 수신하고 지정된 바이트 배열에 씁니다. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | 지정된 엔드포인트에서 데이터를 수신하고 지정된 바이트 배열에 씁니다. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | 지정된 엔드포인트에서 데이터를 수신하고 지정된 바이트 배열에 씁니다. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | 지정된 엔드포인트에서 데이터를 수신하고 지정된 바이트 배열에 씁니다. |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | 지정된 엔드포인트에서 데이터를 수신하고 지정된 바이트 배열에 씁니다. |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | 지정된 엔드포인트에서 데이터를 수신하고 지정된 바이트 배열에 씁니다. |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | 지정된 엔드포인트에서 데이터를 수신하고 지정된 바이트 배열에 씁니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | 지정된 데이터를 소켓으로 전송합니다. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | 지정된 데이터를 소켓으로 전송합니다. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/)) | 지정된 데이터를 소켓으로 전송합니다. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/)) | 지정된 데이터를 소켓으로 전송합니다. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/)) | 지정된 데이터를 소켓으로 전송합니다. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/)) | 지정된 데이터를 소켓으로 전송합니다. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 지정된 데이터를 소켓으로 전송합니다. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>) | 지정된 데이터를 소켓으로 전송합니다. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&) | 지정된 데이터를 소켓으로 전송합니다. |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>) | 지정된 데이터를 소켓으로 전송합니다. |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/)) | 지정된 데이터를 소켓으로 전송합니다. |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | 지정된 데이터를 소켓으로 전송합니다. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | 지정된 데이터를 소켓으로 전송합니다. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | 지정된 데이터를 소켓으로 전송합니다. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | 지정된 데이터를 소켓으로 전송합니다. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | 지정된 데이터를 소켓으로 전송합니다. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | 지정된 데이터를 소켓으로 전송합니다. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | 지정된 데이터를 소켓으로 전송합니다. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | 지정된 데이터를 지정된 엔드포인트로 전송합니다. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | 지정된 데이터를 지정된 엔드포인트로 전송합니다. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | 지정된 데이터를 지정된 엔드포인트로 전송합니다. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | 지정된 데이터를 지정된 엔드포인트로 전송합니다. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | 지정된 데이터를 지정된 엔드포인트로 전송합니다. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | 지정된 데이터를 지정된 엔드포인트로 전송합니다. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | 지정된 데이터를 지정된 엔드포인트로 전송합니다. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | 지정된 데이터를 지정된 엔드포인트로 전송합니다. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | 지정된 데이터를 지정된 엔드포인트로 전송합니다. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | 지정된 데이터를 지정된 엔드포인트로 전송합니다. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | 지정된 데이터를 지정된 엔드포인트로 전송합니다. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | 지정된 데이터를 지정된 엔드포인트로 전송합니다. |
| void [set_Blocking](./set_blocking/)(**bool**) | 소켓이 블록 모드인지 여부를 나타내는 값을 설정합니다. |
| void [set_ConnectionTimeout](./set_connectiontimeout/)(**int32_t**) | 연결 제한 시간을 설정합니다. |
| void [set_DontFragment](./set_dontfragment/)(**bool**) | 소켓이 IP 데이터그램의 단편화를 허용하는지 여부를 나타내는 값을 설정합니다. |
| void [set_DualMode](./set_dualmode/)(**bool**) | 소켓이 듀얼 모드인지 여부를 나타내는 값을 설정합니다. |
| void [set_EnableBroadcast](./set_enablebroadcast/)(**bool**) | 소켓이 브로드캐스트 패킷을 허용하는지 여부를 나타내는 값을 설정합니다. |
| void [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(**bool**) | 단일 프로세스만 소켓을 포트에 바인딩할 수 있는지 여부를 나타내는 값을 설정합니다. |
| void [set_LingerState](./set_lingerstate/)([System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\>) | 소켓이 모든 대기 중인 데이터를 전송하려고 시도하면서 닫는 것을 지연시킬지 여부를 나타내는 값을 설정합니다. |
| void [set_MulticastLoopback](./set_multicastloopback/)(**bool**) | 소켓이 송신 멀티캐스트 패킷을 수신하는지 여부를 나타내는 값을 설정합니다. |
| void [set_NoDelay](./set_nodelay/)(**bool**) | 소켓이 Nagle 알고리즘을 사용하는지 여부를 나타내는 값을 설정합니다. |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | 수신 버퍼 크기를 설정합니다. |
| void [set_ReceiveTimeout](./set_receivetimeout/)(**int32_t**) | 'Receive' 호출이 시간 초과될 기간을 설정합니다. |
| void [set_SendBufferSize](./set_sendbuffersize/)(**int32_t**) | 전송 버퍼 크기를 설정합니다. |
| void [set_SendTimeout](./set_sendtimeout/)(**int32_t**) | 'Send' 호출이 시간 초과될 기간을 설정합니다. |
| void [set_Ttl](./set_ttl/)(**int16_t**) | TTL 값을 설정합니다. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **int32_t**) | 지정된 소켓 옵션을 지정된 값으로 설정합니다. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 지정된 소켓 옵션을 지정된 값으로 설정합니다. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **bool**) | 지정된 소켓 옵션을 지정된 값으로 설정합니다. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 지정된 소켓 옵션을 지정된 값으로 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터(공유 포인터가 아니라)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [Shutdown](./shutdown/)([SocketShutdown](../socketshutdown/)) | 소켓의 전송 및 수신 작업을 비활성화합니다. |
|  [Socket](./socket/)([System::Net::Sockets::SocketType](../sockettype/), [System::Net::Sockets::ProtocolType](../protocoltype/)) | 새 인스턴스를 생성합니다. |
|  [Socket](./socket/)([System::Net::Sockets::AddressFamily](../addressfamily/), [System::Net::Sockets::SocketType](../sockettype/), [System::Net::Sockets::ProtocolType](../protocoltype/)) | 새 인스턴스를 생성합니다. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
| virtual  [~Socket](./~socket/)() | 현재 인스턴스를 소멸시킵니다. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [ImplPtr](./implptr/) | 소켓 구현입니다. |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.Slides](../../)