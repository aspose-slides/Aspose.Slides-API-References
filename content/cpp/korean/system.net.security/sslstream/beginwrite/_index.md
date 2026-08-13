---
title: BeginWrite()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 비동기 쓰기 작업을 시작합니다.
type: docs
weight: 443
url: /ko/system.net.security/sslstream/beginwrite/
---
## SslStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) 메서드

비동기 쓰기 작업을 시작합니다.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 데이터를 기록할 바이트 배열입니다. |
| offset | **int32_t** | 지정된 배열에서 바이트 단위의 오프셋입니다. |
| count | **int32_t** | 작성할 바이트 수입니다. |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | 작업이 완료될 때 호출되는 콜백입니다. |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 각 비동기 쓰기 작업을 고유하게 식별하는 데 사용되는 사용자 제공 데이터입니다. |

### 반환값

[IAsyncResult](../../../system/iasyncresult/) 개체는 시작된 비동기 쓰기 작업을 나타냅니다.

## 또 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* 클래스 [IAsyncResult](../../../system/iasyncresult/)
* 클래스 [Object](../../../system/object/)
* 클래스 [SslStream](../)
* 네임스페이스 [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)