---
title: Connect()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 원격 엔드포인트에 연결을 설정합니다.
type: docs
weight: 560
url: /ko/system.net.sockets/socket/connect/
---
## Socket::Connect(System::SharedPtr\<EndPoint\>) 메서드


지정된 원격 엔드포인트에 연결을 설정합니다.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<EndPoint> remoteEP)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 원격 엔드포인트. |

## Socket::Connect(System::SharedPtr\<IPAddress\>, int32_t) 메서드


지정된 원격 엔드포인트에 연결을 설정합니다.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | 원격 호스트 IP 주소. |
| port | **int32_t** | 원격 호스트의 포트 번호. |

## Socket::Connect(String, int32_t) 메서드


지정된 원격 엔드포인트에 연결을 설정합니다.

```cpp
void System::Net::Sockets::Socket::Connect(String host, int32_t port)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| host | [String](../../../system/string/) | 원격 호스트 이름. |
| port | **int32_t** | 원격 호스트의 포트 번호. |

## Socket::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) 메서드


지정된 원격 엔드포인트에 연결을 설정합니다.

```cpp
void System::Net::Sockets::Socket::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | 원격 호스트의 IP 주소들. |
| port | **int32_t** | 원격 호스트의 포트 번호. |

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [EndPoint](../../../system.net/endpoint/)
* 클래스 [Socket](../)
* 클래스 [IPAddress](../../../system.net/ipaddress/)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Net::Sockets](../../)
* 라이브러리 [Aspose.Slides](../../../)