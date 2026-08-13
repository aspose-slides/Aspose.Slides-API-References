---
title: AreEqual()
second_title: Aspose.Slides for C++ API 참조
description: 포인터가 아닌 배열을 비교합니다.
type: docs
weight: 1
url: /ko/system/testcompare/areequal/
---
## TestCompare::AreEqual(const SharedPtr\<Array\<T\>\>\&, const SharedPtr\<Array\<U\>\>\&) method


비포인터 배열을 비교합니다.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<T>> &arrA, const SharedPtr<Array<U>> &arrB)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 첫 번째 배열 요소 유형. |
| U | 두 번째 배열 요소 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | LHS 배열. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<U\>\>\& | RHS 배열. |

### 반환 값

배열 크기와 데이터가 일치하면 true, 그렇지 않으면 false.

## TestCompare::AreEqual(const SharedPtr\<Array\<SharedPtr\<T\>\>\>\&, const SharedPtr\<Array\<SharedPtr\<U\>\>\>\&) method


포인터 배열을 비교합니다.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<SharedPtr<T>>> &arrA, const SharedPtr<Array<SharedPtr<U>>> &arrB)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 첫 번째 배열 피오네티 유형. |
| U | 두 번째 배열 피오네티 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | LHS 배열. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | RHS 배열. |

### 반환 값

배열 크기와 객체가 일치하면 true, 그렇지 않으면 false.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const SharedPtr\<SCG::List\<U\>\>\&) method


비포인터 리스트를 비교합니다.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const SharedPtr<SCG::List<U>> &listB)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 첫 번째 리스트 요소 유형. |
| U | 두 번째 리스트 요소 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | LHS 리스트. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | RHS 리스트. |

### 반환 값

크기와 데이터가 일치하면 true, 그렇지 않으면 false.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) method


포인터 리스트를 비교합니다.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &listA, const SharedPtr<SCG::List<SharedPtr<U>>> &listB)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 첫 번째 리스트 피오네티 유형. |
| U | 두 번째 리스트 피오네티 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | LHS 리스트. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | RHS 리스트. |

### 반환 값

리스트 크기와 객체가 일치하면 true, 그렇지 않으면 false.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const System::ArrayPtr\<U\>\&) method


비포인터 요소인 경우 리스트와 배열을 비교합니다.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const System::ArrayPtr<U> &arrB)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 리스트 요소 유형. |
| U | [Array](../../array/) 요소 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | 리스트. |
| arrB | const [System::ArrayPtr](../../arrayptr/)\<U\>\& | [Array](../../array/). |

### 반환 값

크기와 데이터가 일치하면 true, 그렇지 않으면 false.

## TestCompare::AreEqual(const System::ArrayPtr\<T\>\&, const SharedPtr\<SCG::List\<U\>\>\&) method


비포인터 요소인 경우 리스트와 배열을 비교합니다.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<T> &arrA, const SharedPtr<SCG::List<U>> &listB)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Array](../../array/) 요소 유형. |
| U | 리스트 요소 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arrA | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | [Array](../../array/). |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | 리스트. |

### 반환 값

크기와 데이터가 일치하면 true, 그렇지 않으면 false.

## TestCompare::AreEqual(const System::ArrayPtr\<SharedPtr\<T\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) method


포인터 요소인 경우 리스트와 배열을 비교합니다.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<SharedPtr<T>> &arr, const SharedPtr<SCG::List<SharedPtr<U>>> &list)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Array](../../array/) 피오네티 유형. |
| U | 리스트 피오네티 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | [Array](../../array/). |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | 리스트. |

### 반환 값

크기와 객체가 일치하면 true, 그렇지 않으면 false.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const System::ArrayPtr\<SharedPtr\<U\>\>\&) method


포인터 요소인 경우 리스트와 배열을 비교합니다.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &list, const System::ArrayPtr<SharedPtr<U>> &arr)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 리스트 피오네티 유형. |
| U | [Array](../../array/) 피오네티 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | 리스트. |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | [Array](../../array/). |

### 반환 값

크기와 객체가 일치하면 true, 그렇지 않으면 false.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, U\>\>\&, const SharedPtr\<SCG::Dictionary\<K, U\>\>\&) method


비포인터 매핑 타입 사전을 비교합니다.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, U>> &dictA, const SharedPtr<SCG::Dictionary<K, U>> &dictB)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| K | 키 유형. |
| U | 매핑된 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | LHS 사전. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | RHS 사전. |

### 반환 값

사전 크기와 데이터가 일치하면 true, 그렇지 않으면 false.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&) method


포인터 매핑 타입 사전을 비교합니다.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictB)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| K | 키 유형. |
| U | 매핑된 피오네티 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | LHS 사전. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | RHS 사전. |

### 반환 값

사전 크기와 데이터가 일치하면 true, 그렇지 않으면 false.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::Dictionary\<K2, U2\>\>\&) method


다른 유형의 사전을 비교합니다.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K1, U1>> &dictA, const SharedPtr<SCG::Dictionary<K2, U2>> &dictB)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| K1 | LHS 사전 키 유형. |
| U1 | LHS 사전 매핑된 유형. |
| K2 | RHS 사전 키 유형. |
| U2 | RHS 사전 매핑된 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K1, U1\>\>\& | LHS 사전. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K2, U2\>\>\& | RHS 사전. |

### 반환 값

여기서는 타입 변환이 금지되므로 항상 false를 반환합니다.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<T\>\>\&, const SharedPtr\<SCG::HashSet\<U\>\>\&) method


비포인터 해시셋을 비교합니다.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<T>> &containerPtrA, const SharedPtr<SCG::HashSet<U>> &containerPtrB)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 첫 번째 해시셋 요소 유형. |
| U | 두 번째 해시셋 요소 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| containerPtrA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<T\>\>\& | LHS 해시셋. |
| containerPtrB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<U\>\>\& | RHS 해시셋. |

### 반환 값

해시셋 크기와 데이터가 일치하면 true, 그렇지 않으면 false.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::HashSet\<SharedPtr\<U\>\>\>\&) method


포인터 해시셋을 비교합니다.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<SharedPtr<T>>> &contA, const SharedPtr<SCG::HashSet<SharedPtr<U>>> &contB)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 첫 번째 해시셋 피오네티 유형. |
| U | 두 번째 해시셋 피오네티 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| contA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | LHS 해시셋. |
| contB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | RHS 해시셋. |

### 반환 값

해시셋 크기와 데이터가 일치하면 true, 그렇지 않으면 false.

## TestCompare::AreEqual(const SCG::QueuePtr\<T\>\&, const SCG::QueuePtr\<U\>\&) method


비포인터 큐를 비교합니다.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<T> &queueA, const SCG::QueuePtr<U> &queueB)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 첫 번째 큐 요소 유형. |
| U | 두 번째 큐 요소 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<T\>\& | LHS 큐. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<U\>\& | RHS 큐. |

### 반환 값

큐 크기와 데이터가 일치하면 true, 그렇지 않으면 false.

## TestCompare::AreEqual(const SCG::QueuePtr\<SharedPtr\<T\>\>\&, const SCG::QueuePtr\<SharedPtr\<U\>\>\&) method


포인터 큐를 비교합니다.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<SharedPtr<T>> &queueA, const SCG::QueuePtr<SharedPtr<U>> &queueB)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 첫 번째 큐 피오네티 유형. |
| U | 두 번째 큐 피오네티 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | LHS 큐. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | RHS 큐. |

### 반환 값

큐 크기와 데이터가 일치하면 true, 그렇지 않으면 false.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<T\>\>\&, const SharedPtr\<SCG::Stack\<U\>\>\&) method


비포인터 스택을 비교합니다.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<T>> &stackA, const SharedPtr<SCG::Stack<U>> &stackB)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 첫 번째 스택 요소 유형. |
| U | 두 번째 스택 요소 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<T\>\>\& | LHS 스택. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<U\>\>\& | RHS 스택. |

### 반환 값

스택 크기와 데이터가 일치하면 true, 그렇지 않으면 false.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::Stack\<SharedPtr\<U\>\>\>\&) method


포인터 스택을 비교합니다.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<SharedPtr<T>>> &stackA, const SharedPtr<SCG::Stack<SharedPtr<U>>> &stackB)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 첫 번째 스택 피오네티 유형. |
| U | 두 번째 스택 피오네티 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | LHS 스택. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | RHS 스택. |

### 반환 값

스택 크기와 데이터가 일치하면 true, 그렇지 않으면 false.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&) method


비포인터 매핑 타입 정렬 사전을 비교합니다.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, U>> &dictA, const SharedPtr<SCG::SortedDictionary<K, U>> &dictB)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| K | 키 유형. |
| U | 매핑된 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | LHS 사전. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | RHS 사전. |

### 반환 값

사전 크기와 데이터가 일치하면 true, 그렇지 않으면 false.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&) method


포인터 매핑 타입 정렬 사전을 비교합니다.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictB)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| K | 키 유형. |
| U | 매핑된 피오네티 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | LHS 사전. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | RHS 사전. |

### 반환 값

사전 크기와 데이터가 일치하면 true, 그렇지 않으면 false.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K2, U2\>\>\&) method


다른 유형의 정렬 사전을 비교합니다.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K1, U1>> &dictA, const SharedPtr<SCG::SortedDictionary<K2, U2>> &dictB)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| K1 | LHS 사전 키 유형. |
| U1 | LHS 사전 매핑된 유형. |
| K2 | RHS 사전 키 유형. |
| U2 | RHS 사전 매핑된 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K1, U1\>\>\& | LHS 사전. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K2, U2\>\>\& | RHS 사전. |

### 반환 값

여기서는 타입 변환이 금지되므로 항상 false를 반환합니다.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, U\>\>\&, const SharedPtr\<SCG::SortedList\<K, U\>\>\&) method


비포인터 매핑 타입 정렬 리스트를 비교합니다.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, U>> &dictA, const SharedPtr<SCG::SortedList<K, U>> &dictB)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| K | 키 유형. |
| U | 매핑된 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | LHS 리스트. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | RHS 리스트. |

### 반환 값

리스트 크기와 데이터가 일치하면 true, 그렇지 않으면 false.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&) method


포인터 매핑 타입 정렬 리스트를 비교합니다.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictB)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| K | 키 유형. |
| U | 매핑된 피오네티 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | LHS 리스트. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | RHS 리스트. |

### 반환 값

리스트 크기와 데이터가 일치하면 true, 그렇지 않으면 false.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedList\<K2, U2\>\>\&) method


다른 유형의 정렬 리스트를 비교합니다.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K1, U1>> &dictA, const SharedPtr<SCG::SortedList<K2, U2>> &dictB)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| K1 | LHS 리스트 키 유형. |
| U1 | LHS 리스트 매핑된 유형. |
| K2 | RHS 리스트 키 유형. |
| U2 | RHS 리스트 매핑된 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K1, U1\>\>\& | LHS 리스트. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K2, U2\>\>\& | RHS 리스트. |

### 반환 값

여기서는 타입 변환이 금지되므로 항상 false를 반환합니다.

## TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr\&, const System::Collections::Specialized::StringCollectionPtr\&) method


문자열 컬렉션을 비교합니다.

```cpp
static bool System::TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr &arrA, const System::Collections::Specialized::StringCollectionPtr &arrB)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arrA | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | LHS 컬렉션. |
| arrB | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | RHS 컬렉션. |

### 반환 값

크기와 데이터가 일치하면 true, 그렇지 않으면 false.

## TestCompare::AreEqual(const System::SharedPtr\<SCG::IEnumerable\<T\>\>\&, const System::SharedPtr\<SCG::IEnumerable\<U\>\>\&) method


IEnumerable 인스턴스를 비교합니다.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::SharedPtr<SCG::IEnumerable<T>> &et, const System::SharedPtr<SCG::IEnumerable<U>> &eu)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| et | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<T\>\>\& | LHS enumerable 객체. |
| eu | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<U\>\>\& | RHS enumerable 객체. |

### 반환 값

크기와 데이터가 일치하면 true, 그렇지 않으면 false.

## 또 보기

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../../array/)
* Class [List](../../../system.collections.generic/list/)
* Class [Dictionary](../../../system.collections.generic/dictionary/)
* Class [HashSet](../../../system.collections.generic/hashset/)
* Class [QueuePtr](../../../system.collections.generic/queueptr/)
* Class [Stack](../../../system.collections.generic/stack/)
* Class [SortedDictionary](../../../system.collections.generic/sorteddictionary/)
* Class [SortedList](../../../system.collections.generic/sortedlist/)
* Class [StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struct [TestCompare](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)