---
title: InternalAdd()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 쿠키를 컬렉션에 추가합니다.
type: docs
weight: 118
url: /ko/system.net/cookiecollection/internaladd/
---
## CookieCollection::InternalAdd(System::SharedPtr\<Cookie\>, bool) 메서드


지정된 쿠키를 컬렉션에 추가합니다.

```cpp
int32_t System::Net::CookieCollection::InternalAdd(System::SharedPtr<Cookie> cookie, bool isStrict)
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | 추가할 쿠키입니다. |
| isStrict | **bool** | 지정된 쿠키가 이전 쿠키를 교체해야 하는 경우 true, 그렇지 않으면 false. |

### 반환값

지정된 쿠키가 이전 쿠키를 교체한 경우 0, 그렇지 않으면 1.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Cookie](../../cookie/)
* 클래스 [CookieCollection](../)
* 네임스페이스 [System::Net](../../)
* 라이브러리 [Aspose.Slides](../../../)