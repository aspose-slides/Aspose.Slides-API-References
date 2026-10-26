---
title: TrueForAll()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 배열의 모든 요소가 지정된 프레디케이트에 의해 정의된 조건을 만족하는지 확인합니다.
type: docs
weight: 677
url: /ko/system/array/trueforall/
---
## Array::TrueForAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) 메서드

지정된 배열의 모든 요소가 지정된 프레디케이트에 의해 정의된 조건을 만족하는지 확인합니다.

```cpp
static bool System::Array<T>::TrueForAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) 요소를 조건에 맞추어 일치시킵니다 |
| match | [System::Predicate](../../predicate/)\<T\> | 배열 요소를 일치시키는 조건을 정의하는 프레디케이트 |

## 반환값

모든 arr 배열 요소가 match 프레디케이트에 정의된 조건을 만족하면 true, 그렇지 않으면 false

## 참조

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* 클래스 [Array](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)