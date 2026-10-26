---
title: BeginGetRequestStream()
second_title: C++용 Aspose.Slides API 참조
description: 리소스에 데이터를 쓰기 위한 스트림을 얻기 위해 비동기 작업을 시작합니다.
type: docs
weight: 144
url: /ko/system.net/filewebrequest/begingetrequeststream/
---
## FileWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) 메서드

리소스에 데이터를 쓰기 위한 스트림을 얻기 위해 비동기 작업을 시작합니다.

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | 작업이 완료될 때 호출되는 콜백입니다. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 각 비동기 작업을 고유하게 식별하는 데 사용되는 사용자 제공 데이터입니다. |

### 반환 값

시작된 비동기 작업을 나타내는 [IAsyncResult](../../../system/iasyncresult/) 객체입니다.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* 클래스 [IAsyncResult](../../../system/iasyncresult/)
* 클래스 [Object](../../../system/object/)
* 클래스 [FileWebRequest](../)
* 네임스페이스 [System::Net](../../)
* Library [Aspose.Slides](../../../)