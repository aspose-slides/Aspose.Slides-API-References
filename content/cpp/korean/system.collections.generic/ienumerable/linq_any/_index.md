---
title: LINQ_Any()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 시퀀스에 요소가 하나라도 포함되어 있는지 확인합니다.
type: docs
weight: 157
url: /ko/system.collections.generic/ienumerable/linq_any/
---
## IEnumerable::LINQ_Any() 메서드

시퀀스에 요소가 하나라도 포함되어 있는지 확인합니다.

```cpp
bool System::Collections::Generic::IEnumerable<T>::LINQ_Any()
```

### 반환 값

소스 시퀀스에 요소가 하나라도 포함되어 있으면 true, 그렇지 않으면 false.

## IEnumerable::LINQ_Any(std::function\<bool(T)>) 메서드

시퀀스의 요소가 존재하거나 조건을 만족하는지 확인합니다.

```cpp
bool System::Collections::Generic::IEnumerable<T>::LINQ_Any(std::function<bool(T)> predicate)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | 각 요소가 조건을 만족하는지 테스트하는 함수. |

### 반환 값

소스 시퀀스에 요소가 하나라도 포함되어 있으면 true, 그렇지 않으면 false.

## 또 보기

* 클래스 [IEnumerable](../)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)