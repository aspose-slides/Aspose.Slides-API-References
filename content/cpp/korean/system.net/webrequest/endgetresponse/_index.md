---
title: EndGetResponse()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 리소스에 대한 비동기 요청이 완료될 때까지 대기합니다.
type: docs
weight: 287
url: /ko/system.net/webrequest/endgetresponse/
---
## WebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) 메서드

리소스에 대한 지정된 비동기 요청이 완료될 때까지 대기합니다.

```cpp
virtual System::SharedPtr<WebResponse> System::Net::WebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 리소스에 대한 비동기 요청을 나타내는 [IAsyncResult](../../../system/iasyncresult/) 객체. |

### 반환 값

웹 응답.

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [WebResponse](../../webresponse/)
* 클래스 [IAsyncResult](../../../system/iasyncresult/)
* 클래스 [WebRequest](../)
* 네임스페이스 [System::Net](../../)
* 라이브러리 [Aspose.Slides](../../../)