---
title: AreEqual()
second_title: Aspose.Slides voor C++ API Referentie
description: Vergelijkt arrays van niet-pointers.
type: docs
weight: 1
url: /nl/system/testcompare/areequal/
---
## TestCompare::AreEqual(const SharedPtr\<Array\<T\>\>\&, const SharedPtr\<Array\<U\>\>\&) method

Vergelijkt arrays van niet-pointers.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<T>> &arrA, const SharedPtr<Array<U>> &arrB)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type van het eerste array-element. |
| U | Type van het tweede array-element. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | LHS-array. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<U\>\>\& | RHS-array. |

### Retourwaarde

true als de groottes en gegevens van de arrays overeenkomen, anders false.

## TestCompare::AreEqual(const SharedPtr\<Array\<SharedPtr\<T\>\>\>\&, const SharedPtr\<Array\<SharedPtr\<U\>\>\>\&) method

Vergelijkt arrays van pointers.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<SharedPtr<T>>> &arrA, const SharedPtr<Array<SharedPtr<U>>> &arrB)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type van het eerste array-element waarnaar wordt verwezen. |
| U | Type van het tweede array-element waarnaar wordt verwezen. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | LHS-array. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | RHS-array. |

### Retourwaarde

true als de groottes en objecten van de arrays overeenkomen, anders false.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const SharedPtr\<SCG::List\<U\>\>\&) method

Vergelijkt lijsten van niet-pointers.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const SharedPtr<SCG::List<U>> &listB)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type van het eerste lijst-element. |
| U | Type van het tweede lijst-element. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | LHS-lijst. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | RHS-lijst. |

### Retourwaarde

true als de groottes en gegevens van de lijsten overeenkomen, anders false.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) method

Vergelijkt lijsten van pointers.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &listA, const SharedPtr<SCG::List<SharedPtr<U>>> &listB)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type van het eerste lijst-object waarnaar wordt verwezen. |
| U | Type van het tweede lijst-object waarnaar wordt verwezen. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | LHS-lijst. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | RHS-lijst. |

### Retourwaarde

true als de groottes en objecten van de lijsten overeenkomen, anders false.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const System::ArrayPtr\<U\>\&) method

Vergelijkt lijsten met arrays in geval van elementen die geen pointers zijn.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const System::ArrayPtr<U> &arrB)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type van het lijst-element. |
| U | [Array](../../array/)-type van het element. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | Lijst. |
| arrB | const [System::ArrayPtr](../../arrayptr/)\<U\>\& | [Array](../../array/). |

### Retourwaarde

true als de groottes en gegevens overeenkomen, anders false.

## TestCompare::AreEqual(const System::ArrayPtr\<T\>\&, const SharedPtr\<SCG::List\<U\>\>\&) method

Vergelijkt lijsten met arrays in geval van elementen die geen pointers zijn.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<T> &arrA, const SharedPtr<SCG::List<U>> &listB)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | [Array](../../array/)-type van het element. |
| U | Type van het lijst-element. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arrA | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | [Array](../../array/). |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | Lijst. |

### Retourwaarde

true als de groottes en gegevens overeenkomen, anders false.

## TestCompare::AreEqual(const System::ArrayPtr\<SharedPtr\<T\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) method

Vergelijkt lijsten met arrays in geval van pointers.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<SharedPtr<T>> &arr, const SharedPtr<SCG::List<SharedPtr<U>>> &list)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | [Array](../../array/)-type van het object waarnaar wordt verwezen. |
| U | Type van het lijst-object waarnaar wordt verwezen. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | [Array](../../array/). |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Lijst. |

### Retourwaarde

true als de groottes en objecten overeenkomen, anders false.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const System::ArrayPtr\<SharedPtr\<U\>\>\&) method

Vergelijkt lijsten met arrays in geval van pointers.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &list, const System::ArrayPtr<SharedPtr<U>> &arr)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type van het lijst-object waarnaar wordt verwezen. |
| U | [Array](../../array/)-type van het object waarnaar wordt verwezen. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Lijst. |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | [Array](../../array/). |

### Retourwaarde

true als de groottes en objecten overeenkomen, anders false.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, U\>\>\&, const SharedPtr\<SCG::Dictionary\<K, U\>\>\&) method

Vergelijkt dictionaries van niet-pointer-gemapte typen.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, U>> &dictA, const SharedPtr<SCG::Dictionary<K, U>> &dictB)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| K | Sleuteltype. |
| U | Gemapt type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | LHS-dictionary. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | RHS-dictionary. |

### Retourwaarde

true als de groottes en gegevens van de dictionaries overeenkomen, anders false.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&) method

Vergelijkt dictionaries van pointers-gemapte typen.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictB)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| K | Sleuteltype. |
| U | Gemapt type waarnaar wordt verwezen. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | LHS-dictionary. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | RHS-dictionary. |

### Retourwaarde

true als de groottes en gegevens van de dictionaries overeenkomen, anders false.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::Dictionary\<K2, U2\>\>\&) method

Vergelijkt dictionaries van verschillende typen.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K1, U1>> &dictA, const SharedPtr<SCG::Dictionary<K2, U2>> &dictB)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| K1 | Sleuteltype van de LHS-dictionary. |
| U1 | Gemapt type van de LHS-dictionary. |
| K2 | Sleuteltype van de RHS-dictionary. |
| U2 | Gemapt type van de RHS-dictionary. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K1, U1\>\>\& | LHS-dictionary. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K2, U2\>\>\& | RHS-dictionary. |

### Retourwaarde

Altijd false, want type-conversie is hier verboden.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<T\>\>\&, const SharedPtr\<SCG::HashSet\<U\>\>\&) method

Vergelijkt hashsets van niet-pointers.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<T>> &containerPtrA, const SharedPtr<SCG::HashSet<U>> &containerPtrB)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type van het eerste hashset-element. |
| U | Type van het tweede hashset-element. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| containerPtrA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<T\>\>\& | LHS-hashset. |
| containerPtrB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<U\>\>\& | RHS-hashset. |

### Retourwaarde

true als de groottes en gegevens van de hashsets overeenkomen, anders false.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::HashSet\<SharedPtr\<U\>\>\>\&) method

Vergelijkt hashsets van pointers.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<SharedPtr<T>>> &contA, const SharedPtr<SCG::HashSet<SharedPtr<U>>> &contB)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type van het eerste hashset-object waarnaar wordt verwezen. |
| U | Type van het tweede hashset-object waarnaar wordt verwezen. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| contA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | LHS-hashset. |
| contB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | RHS-hashset. |

### Retourwaarde

true als de groottes en gegevens van de hashsets overeenkomen, anders false.

## TestCompare::AreEqual(const SCG::QueuePtr\<T\>\&, const SCG::QueuePtr\<U\>\&) method

Vergelijkt wachtrijen van niet-pointers.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<T> &queueA, const SCG::QueuePtr<U> &queueB)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type van het eerste wachtrij-element. |
| U | Type van het tweede wachtrij-element. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<T\>\& | LHS-wachtrij. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<U\>\& | RHS-wachtrij. |

### Retourwaarde

true als de groottes en gegevens van de wachtrijen overeenkomen, anders false.

## TestCompare::AreEqual(const SCG::QueuePtr\<SharedPtr\<T\>\>\&, const SCG::QueuePtr\<SharedPtr\<U\>\>\&) method

Vergelijkt wachtrijen van pointers.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<SharedPtr<T>> &queueA, const SCG::QueuePtr<SharedPtr<U>> &queueB)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type van het eerste wachtrij-object waarnaar wordt verwezen. |
| U | Type van het tweede wachtrij-object waarnaar wordt verwezen. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | LHS-wachtrij. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | RHS-wachtrij. |

### Retourwaarde

true als de groottes en gegevens van de wachtrijen overeenkomen, anders false.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<T\>\>\&, const SharedPtr\<SCG::Stack\<U\>\>\&) method

Vergelijkt stacks van niet-pointers.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<T>> &stackA, const SharedPtr<SCG::Stack<U>> &stackB)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type van het eerste stack-element. |
| U | Type van het tweede stack-element. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<T\>\>\& | LHS-stack. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<U\>\>\& | RHS-stack. |

### Retourwaarde

true als de groottes en gegevens van de stacks overeenkomen, anders false.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::Stack\<SharedPtr\<U\>\>\>\&) method

Vergelijkt stacks van pointers.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<SharedPtr<T>>> &stackA, const SharedPtr<SCG::Stack<SharedPtr<U>>> &stackB)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type van het eerste stack-object waarnaar wordt verwezen. |
| U | Type van het tweede stack-object waarnaar wordt verwezen. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | LHS-stack. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | RHS-stack. |

### Retourwaarde

true als de groottes en gegevens van de stacks overeenkomen, anders false.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&) method

Vergelijkt gesorteerde dictionaries van niet-pointer-gemapte typen.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, U>> &dictA, const SharedPtr<SCG::SortedDictionary<K, U>> &dictB)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| K | Sleuteltype. |
| U | Gemapt type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | LHS-dictionary. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | RHS-dictionary. |

### Retourwaarde

true als de groottes en gegevens van de dictionaries overeenkomen, anders false.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&) method

Vergelijkt gesorteerde dictionaries van pointer-gemapte typen.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictB)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| K | Sleuteltype. |
| U | Gemapt type waarnaar wordt verwezen. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | LHS-dictionary. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | RHS-dictionary. |

### Retourwaarde

true als de groottes en gegevens van de dictionaries overeenkomen, anders false.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K2, U2\>\>\&) method

Vergelijkt gesorteerde dictionaries van verschillende typen.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K1, U1>> &dictA, const SharedPtr<SCG::SortedDictionary<K2, U2>> &dictB)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| K1 | Sleuteltype van de LHS-dictionary. |
| U1 | Gemapt type van de LHS-dictionary. |
| K2 | Sleuteltype van de RHS-dictionary. |
| U2 | Gemapt type van de RHS-dictionary. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K1, U1\>\>\& | LHS-dictionary. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K2, U2\>\>\& | RHS-dictionary. |

### Retourwaarde

Altijd false, want type-conversie is hier verboden.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, U\>\>\&, const SharedPtr\<SCG::SortedList\<K, U\>\>\&) method

Vergelijkt gesorteerde lijsten van niet-pointer-gemapte typen.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, U>> &dictA, const SharedPtr<SCG::SortedList<K, U>> &dictB)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| K | Sleuteltype. |
| U | Gemapt type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | LHS-lijst. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | RHS-lijst. |

### Retourwaarde

true als de groottes en gegevens van de lijsten overeenkomen, anders false.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&) method

Vergelijkt gesorteerde lijsten van pointer-gemapte typen.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictB)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| K | Sleuteltype. |
| U | Gemapt type waarnaar wordt verwezen. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | LHS-lijst. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | RHS-lijst. |

### Retourwaarde

true als de groottes en gegevens van de lijsten overeenkomen, anders false.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedList\<K2, U2\>\>\&) method

Vergelijkt gesorteerde lijsten van verschillende typen.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K1, U1>> &dictA, const SharedPtr<SCG::SortedList<K2, U2>> &dictB)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| K1 | Sleuteltype van de LHS-lijst. |
| U1 | Gemapt type van de LHS-lijst. |
| K2 | Sleuteltype van de RHS-lijst. |
| U2 | Gemapt type van de RHS-lijst. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K1, U1\>\>\& | LHS-lijst. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K2, U2\>\>\& | RHS-lijst. |

### Retourwaarde

Altijd false, want type-conversie is hier verboden.

## TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr\&, const System::Collections::Specialized::StringCollectionPtr\&) method

Vergelijkt string-collecties.

```cpp
static bool System::TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr &arrA, const System::Collections::Specialized::StringCollectionPtr &arrB)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arrA | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | LHS-collectie. |
| arrB | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | RHS-collectie. |

### Retourwaarde

True als de groottes en gegevens overeenkomen, anders false.

## TestCompare::AreEqual(const System::SharedPtr\<SCG::IEnumerable\<T\>\>\&, const System::SharedPtr\<SCG::IEnumerable\<U\>\>\&) method

Vergelijkt IEnumerable-instanties.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::SharedPtr<SCG::IEnumerable<T>> &et, const System::SharedPtr<SCG::IEnumerable<U>> &eu)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| et | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<T\>\>\& | LHS-enumerable-object. |
| eu | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<U\>\>\& | RHS-enumerable-object. |

### Retourwaarde

True als de groottes en gegevens overeenkomen, anders false.

## See Also

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