---
title: BeginConnect()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 비동기 연결 작업을 시작합니다.
type: docs
weight: 573
url: /ko/system.net.sockets/socket/beginconnect/
---
## Socket::BeginConnect(System::SharedPtr\<EndPoint\>, AsyncCallback, System::SharedPtr\<Object\>) 메서드

비동기 연결 작업을 시작합니다.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<EndPoint> remoteEP, AsyncCallback callback, System::SharedPtr<Object> state)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 원격 엔드포인트입니다. |
| callback | [AsyncCallback](../../../system/asynccallback/) | 작업이 완료되면 호출되는 콜백입니다. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 각 비동기 연결 작업을 고유하게 식별하는 데 사용되는 사용자 제공 데이터. |

### 반환값

시작된 비동기 연결 작업을 나타내는 [IAsyncResult](../../../system/iasyncresult/) 객체입니다.

## Socket::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) 메서드

비동기 연결 작업을 시작합니다.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| host | [String](../../../system/string/) | 원격 호스트 이름입니다. |
| port | **int32_t** | 원격 호스트의 포트 번호입니다. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 작업이 완료되면 호출되는 콜백입니다. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 각 비동기 연결 작업을 고유하게 식별하는 데 사용되는 사용자 제공 데이터. |

### 반환값

시작된 비동기 연결 작업을 나타내는 [IAsyncResult](../../../system/iasyncresult/) 객체입니다.

## Socket::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) 메서드

비동기 연결 작업을 시작합니다.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | 원격 호스트 IP 주소입니다. |
| port | **int32_t** | 원격 호스트의 포트 번호입니다. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 작업이 완료되면 호출되는 콜백입니다. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 각 비동기 연결 작업을 고유하게 식별하는 데 사용되는 사용자 제공 데이터. |

### 반환값

시작된 비동기 연결 작업을 나타내는 [IAsyncResult](../../../system/iasyncresult/) 객체입니다.

## Socket::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) 메서드

비동기 연결 작업을 시작합니다.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | 원격 호스트의 IP 주소들입니다. |
| port | **int32_t** | 원격 호스트의 포트 번호입니다. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 작업이 완료되면 호출되는 콜백입니다. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 각 비동기 연결 작업을 고유하게 식별하는 데 사용되는 사용자 제공 데이터. |

### 반환값

시작된 비동기 연결 작업을 나타내는 [IAsyncResult](../../../system/iasyncresult/) 객체입니다.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Object](../../../system/object/)
* Class [Socket](../)
* Class [String](../../../system/string/)
* Class [IPAddress](../../../system.net/ipaddress/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)