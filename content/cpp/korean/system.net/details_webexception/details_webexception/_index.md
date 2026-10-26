---
title: Details_WebException()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 인스턴스를 생성합니다.
type: docs
weight: 40
url: /ko/system.net/details_webexception/details_webexception/
---
## Details_WebException::Details_WebException() 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Details_WebException::Details_WebException()
```

## Details_WebException::Details_WebException(String) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Details_WebException::Details_WebException(String message)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| message | [String](../../../system/string/) | 오류 설명. |

## Details_WebException::Details_WebException(String, Exception) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| message | [String](../../../system/string/) | 예외 메시지. |
| innerException | [Exception](../../../system/exception/) | 내부 예외. |

## Details_WebException::Details_WebException(String, WebExceptionStatus) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Details_WebException::Details_WebException(String message, WebExceptionStatus status)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| message | [String](../../../system/string/) | 예외 메시지. |
| status | [WebExceptionStatus](../../webexceptionstatus/) | 상태 코드. |

## Details_WebException::Details_WebException(String, Exception, WebExceptionStatus, System::SharedPtr\<WebResponse\>) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException, WebExceptionStatus status, System::SharedPtr<WebResponse> response)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| message | [String](../../../system/string/) | 예외 메시지. |
| innerException | [Exception](../../../system/exception/) | 내부 예외. |
| status | [WebExceptionStatus](../../webexceptionstatus/) | 상태 코드. |
| response | [System::SharedPtr](../../../system/sharedptr/)\<[WebResponse](../../webresponse/)\> | 현재 예외와 연관된 웹 응답. |

## 참조

* Enum [WebExceptionStatus](../../webexceptionstatus/)
* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Details_WebException](../)
* 클래스 [String](../../../system/string/)
* 클래스 [WebResponse](../../webresponse/)
* 네임스페이스 [System::Net](../../)
* 라이브러리 [Aspose.Slides](../../../)