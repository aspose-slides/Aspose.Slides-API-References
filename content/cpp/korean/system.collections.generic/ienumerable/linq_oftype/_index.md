---
title: LINQ_OfType()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 유형을 기준으로 시퀀스의 요소를 필터링합니다.
type: docs
weight: 235
url: /ko/system.collections.generic/ienumerable/linq_oftype/
---
## IEnumerable::LINQ_OfType() 메서드

Filters the elements of the sequence based on the specified type.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_OfType()
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| ResultType | The type to filter the elements of the sequence. |

### 반환값

[IEnumerable](../)는 ResultType의 시퀀스에 포함된 요소를 포함합니다.

## IEnumerable::LINQ_OfType() 메서드

```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_OfType()
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IEnumerable](../)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)