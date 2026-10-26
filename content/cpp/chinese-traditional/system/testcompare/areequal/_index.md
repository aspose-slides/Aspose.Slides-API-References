---
title: AreEqual()
second_title: Aspose.Slides for C++ API 參考
description: 比較非指標的陣列。
type: docs
weight: 1
url: /zh-hant/system/testcompare/areequal/
---
## TestCompare::AreEqual(const SharedPtr\<Array\<T\>\>\&, const SharedPtr\<Array\<U\>\>\&) 方法


比較非指標的陣列。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<T>> &arrA, const SharedPtr<Array<U>> &arrB)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 第一個陣列元素類型。 |
| U | 第二個陣列元素類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | 左側陣列。 |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<U\>\>\& | 右側陣列。 |

### 傳回值

若陣列大小與資料相符則返回 true，否則返回 false。

## TestCompare::AreEqual(const SharedPtr\<Array\<SharedPtr\<T\>\>\>\&, const SharedPtr\<Array\<SharedPtr\<U\>\>\>\&) 方法


比較指標陣列。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<SharedPtr<T>>> &arrA, const SharedPtr<Array<SharedPtr<U>>> &arrB)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 第一個陣列所指向的類型。 |
| U | 第二個陣列所指向的類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | 左側陣列。 |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | 右側陣列。 |

### 傳回值

若陣列大小與物件相符則返回 true，否則返回 false。

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const SharedPtr\<SCG::List\<U\>\>\&) 方法


比較非指標的 List。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const SharedPtr<SCG::List<U>> &listB)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 第一個 List 元素類型。 |
| U | 第二個 List 元素類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | 左側列表。 |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | 右側列表。 |

### 傳回值

若大小與資料相符則返回 true，否則返回 false。

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) 方法


比較指標 List。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &listA, const SharedPtr<SCG::List<SharedPtr<U>>> &listB)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 第一個 List 所指向的類型。 |
| U | 第二個 List 所指向的類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | 左側列表。 |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | 右側列表。 |

### 傳回值

若 List 大小與物件相符則返回 true，否則返回 false。

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const System::ArrayPtr\<U\>\&) 方法


比較 List 與非指標陣列。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const System::ArrayPtr<U> &arrB)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | List 元素類型。 |
| U | [Array](../../array/) 元素類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | 列表。 |
| arrB | const [System::ArrayPtr](../../arrayptr/)\<U\>\& | [Array](../../array/)。 |

### 傳回值

若大小與資料相符則返回 true，否則返回 false。

## TestCompare::AreEqual(const System::ArrayPtr\<T\>\&, const SharedPtr\<SCG::List\<U\>\>\&) 方法


比較 List 與非指標陣列。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<T> &arrA, const SharedPtr<SCG::List<U>> &listB)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | [Array](../../array/) 元素類型。 |
| U | List 元素類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| arrA | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | [Array](../../array/)。 |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | 列表。 |

### 傳回值

若大小與資料相符則返回 true，否則返回 false。

## TestCompare::AreEqual(const System::ArrayPtr\<SharedPtr\<T\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) 方法


比較指標 List 與指標陣列。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<SharedPtr<T>> &arr, const SharedPtr<SCG::List<SharedPtr<U>>> &list)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | [Array](../../array/) 所指向的類型。 |
| U | List 所指向的類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | [Array](../../array/)。 |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | 列表。 |

### 傳回值

若大小與物件相符則返回 true，否則返回 false。

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const System::ArrayPtr\<SharedPtr\<U\>\>\&) 方法


比較指標 List 與指標陣列。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &list, const System::ArrayPtr<SharedPtr<U>> &arr)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | List 所指向的類型。 |
| U | [Array](../../array/) 所指向的類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | 列表。 |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | [Array](../../array/)。 |

### 傳回值

若大小與物件相符則返回 true，否則返回 false。

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, U\>\>\&, const SharedPtr\<SCG::Dictionary\<K, U\>\>\&) 方法


比較非指標映射類型的字典。

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, U>> &dictA, const SharedPtr<SCG::Dictionary<K, U>> &dictB)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| K | 鍵類型。 |
| U | 映射類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | 左側字典。 |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | 右側字典。 |

### 傳回值

若字典大小與資料相符則返回 true，否則返回 false。

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&) 方法


比較指標映射類型的字典。

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictB)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| K | 鍵類型。 |
| U | 映射所指向的類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | 左側字典。 |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | 右側字典。 |

### 傳回值

若字典大小與資料相符則返回 true，否則返回 false。

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::Dictionary\<K2, U2\>\>\&) 方法


比較不同類型的字典。

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K1, U1>> &dictA, const SharedPtr<SCG::Dictionary<K2, U2>> &dictB)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| K1 | 左側字典鍵類型。 |
| U1 | 左側字典映射類型。 |
| K2 | 右側字典鍵類型。 |
| U2 | 右側字典映射類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K1, U1\>\>\& | 左側字典。 |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K2, U2\>\>\& | 右側字典。 |

### 傳回值

此情況始終返回 false，因為不允許型別轉換。

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<T\>\>\&, const SharedPtr\<SCG::HashSet\<U\>\>\&) 方法


比較非指標的雜湊集合。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<T>> &containerPtrA, const SharedPtr<SCG::HashSet<U>> &containerPtrB)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 第一個雜湊集合元素類型。 |
| U | 第二個雜湊集合元素類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| containerPtrA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<T\>\>\& | 左側雜湊集合。 |
| containerPtrB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<U\>\>\& | 右側雜湊集合。 |

### 傳回值

若雜湊集合大小與資料相符則返回 true，否則返回 false。

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::HashSet\<SharedPtr\<U\>\>\>\&) 方法


比較指標的雜湊集合。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<SharedPtr<T>>> &contA, const SharedPtr<SCG::HashSet<SharedPtr<U>>> &contB)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 第一個雜湊集合所指向的類型。 |
| U | 第二個雜湊集合所指向的類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| contA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | 左側雜湊集合。 |
| contB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | 右側雜湊集合。 |

### 傳回值

若雜湊集合大小與資料相符則返回 true，否則返回 false。

## TestCompare::AreEqual(const SCG::QueuePtr\<T\>\&, const SCG::QueuePtr\<U\>\&) 方法


比較非指標的佇列。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<T> &queueA, const SCG::QueuePtr<U> &queueB)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 第一個佇列元素類型。 |
| U | 第二個佇列元素類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<T\>\& | 左側佇列。 |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<U\>\& | 右側佇列。 |

### 傳回值

若佇列大小與資料相符則返回 true，否則返回 false。

## TestCompare::AreEqual(const SCG::QueuePtr\<SharedPtr\<T\>\>\&, const SCG::QueuePtr\<SharedPtr\<U\>\>\&) 方法


比較指標佇列。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<SharedPtr<T>> &queueA, const SCG::QueuePtr<SharedPtr<U>> &queueB)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 第一個佇列所指向的類型。 |
| U | 第二個佇列所指向的類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | 左側佇列。 |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | 右側佇列。 |

### 傳回值

若佇列大小與資料相符則返回 true，否則返回 false。

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<T\>\>\&, const SharedPtr\<SCG::Stack\<U\>\>\&) 方法


比較非指標的堆疊。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<T>> &stackA, const SharedPtr<SCG::Stack<U>> &stackB)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 第一個堆疊元素類型。 |
| U | 第二個堆疊元素類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<T\>\>\& | 左側堆疊。 |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<U\>\>\& | 右側堆疊。 |

### 傳回值

若堆疊大小與資料相符則返回 true，否則返回 false。

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::Stack\<SharedPtr\<U\>\>\>\&) 方法


比較指標堆疊。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<SharedPtr<T>>> &stackA, const SharedPtr<SCG::Stack<SharedPtr<U>>> &stackB)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 第一個堆疊所指向的類型。 |
| U | 第二個堆疊所指向的類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | 左側堆疊。 |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | 右側堆疊。 |

### 傳回值

若堆疊大小與資料相符則返回 true，否則返回 false。

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&) 方法


比較非指標映射類型的已排序字典。

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, U>> &dictA, const SharedPtr<SCG::SortedDictionary<K, U>> &dictB)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| K | 鍵類型。 |
| U | 映射類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | 左側字典。 |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | 右側字典。 |

### 傳回值

若字典大小與資料相符則返回 true，否則返回 false。

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&) 方法


比較指標映射類型的已排序字典。

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictB)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| K | 鍵類型。 |
| U | 映射所指向的類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | 左側字典。 |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | 右側字典。 |

### 傳回值

若字典大小與資料相符則返回 true，否則返回 false。

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K2, U2\>\>\&) 方法


比較不同類型的已排序字典。

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K1, U1>> &dictA, const SharedPtr<SCG::SortedDictionary<K2, U2>> &dictB)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| K1 | 左側字典鍵類型。 |
| U1 | 左側字典映射類型。 |
| K2 | 右側字典鍵類型。 |
| U2 | 右側字典映射類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K1, U1\>\>\& | 左側字典。 |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K2, U2\>\>\& | 右側字典。 |

### 傳回值

此情況始終返回 false，因為不允許型別轉換。

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, U\>\>\&, const SharedPtr\<SCG::SortedList\<K, U\>\>\&) 方法


比較非指標映射類型的已排序列表。

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, U>> &dictA, const SharedPtr<SCG::SortedList<K, U>> &dictB)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| K | 鍵類型。 |
| U | 映射類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | 左側列表。 |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | 右側列表。 |

### 傳回值

若列表大小與資料相符則返回 true，否則返回 false。

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&) 方法


比較指標映射類型的已排序列表。

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictB)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| K | 鍵類型。 |
| U | 映射所指向的類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | 左側列表。 |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | 右側列表。 |

### 傳回值

若列表大小與資料相符則返回 true，否則返回 false。

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedList\<K2, U2\>\>\&) 方法


比較不同類型的已排序列表。

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K1, U1>> &dictA, const SharedPtr<SCG::SortedList<K2, U2>> &dictB)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| K1 | 左側列表鍵類型。 |
| U1 | 左側列表映射類型。 |
| K2 | 右側列表鍵類型。 |
| U2 | 右側列表映射類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K1, U1\>\>\& | 左側列表。 |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K2, U2\>\>\& | 右側列表。 |

### 傳回值

此情況始終返回 false，因為不允許型別轉換。

## TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr\&, const System::Collections::Specialized::StringCollectionPtr\&) 方法


比較字串集合。

```cpp
static bool System::TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr &arrA, const System::Collections::Specialized::StringCollectionPtr &arrB)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| arrA | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | 左側集合。 |
| arrB | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | 右側集合。 |

### 傳回值

若大小與資料相符則返回 True，否則返回 false。

## TestCompare::AreEqual(const System::SharedPtr\<SCG::IEnumerable\<T\>\>\&, const System::SharedPtr\<SCG::IEnumerable\<U\>\>\&) 方法


比較 IEnumerable 實例。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::SharedPtr<SCG::IEnumerable<T>> &et, const System::SharedPtr<SCG::IEnumerable<U>> &eu)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| et | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<T\>\>\& | 左側可列舉物件。 |
| eu | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<U\>\>\& | 右側可列舉物件。 |

### 傳回值

若大小與資料相符則返回 True，否則返回 false。

## 另請參閱

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