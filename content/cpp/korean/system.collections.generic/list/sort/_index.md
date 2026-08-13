---
title: Sort()
second_title: Aspose.Slides for C++ API 참조
description: 목록의 요소를 정렬합니다.
type: docs
weight: 521
url: /ko/system.collections.generic/list/sort/
---
## List::Sort(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) 메서드

리스트의 요소를 정렬합니다.

```cpp
void System::Collections::Generic::List<T>::Sort(const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| comparator | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | 사용할 비교자. |

## List::Sort() 메서드

기본 비교자를 사용하여 목록의 요소를 정렬합니다.

```cpp
void System::Collections::Generic::List<T>::Sort()
```

## List::Sort(int, int, SharedPtr\<System::Collections::Generic::IComparer\<T\>\>) 메서드

목록 슬라이스의 요소를 정렬합니다.

```cpp
void System::Collections::Generic::List<T>::Sort(int index, int count, SharedPtr<System::Collections::Generic::IComparer<T>> comparator)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 슬라이스 시작 인덱스. |
| count | int | 슬라이스 크기. |
| comparator | [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\> | 사용할 비교자. |

## List::Sort(Comparison\<T\>, bool) 메서드

리스트의 요소를 정렬합니다.

```cpp
void System::Collections::Generic::List<T>::Sort(Comparison<T> comparison, bool)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| comparison | [Comparison](../../../system/comparison/)\<T\> | 사용할 [Comparison](../../../system/comparison/). |

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IComparer](../../icomparer/)
* 클래스 [List](../)
* 클래스 [Comparison](../../../system/comparison/)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)