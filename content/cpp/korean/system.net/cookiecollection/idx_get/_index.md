---
title: idx_get()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 인덱스에 있는 쿠키 컬렉션에서 쿠키를 반환합니다.
type: docs
weight: 40
url: /ko/system.net/cookiecollection/idx_get/
---
## CookieCollection::idx_get(int32_t) 메서드

지정된 인덱스에 있는 쿠키 컬렉션에서 쿠키를 반환합니다.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(int32_t index)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 반환해야 하는 쿠키의 인덱스입니다. |

### 반환값

지정된 인덱스에 있는 쿠키.

## CookieCollection::idx_get(String) 메서드

지정된 이름으로 쿠키 컬렉션에서 쿠키를 반환합니다.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(String name)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 반환해야 하는 쿠키의 이름입니다. |

### 반환값

지정된 이름으로 쿠키 컬렉션에서 찾은 경우 쿠키를 반환하고, 찾지 못하면 nullptr을 반환합니다.

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Cookie](../../cookie/)
* 클래스 [CookieCollection](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Net](../../)
* 라이브러리 [Aspose.Slides](../../../)