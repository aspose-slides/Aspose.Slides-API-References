---
title: LINQ_Average()
second_title: Aspose.Slides for C++ API 참조
description: 수치 값 시퀀스의 평균을 계산합니다.
type: docs
weight: 365
url: /ko/system.collections.generic/ienumerable/linq_average/
---
## IEnumerable::LINQ_Average() 메서드

수치 값 시퀀스의 평균을 계산합니다.

```cpp
Source System::Collections::Generic::IEnumerable<Source>::LINQ_Average()
```

### 반환값

시퀀스의 값들의 평균입니다.

## IEnumerable::LINQ_Average(const Func\<T, ResultType\>\&) 메서드

입력 시퀀스의 각 요소에 변환 함수를 호출하여 얻은 값 시퀀스의 평균을 계산합니다.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<T, ResultType> &selector)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| ResultType | selector가 반환하는 값의 타입입니다. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | 각 요소에 적용할 변환 함수입니다. |

### 반환값

투영된 값들의 평균입니다.

## IEnumerable::LINQ_Average(const Func\<Source, ResultType\>\&) 메서드




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<Source, ResultType> &selector)
```

## 연관 보기

* 클래스 [IEnumerable](../)
* 클래스 [Func](../../../system/func/)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)