---
title: LINQ_All()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 시퀀스의 모든 요소가 조건을 만족하는지 확인합니다.
type: docs
weight: 144
url: /ko/system.collections.generic/ienumerable/linq_all/
---
## IEnumerable::LINQ_All(std::function\<bool(T)>) 메서드

시퀀스의 모든 요소가 조건을 만족하는지 확인합니다.

```cpp
bool System::Collections::Generic::IEnumerable<T>::LINQ_All(std::function<bool(T)> predicate)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | 각 요소가 조건을 만족하는지 테스트하는 함수. |

### 반환 값

소스 시퀀스의 모든 요소가 지정된 predicate 테스트를 통과하거나 시퀀스가 비어 있는 경우 true를 반환하고, 그렇지 않으면 false를 반환합니다.

## 참조

* 클래스 [IEnumerable](../)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)