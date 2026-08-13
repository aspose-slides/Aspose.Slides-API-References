---
title: LINQ_Min()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 제네릭 시퀀스의 각 요소에 변환 함수를 호출하고 최소 결과 값을 반환합니다.
type: docs
weight: 339
url: /ko/system.collections.generic/ienumerable/linq_min/
---
## IEnumerable::LINQ_Min(const Func\<T, ResultType\>\&) 메서드

제네릭 시퀀스의 각 요소에 변환 함수를 호출하고 최소 결과 값을 반환합니다.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<T, ResultType> &selector)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| ResultType | 선택기에서 반환되는 값의 형식. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | 각 요소에 적용할 변환 함수. |

### 반환값

시퀀스에서 최소값.

## IEnumerable::LINQ_Min(const Func\<Source, ResultType\>\&) 메서드

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<Source, ResultType> &selector)
```

## 참조

* 클래스 [Func](../../../system/func/)
* 클래스 [IEnumerable](../)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)