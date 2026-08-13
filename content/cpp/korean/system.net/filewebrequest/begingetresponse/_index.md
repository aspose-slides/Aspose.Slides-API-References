---
title: BeginGetResponse()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 리소스에 대한 비동기 요청을 시작합니다.
type: docs
weight: 170
url: /ko/system.net/filewebrequest/begingetresponse/
---
## FileWebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) 메서드


리소스에 대한 비동기 요청을 시작합니다.

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | 작업이 완료될 때 호출되는 콜백입니다. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 각 비동기 작업을 고유하게 식별하는 데 사용되는 사용자 제공 데이터입니다. |

### 반환값

시작된 비동기 작업을 나타내는 [IAsyncResult](../../../system/iasyncresult/) 객체입니다.

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 타입정의 [AsyncCallback](../../../system/asynccallback/)
* 클래스 [IAsyncResult](../../../system/iasyncresult/)
* 클래스 [Object](../../../system/object/)
* 클래스 [FileWebRequest](../)
* 네임스페이스 [System::Net](../../)
* 라이브러리 [Aspose.Slides](../../../)