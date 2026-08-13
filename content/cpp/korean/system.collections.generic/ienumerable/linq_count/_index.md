---
title: LINQ_Count()
second_title: Aspose.Slides for C++ API 참조
description: 시퀀스의 요소 수를 반환합니다 (직접 계산을 통해).
type: docs
weight: 118
url: /ko/system.collections.generic/ienumerable/linq_count/
---
## IEnumerable::LINQ_Count() 메서드

시퀀스의 요소 수를 반환합니다 (직접 계산을 통해).

```cpp
int System::Collections::Generic::IEnumerable<T>::LINQ_Count()
```

### 반환 값

시퀀스의 요소 수.

## IEnumerable::LINQ_Count(const Func\<T, bool\>\&) 메서드

지정된 조건을 만족하는 시퀀스의 요소 수를 반환합니다.

```cpp
int System::Collections::Generic::IEnumerable<T>::LINQ_Count(const Func<T, bool> &predicate)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| predicate | const [Func](../../../system/func/)\<T, **bool**\>\& | 각 요소가 조건을 만족하는지 테스트하는 함수. |

### 반환 값

지정된 조건을 만족하는 시퀀스의 요소 수.

## 참조

* 클래스 [IEnumerable](../)
* 클래스 [Func](../../../system/func/)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)