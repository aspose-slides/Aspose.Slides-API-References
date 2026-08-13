---
title: FindIndex()
second_title: Aspose.Slides for C++ API 참조
description: 특정 술어를 만족하는 요소를 찾습니다.
type: docs
weight: 404
url: /ko/system.collections.generic/list/findindex/
---
## List::FindIndex(System::Predicate\<T\>) 메서드

특정 술어를 만족하는 요소를 찾습니다.

```cpp
int System::Collections::Generic::List<T>::FindIndex(System::Predicate<T> match)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| match | [System::Predicate](../../../system/predicate/)\<T\> | 요소를 확인하기 위한 술어. |

### 반환값

[Index](../../../system/index/) 일치하는 요소의 인덱스 또는 찾지 못했을 경우 -1.

## List::FindIndex(int, System::Predicate\<T\>) 메서드

특정 술어를 만족하는 요소를 찾습니다.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, System::Predicate<T> match)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/)에서 검색을 시작합니다. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | 요소를 확인하기 위한 술어. |

### 반환값

[Index](../../../system/index/) 일치하는 요소의 인덱스 또는 찾지 못했을 경우 -1.

## List::FindIndex(int, int, System::Predicate\<T\>) 메서드

특정 술어를 만족하는 요소를 찾습니다.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, int count, System::Predicate<T> match)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/)에서 검색을 시작합니다. |
| count | int | 검색할 요소 수. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | 요소를 확인하기 위한 술어. |

### 반환값

[Index](../../../system/index/) 일치하는 요소의 인덱스 또는 찾지 못했을 경우 -1.

## 참조

* 타입정의 [Predicate](../../../system/predicate/)
* 클래스 [List](../)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)