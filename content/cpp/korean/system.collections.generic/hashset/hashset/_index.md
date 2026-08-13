---
title: HashSet()
second_title: Aspose.Slides for C++ API 레퍼런스
description: RTTI 정보.
type: docs
weight: 1
url: /ko/system.collections.generic/hashset/hashset/
---
## HashSet::HashSet() 생성자

RTTI 정보.

```cpp
System::Collections::Generic::HashSet<T>::HashSet()
```

## 비고

빈 세트를 생성합니다.

## HashSet::HashSet(int) 생성자

지정된 용량으로 빈 세트를 생성합니다.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(int capacity)
```

## HashSet::HashSet(const SharedPtr\<IEqualityComparer\<T\>\>\&) 생성자

지정된 동등 비교자를 사용하는 빈 세트를 생성합니다.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEqualityComparer<T>> &comparer)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<T\>\>\& | [Comparer](../../comparer/) 객체를 hashset과 연결합니다. |

## HashSet::HashSet(const SharedPtr\<IEnumerable\<T\>\>\&) 생성자

열거 가능한 값들을 기반으로 hashset을 생성합니다.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEnumerable<T>> &items)
```

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [HashSet](../)
* 클래스 [IEqualityComparer](../../iequalitycomparer/)
* 클래스 [IEnumerable](../../ienumerable/)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)