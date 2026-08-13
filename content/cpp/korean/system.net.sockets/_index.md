---
title: "System::Net::Sockets"
second_title: Aspose.Slides for C++ API 레퍼런스
description: 
type: docs
weight: 729
url: /ko/system.net.sockets/
---
## 클래스

| 클래스 | 설명 |
| --- | --- |
| [Details_SocketException](./details_socketexception/) | 소켓 오류가 발생했을 때 발생하는 예외를 나타냅니다. 이 클래스를 수동으로 인스턴스화하지 마십시오. 대신 SocketException 클래스를 사용하십시오. SocketException 클래스 인스턴스를 [System::SmartPtr](../system/smartptr/)에 래핑하지 마십시오. |
| [IPPacketInformation](./ippacketinformation/) | 패킷에 대한 정보를 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 이 유형의 인스턴스를 생성하거나 operator new 를 사용하지 마십시오. 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터로 래핑하고, 해당 포인터를 인수로 함수에 전달하십시오. |
| [LingerOption](./lingeroption/) | 소켓이 Close() 또는 Close() 메서드 호출 후에도 연결 상태를 유지할지 여부를 지정합니다. 또한 데이터 전송이 계속되는 경우 소켓이 연결된 상태를 유지하는 기간을 지정합니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 이 유형의 인스턴스를 생성하거나 operator new 를 사용하지 마십시오. 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터로 래핑하고, 해당 포인터를 인수로 함수에 전달하십시오. |
| [NetworkStream](./networkstream/) | 네트워크 액세스를 위한 데이터의 기본 스트림을 제공합니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 이 유형의 인스턴스를 생성하거나 operator new 를 사용하지 마십시오. 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터로 래핑하고, 해당 포인터를 인수로 함수에 전달하십시오. |
| [Socket](./socket/) | [Socket](./socket/) 클래스는 Berkeley sockets 인터페이스를 구현합니다. |
| [TcpClient](./tcpclient/) | TCP 네트워크 서비스를 위한 클라이언트를 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 이 유형의 인스턴스를 생성하거나 operator new 를 사용하지 마십시오. 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터로 래핑하고, 해당 포인터를 인수로 함수에 전달하십시오. |
| [TcpListener](./tcplistener/) | TCP 네트워크 서비스를 위한 리스너를 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 이 유형의 인스턴스를 생성하거나 operator new 를 사용하지 마십시오. 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터로 래핑하고, 해당 포인터를 인수로 함수에 전달하십시오. |
| [UdpClient](./udpclient/) | User Datagram Protocol (UDP) 네트워크 서비스를 제공합니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 이 유형의 인스턴스를 생성하거나 operator new 를 사용하지 마십시오. 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터로 래핑하고, 해당 포인터를 인수로 함수에 전달하십시오. |
## 함수

| 함수 | 설명 |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |
| **bool** [operator!=](./operator_not_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |
## 열거형

| 열거형 | 설명 |
| --- | --- |
| [SocketType](./sockettype/) | 소켓 유형을 열거합니다. |
| [AddressFamily](./addressfamily/) | 주소 패밀리를 열거합니다. |
| [IOControlCode](./iocontrolcode/) | [IO](../system.io/) 제어 코드를 열거합니다. |
| [ProtocolFamily](./protocolfamily/) | 프로토콜 패밀리를 열거합니다. |
| [ProtocolType](./protocoltype/) | 프로토콜 유형을 열거합니다. |
| [SelectMode](./selectmode/) | 소켓 상태를 폴링하기 위한 모드를 지정합니다. |
| [SocketError](./socketerror/) | 소켓 오류 유형을 열거합니다. |
| [SocketFlags](./socketflags/) | 소켓 메시지에 대한 상수 값을 제공합니다. |
| [SocketOptionLevel](./socketoptionlevel/) | '[Socket](./socket/)' 클래스의 소켓 옵션 레벨을 정의합니다. |
| [SocketOptionName](./socketoptionname/) | [Socket](./socket/) 클래스의 소켓 옵션 이름을 정의합니다. |
| [SocketShutdown](./socketshutdown/) | [Socket.Shutdown](./socket/shutdown/) 메서드에서 사용되는 상수를 정의합니다. |
## 타입 정의

| 타입 정의 | 설명 |
| --- | --- |
| [SocketException](./socketexception/) |  |