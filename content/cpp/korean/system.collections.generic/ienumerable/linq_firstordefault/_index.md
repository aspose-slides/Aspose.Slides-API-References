---
title: LINQ_FirstOrDefault()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 시퀀스의 첫 번째 요소를 반환하며, 시퀀스가 비어 있는 경우 기본값을 반환합니다.
type: docs
weight: 66
url: /ko/system.collections.generic/ienumerable/linq_firstordefault/
---
## IEnumerable::LINQ_FirstOrDefault() 메서드

시퀀스의 첫 번째 요소를 반환하며, 시퀀스가 비어 있는 경우 기본값을 반환합니다.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault()
```

### 반환값

시퀀스가 비어 있는 경우 첫 번째 요소 또는 기본 생성된 값을 반환합니다.

## IEnumerable::LINQ_FirstOrDefault(std::function\<bool(T)>) 메서드

조건을 만족하는 시퀀스의 첫 번째 요소를 반환하며, 해당 요소가 없으면 기본값을 반환합니다.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault(std::function<bool(T)> predicate)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | 각 요소가 조건을 만족하는지 테스트하는 함수. |

### 반환값

source가 비어 있거나 predicate에 의해 지정된 테스트를 통과하는 요소가 없으면 default(T)를 반환합니다; 그렇지 않으면 predicate에 의해 지정된 테스트를 통과하는 source의 첫 번째 요소를 반환합니다.

## 참고

* 클래스 [IEnumerable](../)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)