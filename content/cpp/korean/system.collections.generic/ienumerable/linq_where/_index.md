---
title: LINQ_Where()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 프레디케이트를 기반으로 시퀀스를 필터링합니다.
type: docs
weight: 170
url: /ko/system.collections.generic/ienumerable/linq_where/
---
## IEnumerable::LINQ_Where(std::function\<bool(T)>) 메서드

지정된 프레디케이트를 기반으로 시퀀스를 필터링합니다.

```cpp
SharedPtr<IEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_Where(std::function<bool(T)> predicate)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | 각 요소를 특정 조건에 대해 테스트하는 함수입니다. |

### 반환값

필터링된 요소를 포함하는 [IEnumerable](../)입니다.

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IEnumerable](../)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)