---
title: TcpListener()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 인스턴스를 생성합니다.
type: docs
weight: 53
url: /ko/system.net.sockets/tcplistener/tcplistener/
---
## TcpListener::TcpListener(System::SharedPtr\<IPEndPoint\>) constructor

새 인스턴스를 생성합니다.

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPEndPoint> localEP)
```

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| localEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | 리스너 소켓을 바인딩해야 하는 로컬 엔드포인트입니다. |

## TcpListener::TcpListener(System::SharedPtr\<IPAddress\>, int32_t) constructor

새 인스턴스를 생성합니다.

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPAddress> localaddr, int32_t port)
```

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| localaddr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | 로컬 IP 주소. |
| port | **int32_t** | 수신 대기할 포트 번호. |

## TcpListener::TcpListener(int32_t) constructor

새 인스턴스를 생성합니다.

```cpp
System::Net::Sockets::TcpListener::TcpListener(int32_t port)
```

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| port | **int32_t** | 수신 대기할 포트 번호. |

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IPEndPoint](../../../system.net/ipendpoint/)
* 클래스 [TcpListener](../)
* 클래스 [IPAddress](../../../system.net/ipaddress/)
* 네임스페이스 [System::Net::Sockets](../../)
* 라이브러리 [Aspose.Slides](../../../)