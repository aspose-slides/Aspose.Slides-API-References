---
title: SortedSet()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 빈 세트를 생성합니다.
type: docs
weight: 1
url: /ko/system.collections.generic/sortedset/sortedset/
---
## SortedSet::SortedSet() 생성자

빈 세트를 생성합니다.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet()
```

## SortedSet::SortedSet(int) 생성자

지정된 용량으로 빈 세트를 생성합니다.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(int capacity)
```

## SortedSet::SortedSet(const SharedPtr\<IComparer\<T\>\>\&) 생성자

지정된 비교자를 사용하는 빈 세트를 생성합니다.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IComparer<T>> &comparer)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) 객체를 [SortedSet](../)와 연결합니다. |

## SortedSet::SortedSet(const SharedPtr\<IEnumerable\<T\>\>\&) 생성자

열거 가능한 값에 기반하여 [SortedSet](../)를 생성합니다.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IEnumerable<T>> &items)
```

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [SortedSet](../)
* 클래스 [IComparer](../../icomparer/)
* 클래스 [IEnumerable](../../ienumerable/)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)