---
title: Find()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 배열에서 지정된 조건자를 만족하는 첫 번째 요소를 검색합니다.
type: docs
weight: 651
url: /ko/system/array/find/
---
## Array::Find(System::ArrayPtr\<T\>, System::Predicate\<T\>) 메서드

지정된 배열에서 지정된 조건자를 만족하는 첫 번째 요소를 검색합니다.

```cpp
static T System::Array<T>::Find(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../)에서 요소를 검색하기 위한 |
| match | [System::Predicate](../../predicate/)\<T\> | 배열 요소와 일치시키기 위한 조건을 정의하는 조건자 |

### 반환 값

조건자에 의해 정의된 조건을 만족하는 배열의 첫 번째 요소의 복사본이며, 그렇지 않으면 유형 T의 기본값을 반환합니다.

## 참고

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)