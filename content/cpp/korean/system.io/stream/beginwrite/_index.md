---
title: BeginWrite()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 비동기 쓰기 작업을 시작합니다.
type: docs
weight: 170
url: /ko/system.io/stream/beginwrite/
---
## Stream::BeginWrite(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) 메서드


비동기 쓰기 작업을 시작합니다.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 작성할 데이터를 포함하는 버퍼 |
| offset | int | **buffer** 안의 0부터 시작하는 오프셋으로, 데이터 쓰기가 시작되는 위치를 나타냅니다 |
| count | int | 쓰기 위한 바이트 수 |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | 작업이 완료될 때 호출되는 콜백 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 각 비동기 쓰기 작업을 고유하게 식별하는 데 사용되는 사용자 제공 데이터 |

### 반환 값

시작된 비동기 쓰기 작업을 나타내는 [IAsyncResult](../../../system/iasyncresult/) 객체

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* 클래스 [IAsyncResult](../../../system/iasyncresult/)
* 클래스 [Object](../../../system/object/)
* 클래스 [Stream](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)