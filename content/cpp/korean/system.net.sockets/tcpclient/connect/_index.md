---
title: Connect()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 원격 호스트에 연결을 설정합니다.
type: docs
weight: 248
url: /ko/system.net.sockets/tcpclient/connect/
---
## TcpClient::Connect(String, int32_t) 메서드

지정된 원격 호스트에 연결을 설정합니다.

```cpp
void System::Net::Sockets::TcpClient::Connect(String hostname, int32_t port)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | 연결할 원격 호스트 이름. |
| port | **int32_t** | 연결할 원격 호스트의 포트. |

## TcpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) 메서드

지정된 원격 호스트에 연결을 설정합니다.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | 원격 호스트의 IP 주소. |
| port | **int32_t** | 연결할 원격 호스트의 포트. |

## TcpClient::Connect(System::SharedPtr\<IPEndPoint\>) 메서드

지정된 원격 호스트에 연결을 설정합니다.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPEndPoint> remoteEP)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | 연결할 원격 호스트. |

## TcpClient::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) 메서드

지정된 원격 호스트에 연결을 설정합니다.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> ipAddresses, int32_t port)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| ipAddresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | 원격 호스트의 IP 주소들. |
| port | **int32_t** | 연결할 원격 호스트의 포트. |

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [TcpClient](../)
* Class [IPAddress](../../../system.net/ipaddress/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)