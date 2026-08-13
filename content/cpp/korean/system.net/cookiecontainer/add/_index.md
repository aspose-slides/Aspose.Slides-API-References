---
title: Add()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 컬렉션에 쿠키를 추가합니다.
type: docs
weight: 105
url: /ko/system.net/cookiecontainer/add/
---
## CookieContainer::Add(System::SharedPtr\<Cookie\>) 메서드

컬렉션에 쿠키를 추가합니다.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | 추가할 쿠키입니다. |

## CookieContainer::Add(System::SharedPtr\<Cookie\>, bool) 메서드

컬렉션에 쿠키를 추가합니다.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie, bool throwOnError)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | 추가할 쿠키입니다. |
| throwOnError | **bool** | 오류가 발생했을 때 예외가 발생하는지 여부를 나타내는 값입니다. |

## CookieContainer::Add(System::SharedPtr\<CookieCollection\>) 메서드

지정된 컬렉션에서 현재 컬렉션으로 쿠키를 복사합니다.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<CookieCollection> cookies)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | 쿠키를 복사할 컬렉션입니다. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<Cookie\>) 메서드

지정된 URI에 대한 쿠키를 추가합니다.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<Cookie> cookie)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 쿠키의 URI입니다. |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | 추가할 쿠키입니다. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<CookieCollection\>) 메서드

지정된 URI에 대해 지정된 컬렉션에서 현재 컬렉션으로 쿠키를 복사합니다.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<CookieCollection> cookies)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 쿠키의 URI입니다. |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | 쿠키를 복사해야 하는 쿠키 컬렉션입니다. |

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Cookie](../../cookie/)
* 클래스 [CookieContainer](../)
* 클래스 [CookieCollection](../../cookiecollection/)
* 클래스 [Uri](../../../system/uri/)
* 네임스페이스 [System::Net](../../)
* Library [Aspose.Slides](../../../)