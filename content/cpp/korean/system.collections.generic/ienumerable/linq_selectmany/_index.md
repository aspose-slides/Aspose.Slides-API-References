---
title: LINQ_SelectMany()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 시퀀스의 각 요소를 투사하고 결과 시퀀스를 하나의 시퀀스로 결합합니다.
type: docs
weight: 300
url: /ko/system.collections.generic/ienumerable/linq_selectmany/
---
## IEnumerable::LINQ_SelectMany(const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\&) 메서드


시퀀스의 각 요소를 투사하고 결과 시퀀스를 하나의 시퀀스로 결합합니다.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<T, SharedPtr<IEnumerable<ResultType>>> &selector)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| ResultType | **selector**에 의해 반환되는 값의 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, [SharedPtr](../../../system/sharedptr/)\<[IEnumerable](../)\<ResultType\>\>\>\& | 변환 함수. |

### 반환값

입력 시퀀스의 각 요소에 대한 일대다 투사 함수를 호출한 결과를 포함하는 [IEnumerable](../)입니다.

## IEnumerable::LINQ_SelectMany(const Func\<Source, SharedPtr\<IEnumerable\<Result\>\>\>\&) 메서드




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<Source, SharedPtr<IEnumerable<Result>>> &selector)
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IEnumerable](../)
* 클래스 [Func](../../../system/func/)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)