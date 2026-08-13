---
title: FindAll()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 프레디케이트에 의해 정의된 조건과 일치하는 모든 요소를 검색합니다.
type: docs
weight: 664
url: /ko/system/array/findall/
---
## Array::FindAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) 메서드


지정된 프레디케이트에 의해 정의된 조건과 일치하는 모든 요소를 검색합니다.

```cpp
static System::ArrayPtr<T> System::Array<T>::FindAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../)에서 검색할 요소 |
| match | [System::Predicate](../../predicate/)\<T\> | 배열 요소와 일치시키는 조건을 정의하는 프레디케이트 |

### 반환값

지정된 프레디케이트에 의해 정의된 조건과 일치하는 모든 요소를 포함하는 [Array](../)이며, 찾을 수 없는 경우 빈 [Array](../)입니다.

## 참고

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* 클래스 [Array](../)
* 네임스페이스 [System](../../)
* Library [Aspose.Slides](../../../)