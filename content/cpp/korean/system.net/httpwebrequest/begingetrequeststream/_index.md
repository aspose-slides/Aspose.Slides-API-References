---
title: BeginGetRequestStream()
second_title: Aspose.Slides for C++ API 참조
description: 리소스에 데이터를 쓰기 위한 스트림을 가져오기 위한 비동기 작업을 시작합니다.
type: docs
weight: 469
url: /ko/system.net/httpwebrequest/begingetrequeststream/
---
## HttpWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) method


리소스에 데이터를 쓰기 위한 스트림을 가져오기 위한 비동기 작업을 시작합니다.

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | 작업이 완료될 때 호출되는 콜백입니다. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 각 비동기 작업을 고유하게 식별하기 위해 사용자가 제공한 데이터입니다. |

### 반환 값

[IAsyncResult](../../../system/iasyncresult/) 객체로, 시작된 비동기 작업을 나타냅니다.

## 또 보기

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 타입 정의 [AsyncCallback](../../../system/asynccallback/)
* 클래스 [IAsyncResult](../../../system/iasyncresult/)
* 클래스 [Object](../../../system/object/)
* 클래스 [HttpWebRequest](../)
* 네임스페이스 [System::Net](../../)
* 라이브러리 [Aspose.Slides](../../../)