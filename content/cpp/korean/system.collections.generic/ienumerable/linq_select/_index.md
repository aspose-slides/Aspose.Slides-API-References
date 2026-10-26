---
title: LINQ_Select()
second_title: Aspose.Slides for C++ API 참조
description: 시퀀스의 요소를 변환합니다.
type: docs
weight: 248
url: /ko/system.collections.generic/ienumerable/linq_select/
---
## IEnumerable::LINQ_Select(const Func\<T, ResultType\>\&) 메서드

시퀀스의 요소를 변환합니다.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, ResultType> &selector)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| ResultType | **selector**가 반환하는 값의 유형입니다. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | 변환 함수입니다. |

### 반환값

[IEnumerable](../)는 selector 함수에 의해 반환된 요소를 포함합니다.

## IEnumerable::LINQ_Select(const Func\<T, int32_t, ResultType\>\&) 메서드

시퀀스의 각 요소를 인덱스를 포함하여 새 형태로 변환합니다.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, int32_t, ResultType> &selector)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| ResultType | **selector**가 반환하는 값의 유형입니다. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, **int32_t**, ResultType\>\& | 변환 함수입니다. |

### 반환값

[IEnumerable](../)는 selector 함수에 의해 반환된 요소를 포함합니다.

## IEnumerable::LINQ_Select(const Func\<Source, Result\>\&) 메서드




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, Result> &selector)
```

## IEnumerable::LINQ_Select(const Func\<Source, int32_t, Result\>\&) 메서드




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, int32_t, Result> &selector)
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)