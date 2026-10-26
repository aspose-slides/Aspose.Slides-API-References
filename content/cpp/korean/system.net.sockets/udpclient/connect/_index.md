---
title: Connect()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 호스트의 지정된 포트에 연결을 설정합니다.
type: docs
weight: 66
url: /ko/system.net.sockets/udpclient/connect/
---
## UdpClient::Connect(String, int32_t) 메서드

지정된 호스트의 지정된 포트에 연결을 설정합니다.

```cpp
void System::Net::Sockets::UdpClient::Connect(String hostname, int32_t port)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | 연결하려는 원격 DNS 호스트의 이름입니다. |
| port | **int32_t** | 통신하려는 로컬 포트 번호입니다. |

## UdpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) 메서드

지정된 주소와 포트에서 호스트와 연결을 설정합니다.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPAddress> addr, int32_t port)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| addr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | 데이터를 전송할 원격 호스트의 [IPAddress](../../../system.net/ipaddress/)입니다. |
| port | **int32_t** | 통신하려는 로컬 포트 번호입니다. |

## UdpClient::Connect(System::SharedPtr\<IPEndPoint\>) 메서드

원격 끝점에 연결을 설정합니다.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPEndPoint> endPoint)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | UDP 연결을 바인드할 끝점입니다. |

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [UdpClient](../)
* 클래스 [IPAddress](../../../system.net/ipaddress/)
* 클래스 [IPEndPoint](../../../system.net/ipendpoint/)
* 네임스페이스 [System::Net::Sockets](../../)
* 라이브러리 [Aspose.Slides](../../../)