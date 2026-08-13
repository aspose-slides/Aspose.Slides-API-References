---
title: EndGetRequestStream()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 스트림을 가져오는 비동기 작업이 완료될 때까지 기다립니다.
type: docs
weight: 157
url: /ko/system.net/filewebrequest/endgetrequeststream/
---
## FileWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) 메서드

지정된 스트림 가져오기 비동기 작업이 완료될 때까지 대기합니다.

```cpp
System::SharedPtr<IO::Stream> System::Net::FileWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 스트림을 가져오는 비동기 작업을 나타내는 [IAsyncResult](../../../system/iasyncresult/) 객체. |

### 반환값

리소스에 데이터를 쓰기 위한 스트림.

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Stream](../../../system.io/stream/)
* 클래스 [IAsyncResult](../../../system/iasyncresult/)
* 클래스 [FileWebRequest](../)
* 네임스페이스 [System::Net](../../)
* 라이브러리 [Aspose.Slides](../../../)