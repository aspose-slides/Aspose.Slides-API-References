---
title: IsProperSubsetOf()
second_title: Aspose.Slides C++용 API 레퍼런스
description: 현재 집합이 다른 컨테이너의 엄격한 부분집합인지 확인합니다.
type: docs
weight: 40
url: /ko/system.collections.generic/iset/ispropersubsetof/
---
## ISet::IsProperSubsetOf(IEnumerablePtr) 메서드

현재 집합이 다른 컨테이너의 엄격한 부분집합인지 확인합니다.

```cpp
virtual bool System::Collections::Generic::ISet<T>::IsProperSubsetOf(IEnumerablePtr other)=0
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | [IEnumerablePtr](../ienumerableptr/) | 확인할 상위 집합. |

### 반환값

현재 집합의 모든 요소가 **other**에 존재하고 **other**가 현재 집합보다 더 많은 요소를 가지고 있으면 true, 그렇지 않으면 false.

## 참조

* 타입 정의 [IEnumerablePtr](../ienumerableptr/)
* 클래스 [ISet](../)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)