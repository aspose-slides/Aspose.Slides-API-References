---
title: AbstractEqual()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 알 수 없는 유형의 두 컬렉션을 비교합니다.
type: docs
weight: 14
url: /ko/system/testcompare/abstractequal/
---
## TestCompare::AbstractEqual(SCG::ICollection\<T\> *const, SCG::ICollection\<T\> *const) 메서드


알 수 없는 유형의 두 컬렉션을 비교합니다.

```cpp
template<typename T> static bool System::TestCompare::AbstractEqual(SCG::ICollection<T> *const collA, SCG::ICollection<T> *const collB)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 컬렉션 요소 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| collA | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | LHS 컬렉션. |
| collB | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | RHS 컬렉션. |

### 반환 값

컬렉션이 일치하면 true (예: 두 컬렉션이 모두 null인 경우) 또는 크기가 일치하고 요소가 일치하면 true, 그 외의 경우 false.

## 관련 항목

* 클래스 [ICollection](../../../system.collections.generic/icollection/)
* 구조체 [TestCompare](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)