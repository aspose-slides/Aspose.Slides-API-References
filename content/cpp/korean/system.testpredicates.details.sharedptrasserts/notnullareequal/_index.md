---
title: NotNullAreEqual()
second_title: C++용 Aspose.Slides API 참조
description: 값 유형 사전을 동등 비교합니다.
type: docs
weight: 53
url: /ko/system.testpredicates.details.sharedptrasserts/notnullareequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\>\&) 함수

값 유형 사전을 동등 비교합니다.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &rhs)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| K | 키 유형. |
| V | 값 유형. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | 좌변 표현식. |
| rhs_expr | const char * | 우변 표현식. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | 좌변 값. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | 우변 값. |

### 반환 값

gtest 스타일 어설션 결과.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\>) 함수

공유 포인터 사전을 동등 비교합니다.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &rhs)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| K | 키 유형. |
| V | 값 유형. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | 좌변 표현식. |
| rhs_expr | const char * | 우변 표현식. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | 좌변 값. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | 우변 값. |

### 반환 값

gtest 스타일 어설션 결과.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::HashSet\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::HashSet\<T2\>\>) 함수

해시 집합을 동등 비교합니다.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::HashSet<T1>> &lhs, const SharedPtr<System::Collections::Generic::HashSet<T2>> &rhs)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | 좌변 컨테이너 요소 유형. |
| T2 | 우변 컨테이너 요소 유형. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | 좌변 표현식. |
| rhs_expr | const char * | 우변 표현식. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T1\>\>\& | 좌변 값. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T2\>\>\& | 우변 값. |

### 반환 값

gtest 스타일 어설션 결과.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Queue\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Queue\<T2\>\>) 함수

큐를 동등 비교합니다.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Queue<T1>> &lhs, const SharedPtr<System::Collections::Generic::Queue<T2>> &rhs)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | 좌변 컨테이너 요소 유형. |
| T2 | 우변 컨테이너 요소 유형. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | 좌변 표현식. |
| rhs_expr | const char * | 우변 표현식. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T1\>\>\& | 좌변 값. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T2\>\>\& | 우변 값. |

### 반환 값

gtest 스타일 어설션 결과.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Stack\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Stack\<T2\>\>) 함수

스택을 동등 비교합니다.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Stack<T1>> &lhs, const SharedPtr<System::Collections::Generic::Stack<T2>> &rhs)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | 좌변 컨테이너 요소 유형. |
| T2 | 우변 컨테이너 요소 유형. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | 좌변 표현식. |
| rhs_expr | const char * | 우변 표현식. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T1\>\>\& | 좌변 값. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T2\>\>\& | 우변 값. |

### 반환 값

gtest 스타일 어설션 결과.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>) 함수

값 유형의 정렬된 사전을 동등 비교합니다.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &rhs)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| K | 키 유형. |
| V | 값 유형. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | 좌변 표현식. |
| rhs_expr | const char * | 우변 표현식. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | 좌변 값. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | 우변 값. |

### 반환 값

gtest 스타일 어설션 결과.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>) 함수

공유 포인터의 정렬된 사전을 동등 비교합니다.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &rhs)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| K | 키 유형. |
| V | 값 유형. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | 좌변 표현식. |
| rhs_expr | const char * | 우변 표현식. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | 좌변 값. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | 우변 값. |

### 반환 값

gtest 스타일 어설션 결과.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>) 함수

값 유형의 정렬된 리스트를 동등 비교합니다.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &rhs)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| K | 키 유형. |
| V | 값 유형. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | 좌변 표현식. |
| rhs_expr | const char * | 우변 표현식. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | 좌변 값. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | 우변 값. |

### 반환 값

gtest 스타일 어설션 결과.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>) 함수

공유 포인터의 정렬된 리스트를 동등 비교합니다.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &rhs)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| K | 키 유형. |
| V | 값 유형. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | 좌변 표현식. |
| rhs_expr | const char * | 우변 표현식. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | 좌변 값. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | 우변 값. |

### 반환 값

gtest 스타일 어설션 결과.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::BitArray\>\&, const SharedPtr\<System::Collections::BitArray\>\&) 함수

비트 배열을 동등 비교합니다.

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::BitArray> &lhs, const SharedPtr<System::Collections::BitArray> &rhs)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | 좌변 표현식. |
| rhs_expr | const char * | 우변 표현식. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | 좌변 값. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | 우변 값. |

### 반환 값

gtest 스타일 어설션 결과.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&) 함수

문자열 컬렉션을 동등 비교합니다.

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Specialized::StringCollection> &lhs, const SharedPtr<System::Collections::Specialized::StringCollection> &rhs)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | 좌변 표현식. |
| rhs_expr | const char * | 우변 표현식. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | 좌변 값. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | 우변 값. |

### 반환 값

gtest 스타일 어설션 결과.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&) 함수

추상 컬렉션을 동등 비교합니다.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::ICollection<T>> &lhs, const SharedPtr<System::Collections::Generic::ICollection<T>> &rhs)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 요소 유형. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | 좌변 표현식. |
| rhs_expr | const char * | 우변 표현식. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | 좌변 값. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | 우변 값. |

### 반환 값

gtest 스타일 어설션 결과.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<Object\>\&, const SharedPtr\<Object\>\&) 함수

두 [Object](../../system/object/) 유형을 동등 비교합니다.

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<Object> &lhs, const SharedPtr<Object> &rhs)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | 좌변 표현식. |
| rhs_expr | const char * | 우변 표현식. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | 좌변 값. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | 우변 값. |

### 반환 값

gtest 스타일 어설션 결과.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<T1\>\&, const SharedPtr\<T2\>\&) 함수

알 수 없는 유형을 동등 비교합니다.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<T1> &lhs, const SharedPtr<T2> &rhs)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | 좌변 객체 유형. |
| T2 | 우변 객체 유형. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | 좌변 표현식. |
| rhs_expr | const char * | 우변 표현식. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<T1\>\& | 좌변 값. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<T2\>\& | 우변 값. |

### 반환 값

gtest 스타일 어설션 결과.

## 참고

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Dictionary](../../system.collections.generic/dictionary/)
* Class [HashSet](../../system.collections.generic/hashset/)
* Class [Queue](../../system.collections.generic/queue/)
* Class [Stack](../../system.collections.generic/stack/)
* Class [SortedDictionary](../../system.collections.generic/sorteddictionary/)
* Class [SortedList](../../system.collections.generic/sortedlist/)
* Class [BitArray](../../system.collections/bitarray/)
* Class [StringCollection](../../system.collections.specialized/stringcollection/)
* Class [ICollection](../../system.collections.generic/icollection/)
* Class [Object](../../system/object/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)