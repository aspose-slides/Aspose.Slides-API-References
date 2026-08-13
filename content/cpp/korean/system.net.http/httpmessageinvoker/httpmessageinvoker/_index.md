---
title: HttpMessageInvoker()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 인스턴스를 생성합니다.
type: docs
weight: 1
url: /ko/system.net.http/httpmessageinvoker/httpmessageinvoker/
---
## HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr\<HttpMessageHandler\>) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Http::HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr<HttpMessageHandler> handler)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | 요청을 전송하는 데 사용되는 HTTP 핸들러입니다. |

## HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr\<HttpMessageHandler\>, bool) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Http::HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr<HttpMessageHandler> handler, bool disposeHandler)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | 요청을 전송하는 데 사용되는 HTTP 핸들러입니다. |
| disposeHandler | **bool** | 이 인스턴스가 폐기될 때 핸들러를 폐기해야 하는지를 나타내는 값입니다. |

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [HttpMessageHandler](../../httpmessagehandler/)
* 클래스 [HttpMessageInvoker](../)
* 네임스페이스 [System::Net::Http](../../)
* 라이브러리 [Aspose.Slides](../../../)