---
title: BeginRead()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 비동기 읽기 작업을 시작합니다.
type: docs
weight: 417
url: /ko/system.net.security/sslstream/beginread/
---
## SslStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) 메서드

비동기 읽기 작업을 시작합니다.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 데이터를 읽어올 바이트 배열. |
| offset | **int32_t** | 지정된 배열에서 바이트 단위의 오프셋. |
| count | **int32_t** | 읽을 바이트 수. |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | 작업이 완료될 때 호출되는 콜백. |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 각 비동기 읽기 작업을 고유하게 식별하는 데 사용되는 사용자 제공 데이터. |

### 반환 값

시작된 비동기 읽기 작업을 나타내는 [IAsyncResult](../../../system/iasyncresult/) 객체.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* 클래스 [IAsyncResult](../../../system/iasyncresult/)
* 클래스 [Object](../../../system/object/)
* 클래스 [SslStream](../)
* 네임스페이스 [System::Net::Security](../../)
* 라이브러리 [Aspose.Slides](../../../)