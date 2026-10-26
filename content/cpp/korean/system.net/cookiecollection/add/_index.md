---
title: Add()
second_title: Aspose.Slides for C++ API 참조
description: 컬렉션에 쿠키를 추가합니다.
type: docs
weight: 53
url: /ko/system.net/cookiecollection/add/
---
## CookieCollection::Add(const System::SharedPtr\<Cookie\>\&) 메서드

컬렉션에 쿠키를 추가합니다.

```cpp
void System::Net::CookieCollection::Add(const System::SharedPtr<Cookie> &cookie) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cookie | const [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\>\& | 추가할 쿠키입니다. |

## CookieCollection::Add(System::SharedPtr\<CookieCollection\>) 메서드

지정된 컬렉션에서 현재 컬렉션으로 쿠키를 추가합니다.

```cpp
void System::Net::CookieCollection::Add(System::SharedPtr<CookieCollection> cookies)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../)\> | 현재 컬렉션으로 쿠키가 복사될 컬렉션입니다. |

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Cookie](../../cookie/)
* 클래스 [CookieCollection](../)
* 네임스페이스 [System::Net](../../)
* 라이브러리 [Aspose.Slides](../../../)