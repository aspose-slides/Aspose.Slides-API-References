---
title: BeginAcceptSocket()
second_title: Aspose.Slides for C++ API 참조
description: 비동기 수락 작업을 시작합니다.
type: docs
weight: 144
url: /ko/system.net.sockets/tcplistener/beginacceptsocket/
---
## TcpListener::BeginAcceptSocket(AsyncCallback, System::SharedPtr\<Object\>) 메서드

비동기 수락 작업을 시작합니다.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptSocket(AsyncCallback callback, System::SharedPtr<Object> state)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | 작업이 완료될 때 호출되는 콜백입니다. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 각 비동기 연결 작업을 고유하게 식별하는 데 사용되는 사용자 제공 데이터입니다. |

### 반환 값

시작된 비동기 수락 작업을 나타내는 [IAsyncResult](../../../system/iasyncresult/) 객체입니다.

## 또보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* 클래스 [IAsyncResult](../../../system/iasyncresult/)
* 클래스 [Object](../../../system/object/)
* 클래스 [TcpListener](../)
* 네임스페이스 [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)