---
title: Find()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 이름을 사용하여 컬렉션에서 NameValueHeaderValue-class 인스턴스를 찾습니다.
type: docs
weight: 144
url: /ko/system.net.http.headers/namevalueheadervalue/find/
---
## NameValueHeaderValue::Find(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, String) 메서드

지정된 이름을 사용하여 컬렉션에서 NameValueHeaderValue-class 인스턴스를 찾습니다.

```cpp
static System::SharedPtr<NameValueHeaderValue> System::Net::Http::Headers::NameValueHeaderValue::Find(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, String name)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | NameValueHeaderValue-class 인스턴스의 컬렉션. |
| name | [String](../../../system/string/) | 검색할 이름. |

### 반환 값

찾은 경우 NameValueHeaderValue-class 인스턴스를 반환하고, 그렇지 않으면 nullptr를 반환합니다.

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [NameValueHeaderValue](../)
* 클래스 [ObjectCollection](../../objectcollection/)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Net::Http::Headers](../../)
* 라이브러리 [Aspose.Slides](../../../)