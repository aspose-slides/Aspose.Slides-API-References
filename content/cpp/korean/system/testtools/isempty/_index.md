---
title: IsEmpty()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 문자열이 비어 있는지 확인합니다.
type: docs
weight: 14
url: /ko/system/testtools/isempty/
---
## TestTools::IsEmpty(const System::String\&) method

문자열이 비어 있는지 확인합니다.

```cpp
static bool System::TestTools::IsEmpty(const System::String &str)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/)를(을) 비어 있는지 확인하기 위해. |

### 반환 값

문자열이 비어 있으면 true (null-length), 그렇지 않으면 false.

## TestTools::IsEmpty(const SharedPtr\<T\>\&) method

컬렉션이 비어 있는지 확인합니다.

```cpp
template<typename T> static bool System::TestTools::IsEmpty(const SharedPtr<T> &collection)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 컬렉션 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | 확인할 컬렉션. |

### 반환 값

컬렉션에 요소가 0개이면 true, 그렇지 않으면 false.

## 참고

* Typedef [SharedPtr](../../sharedptr/)
* 클래스 [String](../../string/)
* 구조체 [TestTools](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)