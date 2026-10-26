---
title: GetCookieHeader()
second_title: Aspose.Slides for C++ API 참고 자료
description: 지정된 URI와 연결된 쿠키를 포함하는 HTTP 헤더를 반환합니다.
type: docs
weight: 170
url: /ko/system.net/cookiecontainer/getcookieheader/
---
## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>) 메서드

지정된 URI와 연결된 쿠키를 포함하는 HTTP 헤더를 반환합니다.

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 헤더 이름이 구성될 URI입니다. |

### 반환 값

지정된 URI와 연결된 쿠키를 포함하는 HTTP 헤더를 반환합니다.

## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>, String\&) 메서드

지정된 URI와 연결된 쿠키를 포함하는 HTTP 헤더를 반환합니다.

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri, String &optCookie2)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 헤더 이름이 구성될 URI입니다. |
| optCookie2 | [String](../../../system/string/)\& | 최대 지원 버전의 쿠키가 할당될 출력 매개변수입니다. |

### 반환 값

지정된 URI와 연결된 쿠키를 포함하는 HTTP 헤더를 반환합니다.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [Uri](../../../system/uri/)
* 클래스 [CookieContainer](../)
* 네임스페이스 [System::Net](../../)
* Library [Aspose.Slides](../../../)