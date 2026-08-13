---
title: FindIndex()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 배열에서 지정된 프레디케이트의 조건을 만족하는 첫 번째 요소를 검색합니다.
type: docs
weight: 638
url: /ko/system/array/findindex/
---
## Array::FindIndex(System::ArrayPtr\<T\>, System::Predicate\<T\>) 메서드


지정된 배열에서 지정된 프레디케이트의 조건을 만족하는 첫 번째 요소를 검색합니다.

```cpp
static int System::Array<T>::FindIndex(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../)에서 요소를 검색하기 위해 |
| match | [System::Predicate](../../predicate/)\<T\> | 배열 요소와 일치시키기 위한 조건을 정의하는 프레디케이트 |

### 반환 값

프레디케이트에 의해 정의된 조건을 만족하는 배열의 첫 번째 요소의 인덱스, 조건을 만족하지 않으면 -1

## 또 보기

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)