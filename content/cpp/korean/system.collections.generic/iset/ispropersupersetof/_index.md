---
title: IsProperSupersetOf()
second_title: Aspose.Slides for C++ API 참조
description: 현재 집합이 다른 컨테이너의 엄격한 상위 집합인지 확인합니다.
type: docs
weight: 53
url: /ko/system.collections.generic/iset/ispropersupersetof/
---
## ISet::IsProperSupersetOf(IEnumerablePtr) method

현재 집합이 다른 컨테이너의 엄격한 상위 집합인지 확인합니다.

```cpp
virtual bool System::Collections::Generic::ISet<T>::IsProperSupersetOf(IEnumerablePtr other)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| other | [IEnumerablePtr](../ienumerableptr/) | 확인할 하위 집합입니다. |

### 반환 값

**other**의 모든 요소가 집합에 존재하고 집합이 **other**보다 더 많은 요소를 포함하면 true, 그렇지 않으면 false입니다.

## 참조

* typedef [IEnumerablePtr](../ienumerableptr/)
* 클래스 [ISet](../)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)