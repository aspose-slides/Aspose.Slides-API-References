---
title: BeginWrite()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 비동기 쓰기 작업을 시작합니다.
type: docs
weight: 274
url: /ko/system.net.sockets/networkstream/beginwrite/
---
## NetworkStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) 메서드

비동기 쓰기 작업을 시작합니다.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 작성할 데이터를 포함하는 버퍼. |
| offset | **int32_t** | 지정된 배열에서 바이트 단위의 오프셋. |
| size | **int32_t** | 작성할 바이트 수. |
| callback | [AsyncCallback](../../../system/asynccallback/) | 작업이 완료될 때 호출되는 콜백. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 각 비동기 쓰기 작업을 고유하게 식별하는 데 사용되는 사용자 제공 데이터. |

### 반환값

시작된 비동기 쓰기 작업을 나타내는 [IAsyncResult](../../../system/iasyncresult/) 객체.

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 타입정의 [AsyncCallback](../../../system/asynccallback/)
* 클래스 [IAsyncResult](../../../system/iasyncresult/)
* 클래스 [Object](../../../system/object/)
* 클래스 [NetworkStream](../)
* 네임스페이스 [System::Net::Sockets](../../)
* 라이브러리 [Aspose.Slides](../../../)