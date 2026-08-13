---
title: BeginSend()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 비동기 전송 작업을 시작합니다.
type: docs
weight: 495
url: /ko/system.net.sockets/socket/beginsend/
---
## Socket::BeginSend(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) method

비동기 전송 작업을 시작합니다.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginSend(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 데이터를 읽어올 버퍼입니다. |
| offset | **int32_t** | 지정된 배열의 바이트 단위 오프셋입니다. |
| size | **int32_t** | ‘offset’ 매개변수부터 시작하는 지정된 배열의 바이트 수입니다. |
| socketFlags | [SocketFlags](../../socketflags/) | 전송 동작입니다. |
| callback | [AsyncCallback](../../../system/asynccallback/) | 작업이 완료될 때 호출되는 콜백입니다. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 각 비동기 전송 작업을 고유하게 식별하기 위해 사용자가 제공하는 데이터입니다. |

### Return Value

시작된 비동기 전송 작업을 나타내는 [IAsyncResult](../../../system/iasyncresult/) 객체입니다.

## See Also

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)