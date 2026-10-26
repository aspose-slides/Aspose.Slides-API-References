---
title: TryGetFirst()
second_title: Aspose.Slides C++용 API 레퍼런스
description: 컬렉션의 첫 번째 요소를 가져오려고 시도합니다.
type: docs
weight: 248
url: /ko/system.collections.generic.details/trygetfirst/
---
## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, bool\&) 함수

컬렉션에서 첫 번째 요소를 가져오려고 시도합니다.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, bool &found)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 컬렉션 요소의 타입입니다. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | 요소를 가져올 컬렉션입니다. |
| found | **bool**\& | 출력 매개변수입니다. 컬렉션에 요소가 포함되어 있으면 true를 반환합니다. 그렇지 않으면 false가 반환됩니다. |

### 반환 값

첫 번째 컬렉션 요소를 반환합니다. 컬렉션이 비어 있는 경우 해당 타입의 기본값이 반환됩니다.

## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, const Func\<T, bool\>\&, bool\&) 함수

조건 함수에 만족하는 컬렉션에서 첫 번째 요소를 가져오려고 시도합니다.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, const Func<T, bool> &predicate, bool &found)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 컬렉션 요소의 타입입니다. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | 요소를 가져올 컬렉션입니다. |
| predicate | const [Func](../../system/func/)\<T, **bool**\>\& | 조건 함수입니다. |
| found | **bool**\& | 출력 매개변수입니다. 컬렉션에 요소가 포함되어 있으면 true를 반환합니다. 그렇지 않으면 false가 반환됩니다. |

### 반환 값

첫 번째 컬렉션 요소를 반환합니다. 지정된 조건 함수를 만족하는 요소가 없을 경우 해당 타입의 기본값이 반환됩니다.

## 관련 항목

* 클래스 [IEnumerable](../../system.collections.generic/ienumerable/)
* 클래스 [Func](../../system/func/)
* 네임스페이스 [System::Collections::Generic::Details](../)
* 라이브러리 [Aspose.Slides](../../)