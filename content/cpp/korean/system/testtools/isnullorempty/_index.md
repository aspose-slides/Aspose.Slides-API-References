---
title: IsNullOrEmpty()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 컬렉션이 null이거나 비어 있는지 확인합니다.
type: docs
weight: 27
url: /ko/system/testtools/isnullarempty/
---
## TestTools::IsNullOrEmpty(const SharedPtr\<T\>\&) 메서드

컬렉션이 null이거나 비어 있는지 확인합니다.

```cpp
template<typename T> static bool System::TestTools::IsNullOrEmpty(const SharedPtr<T> &collection)
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

컬렉션이 null이거나 요소 개수가 0이면 True, 그렇지 않으면 false.

## TestTools::IsNullOrEmpty(const System::String\&) 메서드

문자열이 null이거나 비어 있는지 확인합니다.

```cpp
static bool System::TestTools::IsNullOrEmpty(const System::String &str)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/)를 확인합니다. |

### 반환 값

문자열이 null이거나 길이가 0이면 True, 그렇지 않으면 false.

## 참조

* 타입정의 [SharedPtr](../../sharedptr/)
* 클래스 [String](../../string/)
* 구조체 [TestTools](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)