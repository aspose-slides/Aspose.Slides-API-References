---
title: EndGetRequestStream()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 스트림 가져오기 비동기 작업이 완료될 때까지 기다립니다.
type: docs
weight: 482
url: /ko/system.net/httpwebrequest/endgetrequeststream/
---
## HttpWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) 메서드


지정된 비동기 스트림 가져오기 작업이 완료될 때까지 기다립니다.

```cpp
System::SharedPtr<IO::Stream> System::Net::HttpWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | [IAsyncResult](../../../system/iasyncresult/) 객체는 스트림을 가져오는 비동기 작업을 나타냅니다. |

## 반환 값

리소스에 데이터를 기록하기 위한 스트림.

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Stream](../../../system.io/stream/)
* 클래스 [IAsyncResult](../../../system/iasyncresult/)
* 클래스 [HttpWebRequest](../)
* 네임스페이스 [System::Net](../../)
* 라이브러리 [Aspose.Slides](../../../)