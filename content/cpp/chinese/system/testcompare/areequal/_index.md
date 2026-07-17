---
title: AreEqual()
second_title: Aspose.Slides for C++ API 参考
description: 比较非指针数组。
type: docs
weight: 1
url: /zh/system/testcompare/areequal/
---
## TestCompare::AreEqual(const SharedPtr\<Array\<T\>\>\&, const SharedPtr\<Array\<U\>\>\&) 方法

比较非指针数组。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<T>> &arrA, const SharedPtr<Array<U>> &arrB)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 第一个数组元素类型。 |
| U | 第二个数组元素类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | 左侧数组。 |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<U\>\>\& | 右侧数组。 |

### 返回值

如果数组大小和数据匹配，则返回 true；否则返回 false。

## TestCompare::AreEqual(const SharedPtr\<Array\<SharedPtr\<T\>\>\>\&, const SharedPtr\<Array\<SharedPtr\<U\>\>\>\&) 方法

比较指针数组。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<SharedPtr<T>>> &arrA, const SharedPtr<Array<SharedPtr<U>>> &arrB)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 第一个数组指向的类型。 |
| U | 第二个数组指向的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | 左侧数组。 |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | 右侧数组。 |

### 返回值

如果数组大小和对象匹配，则返回 true；否则返回 false。

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const SharedPtr\<SCG::List\<U\>\>\&) 方法

比较非指针列表。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const SharedPtr<SCG::List<U>> &listB)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 第一个列表元素类型。 |
| U | 第二个列表元素类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | 左侧列表。 |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | 右侧列表。 |

### 返回值

如果大小和数据匹配，则返回 true；否则返回 false。

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) 方法

比较指针列表。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &listA, const SharedPtr<SCG::List<SharedPtr<U>>> &listB)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 第一个列表指向的类型。 |
| U | 第二个列表指向的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | 左侧列表。 |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | 右侧列表。 |

### 返回值

如果列表大小和对象匹配，则返回 true；否则返回 false。

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const System::ArrayPtr\<U\>\&) 方法

比较列表与数组（非指针元素情况）。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const System::ArrayPtr<U> &arrB)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 列表元素类型。 |
| U | [Array](../../array/) 元素类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | 列表。 |
| arrB | const [System::ArrayPtr](../../arrayptr/)\<U\>\& | [Array](../../array/)。 |

### 返回值

如果大小和数据匹配，则返回 true；否则返回 false。

## TestCompare::AreEqual(const System::ArrayPtr\<T\>\&, const SharedPtr\<SCG::List\<U\>\>\&) 方法

比较列表与数组（非指针元素情况）。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<T> &arrA, const SharedPtr<SCG::List<U>> &listB)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [Array](../../array/) 元素类型。 |
| U | 列表元素类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arrA | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | [Array](../../array/)。 |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | 列表。 |

### 返回值

如果大小和数据匹配，则返回 true；否则返回 false。

## TestCompare::AreEqual(const System::ArrayPtr\<SharedPtr\<T\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) 方法

比较列表与数组（指针元素情况）。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<SharedPtr<T>> &arr, const SharedPtr<SCG::List<SharedPtr<U>>> &list)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [Array](../../array/) 指向的类型。 |
| U | 列表指向的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | [Array](../../array/)。 |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | 列表。 |

### 返回值

如果大小和对象匹配，则返回 true；否则返回 false。

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const System::ArrayPtr\<SharedPtr\<U\>\>\&) 方法

比较列表与数组（指针元素情况）。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &list, const System::ArrayPtr<SharedPtr<U>> &arr)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 列表指向的类型。 |
| U | [Array](../../array/) 指向的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | 列表。 |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | [Array](../../array/)。 |

### 返回值

如果大小和对象匹配，则返回 true；否则返回 false。

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, U\>\>\&, const SharedPtr\<SCG::Dictionary\<K, U\>\>\&) 方法

比较非指针映射类型的字典。

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, U>> &dictA, const SharedPtr<SCG::Dictionary<K, U>> &dictB)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| K | 键类型。 |
| U | 映射类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | 左侧字典。 |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | 右侧字典。 |

### 返回值

如果字典大小和数据匹配，则返回 true；否则返回 false。

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&) 方法

比较指针映射类型的字典。

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictB)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| K | 键类型。 |
| U | 映射的指向类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | 左侧字典。 |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | 右侧字典。 |

### 返回值

如果字典大小和数据匹配，则返回 true；否则返回 false。

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::Dictionary\<K2, U2\>\>\&) 方法

比较不同类型的字典。

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K1, U1>> &dictA, const SharedPtr<SCG::Dictionary<K2, U2>> &dictB)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| K1 | 左侧字典键类型。 |
| U1 | 左侧字典映射类型。 |
| K2 | 右侧字典键类型。 |
| U2 | 右侧字典映射类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K1, U1\>\>\& | 左侧字典。 |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K2, U2\>\>\& | 右侧字典。 |

### 返回值

始终返回 false，因为此处禁止类型转换。

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<T\>\>\&, const SharedPtr\<SCG::HashSet\<U\>\>\&) 方法

比较非指针哈希集合。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<T>> &containerPtrA, const SharedPtr<SCG::HashSet<U>> &containerPtrB)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 第一个哈希集合元素类型。 |
| U | 第二个哈希集合元素类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| containerPtrA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<T\>\>\& | 左侧哈希集合。 |
| containerPtrB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<U\>\>\& | 右侧哈希集合。 |

### 返回值

如果哈希集合大小和数据匹配，则返回 true；否则返回 false。

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::HashSet\<SharedPtr\<U\>\>\>\&) 方法

比较指针哈希集合。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<SharedPtr<T>>> &contA, const SharedPtr<SCG::HashSet<SharedPtr<U>>> &contB)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 第一个哈希集合指向的类型。 |
| U | 第二个哈希集合指向的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| contA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | 左侧哈希集合。 |
| contB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | 右侧哈希集合。 |

### 返回值

如果哈希集合大小和数据匹配，则返回 true；否则返回 false。

## TestCompare::AreEqual(const SCG::QueuePtr\<T\>\&, const SCG::QueuePtr\<U\>\&) 方法

比较非指针队列。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<T> &queueA, const SCG::QueuePtr<U> &queueB)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 第一个队列元素类型。 |
| U | 第二个队列元素类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<T\>\& | 左侧队列。 |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<U\>\& | 右侧队列。 |

### 返回值

如果队列大小和数据匹配，则返回 true；否则返回 false。

## TestCompare::AreEqual(const SCG::QueuePtr\<SharedPtr\<T\>\>\&, const SCG::QueuePtr\<SharedPtr\<U\>\>\&) 方法

比较指针队列。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<SharedPtr<T>> &queueA, const SCG::QueuePtr<SharedPtr<U>> &queueB)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 第一个队列指向的类型。 |
| U | 第二个队列指向的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | 左侧队列。 |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | 右侧队列。 |

### 返回值

如果队列大小和数据匹配，则返回 true；否则返回 false。

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<T\>\>\&, const SharedPtr\<SCG::Stack\<U\>\>\&) 方法

比较非指针栈。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<T>> &stackA, const SharedPtr<SCG::Stack<U>> &stackB)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 第一个栈元素类型。 |
| U | 第二个栈元素类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<T\>\>\& | 左侧栈。 |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<U\>\>\& | 右侧栈。 |

### 返回值

如果栈大小和数据匹配，则返回 true；否则返回 false。

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::Stack\<SharedPtr\<U\>\>\>\&) 方法

比较指针栈。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<SharedPtr<T>>> &stackA, const SharedPtr<SCG::Stack<SharedPtr<U>>> &stackB)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 第一个栈指向的类型。 |
| U | 第二个栈指向的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | 左侧栈。 |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | 右侧栈。 |

### 返回值

如果栈大小和数据匹配，则返回 true；否则返回 false。

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&) 方法

比较非指针映射类型的已排序字典。

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, U>> &dictA, const SharedPtr<SCG::SortedDictionary<K, U>> &dictB)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| K | 键类型。 |
| U | 映射类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | 左侧字典。 |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | 右侧字典。 |

### 返回值

如果字典大小和数据匹配，则返回 true；否则返回 false。

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&) 方法

比较指针映射类型的已排序字典。

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictB)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| K | 键类型。 |
| U | 映射的指向类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | 左侧字典。 |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | 右侧字典。 |

### 返回值

如果字典大小和数据匹配，则返回 true；否则返回 false。

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K2, U2\>\>\&) 方法

比较不同类型的已排序字典。

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K1, U1>> &dictA, const SharedPtr<SCG::SortedDictionary<K2, U2>> &dictB)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| K1 | 左侧字典键类型。 |
| U1 | 左侧字典映射类型。 |
| K2 | 右侧字典键类型。 |
| U2 | 右侧字典映射类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K1, U1\>\>\& | 左侧字典。 |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K2, U2\>\>\& | 右侧字典。 |

### 返回值

始终返回 false，因为此处禁止类型转换。

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, U\>\>\&, const SharedPtr\<SCG::SortedList\<K, U\>\>\&) 方法

比较非指针映射类型的已排序列表。

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, U>> &dictA, const SharedPtr<SCG::SortedList<K, U>> &dictB)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| K | 键类型。 |
| U | 映射类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | 左侧列表。 |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | 右侧列表。 |

### 返回值

如果列表大小和数据匹配，则返回 true；否则返回 false。

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&) 方法

比较指针映射类型的已排序列表。

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictB)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| K | 键类型。 |
| U | 映射的指向类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | 左侧列表。 |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | 右侧列表。 |

### 返回值

如果列表大小和数据匹配，则返回 true；否则返回 false。

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedList\<K2, U2\>\>\&) 方法

比较不同类型的已排序列表。

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K1, U1>> &dictA, const SharedPtr<SCG::SortedList<K2, U2>> &dictB)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| K1 | 左侧列表键类型。 |
| U1 | 左侧列表映射类型。 |
| K2 | 右侧列表键类型。 |
| U2 | 右侧列表映射类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K1, U1\>\>\& | 左侧列表。 |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K2, U2\>\>\& | 右侧列表。 |

### 返回值

始终返回 false，因为此处禁止类型转换。

## TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr\&, const System::Collections::Specialized::StringCollectionPtr\&) 方法

比较字符串集合。

```cpp
static bool System::TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr &arrA, const System::Collections::Specialized::StringCollectionPtr &arrB)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arrA | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | 左侧集合。 |
| arrB | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | 右侧集合。 |

### 返回值

如果大小和数据匹配，则返回 True；否则返回 false。

## TestCompare::AreEqual(const System::SharedPtr\<SCG::IEnumerable\<T\>\>\&, const System::SharedPtr\<SCG::IEnumerable\<U\>\>\&) 方法

比较 IEnumerable 实例。

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::SharedPtr<SCG::IEnumerable<T>> &et, const System::SharedPtr<SCG::IEnumerable<U>> &eu)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| et | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<T\>\>\& | 左侧可枚举对象。 |
| eu | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<U\>\>\& | 右侧可枚举对象。 |

### 返回值

如果大小和数据匹配，则返回 True；否则返回 false。

## 另请参见

* 类型定义 [SharedPtr](../../sharedptr/)
* 类型定义 [ArrayPtr](../../arrayptr/)
* 类 [Array](../../array/)
* 类 [List](../../../system.collections.generic/list/)
* 类 [Dictionary](../../../system.collections.generic/dictionary/)
* 类 [HashSet](../../../system.collections.generic/hashset/)
* 类 [QueuePtr](../../../system.collections.generic/queueptr/)
* 类 [Stack](../../../system.collections.generic/stack/)
* 类 [SortedDictionary](../../../system.collections.generic/sorteddictionary/)
* 类 [SortedList](../../../system.collections.generic/sortedlist/)
* 类 [StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)
* 类 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 结构体 [TestCompare](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)