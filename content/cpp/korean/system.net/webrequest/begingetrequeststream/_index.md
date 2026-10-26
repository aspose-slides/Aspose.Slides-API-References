---
title: BeginGetRequestStream()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 리소스에 데이터를 쓰기 위한 스트림을 가져오는 비동기 작업을 시작합니다.
type: docs
weight: 300
url: /ko/system.net/webrequest/begingetrequeststream/
---
## WebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) 메서드

리소스에 데이터를 쓰기 위한 스트림을 가져오는 비동기 작업을 시작합니다.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | 작업이 완료될 때 호출되는 callback. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 각 비동기 작업을 고유하게 식별하기 위해 사용자가 제공한 데이터. |

### 반환 값

시작된 비동기 작업을 나타내는 [IAsyncResult](../../../system/iasyncresult/) 객체.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* 클래스 [IAsyncResult](../../../system/iasyncresult/)
* 클래스 [Object](../../../system/object/)
* 클래스 [WebRequest](../)
* 네임스페이스 [System::Net](../../)
* 라이브러리 [Aspose.Slides](../../../)