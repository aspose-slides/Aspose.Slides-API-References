---
title: BeginConnect()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 비동기 연결 작업을 시작합니다.
type: docs
weight: 261
url: /ko/system.net.sockets/tcpclient/beginconnect/
---
## TcpClient::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) 메서드

비동기 연결 작업을 시작합니다.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| host | [String](../../../system/string/) | 원격 호스트 이름입니다. |
| port | **int32_t** | 원격 호스트의 포트입니다. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 작업이 완료될 때 호출되는 콜백입니다. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 각 비동기 연결 작업을 고유하게 식별하기 위해 사용자가 제공한 데이터입니다. |

### 반환 값

시작된 비동기 연결 작업을 나타내는 [IAsyncResult](../../../system/iasyncresult/) 객체.

## TcpClient::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) 메서드

비동기 연결 작업을 시작합니다.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | 원격 호스트의 IP 주소입니다. |
| port | **int32_t** | 원격 호스트의 포트입니다. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 작업이 완료될 때 호출되는 콜백입니다. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 각 비동기 연결 작업을 고유하게 식별하기 위해 사용자가 제공한 데이터입니다. |

### 반환 값

시작된 비동기 연결 작업을 나타내는 [IAsyncResult](../../../system/iasyncresult/) 객체.

## TcpClient::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) 메서드

비동기 연결 작업을 시작합니다.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | 원격 호스트의 IP 주소들입니다. |
| port | **int32_t** | 원격 호스트의 포트입니다. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 작업이 완료될 때 호출되는 콜백입니다. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 각 비동기 연결 작업을 고유하게 식별하기 위해 사용자가 제공한 데이터입니다. |

### 반환 값

시작된 비동기 연결 작업을 나타내는 [IAsyncResult](../../../system/iasyncresult/) 객체.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [IAsyncResult](../../../system/iasyncresult/)
* 클래스 [String](../../../system/string/)
* 클래스 [Object](../../../system/object/)
* 클래스 [TcpClient](../)
* 클래스 [IPAddress](../../../system.net/ipaddress/)
* 네임스페이스 [System::Net::Sockets](../../)
* 라이브러리 [Aspose.Slides](../../../)