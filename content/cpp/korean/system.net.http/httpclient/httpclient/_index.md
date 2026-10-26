---
title: HttpClient()
second_title: Aspose.Slides for C++ API 참조
description: 새 인스턴스를 생성합니다.
type: docs
weight: 92
url: /ko/system.net.http/httpclient/httpclient/
---
## HttpClient::HttpClient() 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Http::HttpClient::HttpClient()
```

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | 요청을 보내는 데 사용되는 HTTP 핸들러입니다. |

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>, bool) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler, bool disposeHandler)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | 요청을 보내는 데 사용되는 HTTP 핸들러입니다. |
| disposeHandler | **bool** | 이 인스턴스가 해제될 때 핸들러를 해제해야 하는지 여부를 나타내는 값입니다. |

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [HttpClient](../)
* 클래스 [HttpMessageHandler](../../httpmessagehandler/)
* 네임스페이스 [System::Net::Http](../../)
* 라이브러리 [Aspose.Slides](../../../)