---
title: TryGetLast()
second_title: Aspose.Slides for C++ API 참조
description: 컬렉션의 마지막 요소를 가져오려고 시도합니다.
type: docs
weight: 261
url: /ko/system.collections.generic.details/trygetlast/
---
## System::Collections::Generic::Details::TryGetLast(IEnumerable\<T\>\&, bool\&) 함수

컬렉션의 마지막 요소를 가져오려고 시도합니다.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetLast(IEnumerable<T> &enumerable, bool &found)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 컬렉션 요소의 유형입니다. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | 요소를 가져올 컬렉션입니다. |
| found | **bool**\& | 출력 매개변수입니다. 컬렉션에 요소가 있으면 true를 반환하고, 없으면 false를 반환합니다. |

### 반환값

컬렉션의 마지막 요소를 반환합니다. 컬렉션이 비어 있으면 타입의 기본값을 반환합니다.

## 참고

* 클래스 [IEnumerable](../../system.collections.generic/ienumerable/)
* 네임스페이스 [System::Collections::Generic::Details](../)
* 라이브러리 [Aspose.Slides](../../)