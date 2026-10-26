---
title: LINQ_Max()
second_title: Aspose.Slides for C++ API 참조
description: 제네릭 시퀀스의 각 요소에 변환 함수를 적용하고, 결과값 중 최대값을 반환합니다.
type: docs
weight: 352
url: /ko/system.collections.generic/ienumerable/linq_max/
---
## IEnumerable::LINQ_Max(const Func\<T, ResultType\>\&) 메서드


제네릭 시퀀스의 각 요소에 변환 함수를 적용하고, 결과값 중 최대값을 반환합니다.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<T, ResultType> &selector)
```


### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| ResultType | selector에 의해 반환된 값의 형식. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | 각 요소에 적용할 변환 함수. |

### 반환 값

시퀀스에서의 최대값.

## IEnumerable::LINQ_Max(const Func\<Source, ResultType\>\&) 메서드




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<Source, ResultType> &selector)
```

## 참조

* 클래스 [Func](../../../system/func/)
* 클래스 [IEnumerable](../)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)