---
title: BeginRead()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 비동기 읽기 작업을 시작합니다.
type: docs
weight: 248
url: /ko/system.net.sockets/networkstream/beginread/
---
## NetworkStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) 메서드

비동기 읽기 작업을 시작합니다.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 읽은 바이트가 기록될 바이트 배열입니다. |
| offset | **int32_t** | 지정된 배열에서 바이트 단위의 오프셋입니다. |
| size | **int32_t** | 읽을 바이트 수입니다. |
| callback | [AsyncCallback](../../../system/asynccallback/) | 작업이 완료될 때 호출되는 콜백입니다. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 각 비동기 읽기 작업을 고유하게 식별하는 데 사용되는 사용자 제공 데이터입니다. |

### 반환값

시작된 비동기 읽기 작업을 나타내는 [IAsyncResult](../../../system/iasyncresult/) 객체입니다.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)