---
title: HttpRequestMessage()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 인스턴스를 생성합니다.
type: docs
weight: 131
url: /ko/system.net.http/httprequestmessage/httprequestmessage/
---
## HttpRequestMessage::HttpRequestMessage() 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Http::HttpRequestMessage::HttpRequestMessage()
```

## HttpRequestMessage::HttpRequestMessage(System::SharedPtr\<HttpMethod\>, System::SharedPtr\<Uri\>) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Http::HttpRequestMessage::HttpRequestMessage(System::SharedPtr<HttpMethod> method, System::SharedPtr<Uri> requestUri)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| method | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMethod](../../httpmethod/)\> | HTTP 메서드. |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 요청된 리소스의 URI. |

## HttpRequestMessage::HttpRequestMessage(System::SharedPtr\<HttpMethod\>, String) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Http::HttpRequestMessage::HttpRequestMessage(System::SharedPtr<HttpMethod> method, String requestUri)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| method | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMethod](../../httpmethod/)\> | HTTP 메서드. |
| requestUri | [String](../../../system/string/) | 요청된 리소스의 URI. |

## 관련 항목

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [HttpRequestMessage](../)
* 클래스 [HttpMethod](../../httpmethod/)
* 클래스 [Uri](../../../system/uri/)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Net::Http](../../)
* 라이브러리 [Aspose.Slides](../../../)