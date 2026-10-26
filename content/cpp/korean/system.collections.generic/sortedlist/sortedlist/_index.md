---
title: SortedList()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 빈 리스트를 생성합니다.
type: docs
weight: 1
url: /ko/system.collections.generic/sortedlist/sortedlist/
---
## SortedList::SortedList() 생성자

빈 리스트를 생성합니다.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList()
```

## SortedList::SortedList(const SharedPtr\<IComparer\<TKey\>\>\&) 생성자

빈 리스트를 생성합니다.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IComparer<TKey>> &comparer)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) 사용. |

## SortedList::SortedList(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) 생성자

복사 생성자.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../../dictionary/) 복사할 데이터. |

## SortedList::SortedList(const map_t\&) 생성자

복사 생성자.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const map_t &map)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | 복사할 맵. |

## SortedList::SortedList(int) 생성자

빈 리스트를 생성합니다.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(int capacity)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| capacity | int | 예약할 요소 수. |

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 타입 정의 [map_t](../map_t/)
* 클래스 [SortedList](../)
* 클래스 [IComparer](../../icomparer/)
* 클래스 [IDictionary](../../idictionary/)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)