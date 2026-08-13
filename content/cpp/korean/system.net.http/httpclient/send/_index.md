---
title: Send()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 HTTP 요청을 전송합니다.
type: docs
weight: 118
url: /ko/system.net.http/httpclient/send/
---
## HttpClient::Send(System::SharedPtr\<HttpRequestMessage\>, HttpCompletionOption) 메서드

지정된 HTTP 요청을 전송합니다.

```cpp
System::SharedPtr<HttpResponseMessage> System::Net::Http::HttpClient::Send(System::SharedPtr<HttpRequestMessage> request, HttpCompletionOption completionOption)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| request | [System::SharedPtr](../../../system/sharedptr/)\<[HttpRequestMessage](../../httprequestmessage/)\> | 전송해야 하는 HTTP 요청 |
| completionOption | [HttpCompletionOption](../../httpcompletionoption/) | 작업을 언제 완료할지 나타내는 값 |

## 참조

* 열거형 [HttpCompletionOption](../../httpcompletionoption/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [HttpResponseMessage](../../httpresponsemessage/)
* 클래스 [HttpRequestMessage](../../httprequestmessage/)
* 클래스 [HttpClient](../)
* 네임스페이스 [System::Net::Http](../../)
* 라이브러리 [Aspose.Slides](../../../)