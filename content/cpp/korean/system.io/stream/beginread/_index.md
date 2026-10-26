---
title: BeginRead()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 비동기 읽기 작업을 시작합니다.
type: docs
weight: 157
url: /ko/system.io/stream/beginread/
---
## Stream::BeginRead(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) method

비동기 읽기 작업을 시작합니다.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginRead(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 읽기 버퍼 |
| offset | int | 읽은 데이터를 쓰기 시작할 위치를 나타내는 **buffer**의 0부터 시작하는 오프셋 |
| count | int | 읽을 바이트 수 |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | 작업이 완료될 때 호출되는 콜백 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 각 비동기 읽기 작업을 고유하게 식별하는 데 사용되는 사용자 제공 데이터 |

### 반환값

시작된 비동기 읽기 작업을 나타내는 [IAsyncResult](../../../system/iasyncresult/) 객체

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 타입정의 [AsyncCallback](../../../system/asynccallback/)
* 클래스 [IAsyncResult](../../../system/iasyncresult/)
* 클래스 [Object](../../../system/object/)
* 클래스 [Stream](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)