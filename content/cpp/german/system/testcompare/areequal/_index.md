---
title: AreEqual()
second_title: Aspose.Slides für C++ API-Referenz
description: Vergleicht Arrays von Nicht-Pointern.
type: docs
weight: 1
url: /de/system/testcompare/areequal/
---
## TestCompare::AreEqual(const SharedPtr\<Array\<T\>\>\&, const SharedPtr\<Array\<U\>\>\&) method


Vergleicht Arrays von Nicht-Pointern.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<T>> &arrA, const SharedPtr<Array<U>> &arrB)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | First array element type. |
| U | Second array element type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | LHS-Array. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<U\>\>\& | RHS-Array. |

### Rückgabewert

true, wenn die Array-Größen und Daten übereinstimmen, sonst false.

## TestCompare::AreEqual(const SharedPtr\<Array\<SharedPtr\<T\>\>\>\&, const SharedPtr\<Array\<SharedPtr\<U\>\>\>\&) method


Vergleicht Arrays von Zeigern.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<SharedPtr<T>>> &arrA, const SharedPtr<Array<SharedPtr<U>>> &arrB)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | First array pointee type. |
| U | Second array pointee type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | LHS-Array. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | RHS-Array. |

### Rückgabewert

true, wenn die Array-Größen und Objekte übereinstimmen, sonst false.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const SharedPtr\<SCG::List\<U\>\>\&) method


Vergleicht Listen von Nicht-Pointern.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const SharedPtr<SCG::List<U>> &listB)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | First list element type. |
| U | Second list element type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | LHS-Liste. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | RHS-Liste. |

### Rückgabewert

true, wenn die Größen und Daten übereinstimmen, sonst false.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) method


Vergleicht Listen von Zeigern.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &listA, const SharedPtr<SCG::List<SharedPtr<U>>> &listB)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | First list pointee type. |
| U | Second list pointee type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | LHS-Liste. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | RHS-Liste. |

### Rückgabewert

true, wenn die Listen-Größen und Objekte übereinstimmen, sonst false.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const System::ArrayPtr\<U\>\&) method


Vergleicht Listen mit Arrays im Fall von Nicht-Pointer-Elementen.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const System::ArrayPtr<U> &arrB)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | List element type. |
| U | [Array](../../array/) element type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | Liste. |
| arrB | const [System::ArrayPtr](../../arrayptr/)\<U\>\& | [Array](../../array/). |

### Rückgabewert

true, wenn die Größen und Daten übereinstimmen, sonst false.

## TestCompare::AreEqual(const System::ArrayPtr\<T\>\&, const SharedPtr\<SCG::List\<U\>\>\&) method


Vergleicht Listen mit Arrays im Fall von Nicht-Pointer-Elementen.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<T> &arrA, const SharedPtr<SCG::List<U>> &listB)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Array](../../array/) element type. |
| U | List element type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arrA | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | [Array](../../array/). |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | Liste. |

### Rückgabewert

true, wenn die Größen und Daten übereinstimmen, sonst false.

## TestCompare::AreEqual(const System::ArrayPtr\<SharedPtr\<T\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) method


Vergleicht Listen mit Arrays im Fall von Zeiger-Elementen.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<SharedPtr<T>> &arr, const SharedPtr<SCG::List<SharedPtr<U>>> &list)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Array](../../array/) pointee type. |
| U | List pointee type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | [Array](../../array/). |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Liste. |

### Rückgabewert

true, wenn die Größen und Objekte übereinstimmen, sonst false.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const System::ArrayPtr\<SharedPtr\<U\>\>\&) method


Vergleicht Listen mit Arrays im Fall von Zeiger-Elementen.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &list, const System::ArrayPtr<SharedPtr<U>> &arr)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | List pointee type. |
| U | [Array](../../array/) pointee type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Liste. |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | [Array](../../array/). |

### Rückgabewert

true, wenn die Größen und Objekte übereinstimmen, sonst false.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, U\>\>\&, const SharedPtr\<SCG::Dictionary\<K, U\>\>\&) method


Vergleicht Dictionaries von Nicht-Pointer-zugeordneten Typen.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, U>> &dictA, const SharedPtr<SCG::Dictionary<K, U>> &dictB)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| K | Key type. |
| U | Mapped type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | LHS-Wörterbuch. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | RHS-Wörterbuch. |

### Rückgabewert

true, wenn die Dictionaries-Größen und Daten übereinstimmen, sonst false.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>) method


Vergleicht Dictionaries von Zeiger-zugeordneten Typen.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictB)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| K | Key type. |
| U | Mapped pointee type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | LHS-Wörterbuch. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | RHS-Wörterbuch. |

### Rückgabewert

true, wenn die Dictionaries-Größen und Daten übereinstimmen, sonst false.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::Dictionary\<K2, U2\>\>\&) method


Vergleicht Dictionaries unterschiedlicher Typen.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K1, U1>> &dictA, const SharedPtr<SCG::Dictionary<K2, U2>> &dictB)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| K1 | LHS dictionary key type. |
| U1 | LHS dictionary mapped type. |
| K2 | RHS dictionary key type. |
| U2 | RHS dictionary mapped type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K1, U1\>\>\& | LHS-Wörterbuch. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K2, U2\>\>\& | RHS-Wörterbuch. |

### Rückgabewert

Always returns false as type conversion is forbidden here.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<T\>\>\&, const SharedPtr\<SCG::HashSet\<U\>\>\&) method


Vergleicht Hashsets von Nicht-Pointern.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<T>> &containerPtrA, const SharedPtr<SCG::HashSet<U>> &containerPtrB)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | First hashset element type. |
| U | Second hashset element type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| containerPtrA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<T\>\>\& | LHS-Hashset. |
| containerPtrB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<U\>\>\& | RHS-Hashset. |

### Rückgabewert

true, wenn die Hashsets-Größen und Daten übereinstimmen, sonst false.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::HashSet\<SharedPtr\<U\>\>\>\&) method


Vergleicht Hashsets von Zeigern.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<SharedPtr<T>>> &contA, const SharedPtr<SCG::HashSet<SharedPtr<U>>> &contB)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | First hashset pointee type. |
| U | Second hashset pointee type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| contA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | LHS-Hashset. |
| contB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | RHS-Hashset. |

### Rückgabewert

true, wenn die Hashsets-Größen und Daten übereinstimmen, sonst false.

## TestCompare::AreEqual(const SCG::QueuePtr\<T\>\&, const SCG::QueuePtr\<U\>\&) method


Vergleicht Queues von Nicht-Pointern.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<T> &queueA, const SCG::QueuePtr<U> &queueB)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | First queue element type. |
| U | Second queue element type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<T\>\& | LHS-Queue. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<U\>\& | RHS-Queue. |

### Rückgabewert

true, wenn die Queues-Größen und Daten übereinstimmen, sonst false.

## TestCompare::AreEqual(const SCG::QueuePtr\<SharedPtr\<T\>\>\&, const SCG::QueuePtr\<SharedPtr\<U\>\>\&) method


Vergleicht Queues von Zeigern.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<SharedPtr<T>> &queueA, const SCG::QueuePtr<SharedPtr<U>> &queueB)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | First queue pointee type. |
| U | Second queue pointee type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | LHS-Queue. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | RHS-Queue. |

### Rückgabewert

true, wenn die Queues-Größen und Daten übereinstimmen, sonst false.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<T\>\>\&, const SharedPtr\<SCG::Stack\<U\>\>\&) method


Vergleicht Stacks von Nicht-Pointern.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<T>> &stackA, const SharedPtr<SCG::Stack<U>> &stackB)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | First stack element type. |
| U | Second stack element type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<T\>\>\& | LHS-Stack. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<U\>\>\& | RHS-Stack. |

### Rückgabewert

true, wenn die Stacks-Größen und Daten übereinstimmen, sonst false.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::Stack\<SharedPtr\<U\>\>\>) method


Vergleicht Stacks von Zeigern.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<SharedPtr<T>>> &stackA, const SharedPtr<SCG::Stack<SharedPtr<U>>> &stackB)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | First stack pointee type. |
| U | Second stack pointee type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | LHS-Stack. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | RHS-Stack. |

### Rückgabewert

true, wenn die Stacks-Größen und Daten übereinstimmen, sonst false.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&) method


Vergleicht sortierte Dictionaries von Nicht-Pointer-zugeordneten Typen.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, U>> &dictA, const SharedPtr<SCG::SortedDictionary<K, U>> &dictB)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| K | Key type. |
| U | Mapped type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | LHS-Wörterbuch. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | RHS-Wörterbuch. |

### Rückgabewert

true, wenn die Dictionaries-Größen und Daten übereinstimmen, sonst false.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>) method


Vergleicht sortierte Dictionaries von Zeiger-zugeordneten Typen.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictB)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| K | Key type. |
| U | Mapped pointee type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | LHS-Wörterbuch. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | RHS-Wörterbuch. |

### Rückgabewert

true, wenn die Dictionaries-Größen und Daten übereinstimmen, sonst false.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K2, U2\>\>\&) method


Vergleicht sortierte Dictionaries unterschiedlicher Typen.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K1, U1>> &dictA, const SharedPtr<SCG::SortedDictionary<K2, U2>> &dictB)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| K1 | LHS dictionary key type. |
| U1 | LHS dictionary mapped type. |
| K2 | RHS dictionary key type. |
| U2 | RHS dictionary mapped type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K1, U1\>\>\& | LHS-Wörterbuch. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K2, U2\>\>\& | RHS-Wörterbuch. |

### Rückgabewert

Always returns false as type conversion is forbidden here.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, U\>\>\&, const SharedPtr\<SCG::SortedList\<K, U\>\>\&) method


Vergleicht sortierte Listen von Nicht-Pointer-zugeordneten Typen.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, U>> &dictA, const SharedPtr<SCG::SortedList<K, U>> &dictB)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| K | Key type. |
| U | Mapped type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | LHS-Liste. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | RHS-Liste. |

### Rückgabewert

true, wenn die Listen-Größen und Daten übereinstimmen, sonst false.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>) method


Vergleicht sortierte Listen von Zeiger-zugeordneten Typen.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictB)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| K | Key type. |
| U | Mapped pointee type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | LHS-Liste. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | RHS-Liste. |

### Rückgabewert

true, wenn die Listen-Größen und Daten übereinstimmen, sonst false.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedList\<K2, U2\>\>\&) method


Vergleicht sortierte Listen unterschiedlicher Typen.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K1, U1>> &dictA, const SharedPtr<SCG::SortedList<K2, U2>> &dictB)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| K1 | LHS list key type. |
| U1 | LHS list mapped type. |
| K2 | RHS list key type. |
| U2 | RHS list mapped type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K1, U1\>\>\& | LHS-Liste. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K2, U2\>\>\& | RHS-Liste. |

### Rückgabewert

Always returns false as type conversion is forbidden here.

## TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr\&, const System::Collections::Specialized::StringCollectionPtr\&) method


Vergleicht String-Collections.

```cpp
static bool System::TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr &arrA, const System::Collections::Specialized::StringCollectionPtr &arrB)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arrA | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | LHS-Collection. |
| arrB | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | RHS-Collection. |

### Rückgabewert

True, wenn die Größen und Daten übereinstimmen, sonst false.

## TestCompare::AreEqual(const System::SharedPtr\<SCG::IEnumerable\<T\>\>\&, const System::SharedPtr\<SCG::IEnumerable\<U\>\>\&) method


Vergleicht IEnumerable-Instanzen.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::SharedPtr<SCG::IEnumerable<T>> &et, const System::SharedPtr<SCG::IEnumerable<U>> &eu)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| et | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<T\>\>\& | LHS-enumerable object. |
| eu | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<U\>\>\& | RHS-enumerable object. |

### Rückgabewert

True, wenn die Größen und Daten übereinstimmen, sonst false.

## Siehe Auch

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [Array](../../array/)
* Klasse [List](../../../system.collections.generic/list/)
* Klasse [Dictionary](../../../system.collections.generic/dictionary/)
* Klasse [HashSet](../../../system.collections.generic/hashset/)
* Klasse [QueuePtr](../../../system.collections.generic/queueptr/)
* Klasse [Stack](../../../system.collections.generic/stack/)
* Klasse [SortedDictionary](../../../system.collections.generic/sorteddictionary/)
* Klasse [SortedList](../../../system.collections.generic/sortedlist/)
* Klasse [StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)
* Klasse [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struktur [TestCompare](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)