---
title: EndGetRequestStream()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 스트림을 가져오는 비동기 작업이 완료될 때까지 기다립니다.
type: docs
weight: 313
url: /ko/system.net/webrequest/endgetrequeststream/
---
## WebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) 메서드

지정된 스트림을 가져오는 비동기 작업이 완료될 때까지 기다립니다.

```cpp
virtual System::SharedPtr<IO::Stream> System::Net::WebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | [IAsyncResult](../../../system/iasyncresult/) 객체는 스트림을 가져오는 비동기 작업을 나타냅니다. |

### 반환 값

리소스에 데이터를 쓰기 위한 스트림.

## 관련 항목

* typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Stream](../../../system.io/stream/)
* 클래스 [IAsyncResult](../../../system/iasyncresult/)
* 클래스 [WebRequest](../)
* 네임스페이스 [System::Net](../../)
* 라이브러리 [Aspose.Slides](../../../)