---
title: Receive()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 서버가 보낸 데이터그램을 반환합니다.
type: docs
weight: 92
url: /ko/system.net.sockets/udpclient/receive/
---
## UdpClient::Receive(System::SharedPtr\<IPEndPoint\>\&) 메서드

서버가 보낸 데이터그램을 반환합니다.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::UdpClient::Receive(System::SharedPtr<IPEndPoint> &remoteEP)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\>\& | 데이터가 전송된 원격 호스트를 나타내는 [IPEndPoint](../../../system.net/ipendpoint/)입니다. |

### 반환값

수신된 데이터가 할당될 바이트 배열입니다.

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IPEndPoint](../../../system.net/ipendpoint/)
* 클래스 [UdpClient](../)
* 네임스페이스 [System::Net::Sockets](../../)
* 라이브러리 [Aspose.Slides](../../../)