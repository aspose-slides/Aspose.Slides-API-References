---
title: Send()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 원격 엔드 포인트에 있는 호스트에 UDP 데이터그램을 보냅니다.
type: docs
weight: 79
url: /ko/system.net.sockets/udpclient/send/
---
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) 메서드

원격 엔드 포인트에 있는 호스트에 UDP 데이터그램을 보냅니다.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, System::SharedPtr<IPEndPoint> endPoint)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 전송할 [Byte](../../../system/byte/) 형식의 배열 |
| bytes | **int32_t** | 데이터그램의 바이트 수 |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | 데이터그램을 전송할 호스트와 포트를 나타내는 [IPEndPoint](../../../system.net/ipendpoint/) |

### 반환 값

전송된 바이트 수입니다.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) 메서드

지정된 원격 호스트의 지정된 포트에 UDP 데이터그램을 보냅니다.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, String hostname, int32_t port)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 전송할 [Byte](../../../system/byte/) 형식의 배열 |
| bytes | **int32_t** | 데이터그램의 바이트 수 |
| hostname | [String](../../../system/string/) | 원격 호스트의 이름 |
| port | **int32_t** | 원격 포트 번호 |

### 반환 값

전송된 바이트 수입니다.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t) 메서드

원격 호스트에 UDP 데이터그램을 보냅니다.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 전송할 [Byte](../../../system/byte/) 형식의 배열 |
| bytes | **int32_t** | 데이터그램의 바이트 수 |

### 반환 값

전송된 바이트 수입니다.

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [UdpClient](../)
* Class [String](../../../system/string/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)