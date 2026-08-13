---
title: Exists()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 Array 객체에 지정된 프레디케이트의 요구 사항을 만족하는 요소가 포함되어 있는지 확인합니다.
type: docs
weight: 781
url: /ko/system/array/exists/
---
## Array::Exists(ArrayPtr\<T\>, std::function\<bool(T)>) 메서드

지정된 [Array](../) 객체에 지정된 프레디케이트의 요구 사항을 만족하는 요소가 포함되어 있는지 결정합니다.

```cpp
static bool System::Array<T>::Exists(ArrayPtr<T> arr, std::function<bool(T)> match)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | 요소를 찾는 배열 |
| match | std::function\<**bool**(T)> | 요구 사항을 정의하고 요소가 이를 만족하는지 확인하는 함수 객체 |

### 반환값

**arr**에 **match**에 의해 정의된 요구 사항을 만족하는 요소가 포함되어 있으면 true

## 참고

* Typedef [ArrayPtr](../../arrayptr/)
* 클래스 [Array](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)