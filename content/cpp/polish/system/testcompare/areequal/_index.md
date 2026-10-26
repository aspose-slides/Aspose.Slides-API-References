---
title: AreEqual()
second_title: Aspose.Slides dla C++ — dokumentacja API
description: Porównuje tablice nie będące wskaźnikami.
type: docs
weight: 1
url: /pl/system/testcompare/areequal/
---
## TestCompare::AreEqual(const SharedPtr\<Array\<T\>\>\&, const SharedPtr\<Array\<U\>\>\&) method


Porównuje tablice nie będące wskaźnikami.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<T>> &arrA, const SharedPtr<Array<U>> &arrB)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementu pierwszej tablicy. |
| U | Typ elementu drugiej tablicy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Tablica po lewej stronie. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<U\>\>\& | Tablica po prawej stronie. |

### Wartość zwracana

true, jeśli rozmiary tablic i dane są zgodne, w przeciwnym razie false.

## TestCompare::AreEqual(const SharedPtr\<Array\<SharedPtr\<T\>\>\>\&, const SharedPtr\<Array\<SharedPtr\<U\>\>\>\&) method


Porównuje tablice wskaźników.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<SharedPtr<T>>> &arrA, const SharedPtr<Array<SharedPtr<U>>> &arrB)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementu wskazywanego w pierwszej tablicy. |
| U | Typ elementu wskazywanego w drugiej tablicy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Tablica po lewej stronie. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Tablica po prawej stronie. |

### Wartość zwracana

true, jeśli rozmiary tablic i obiekty są zgodne, w przeciwnym razie false.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const SharedPtr\<SCG::List\<U\>\>\&) method


Porównuje listy nie będące wskaźnikami.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const SharedPtr<SCG::List<U>> &listB)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementu pierwszej listy. |
| U | Typ elementu drugiej listy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | Lista po lewej stronie. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | Lista po prawej stronie. |

### Wartość zwracana

true, jeśli rozmiary i dane list są zgodne, w przeciwnym razie false.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) method


Porównuje listy wskaźników.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &listA, const SharedPtr<SCG::List<SharedPtr<U>>> &listB)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementu wskazywanego w pierwszej liście. |
| U | Typ elementu wskazywanego w drugiej liście. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Lista po lewej stronie. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Lista po prawej stronie. |

### Wartość zwracana

true, jeśli rozmiary list i obiekty są zgodne, w przeciwnym razie false.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const System::ArrayPtr\<U\>\&) method


Porównuje listy z tablicami w przypadku elementów nie będących wskaźnikami.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const System::ArrayPtr<U> &arrB)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementu listy. |
| U | [Array](../../array/) typ elementu. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | Lista. |
| arrB | const [System::ArrayPtr](../../arrayptr/)\<U\>\& | [Array](../../array/). |

### Wartość zwracana

true, jeśli rozmiary i dane są zgodne, w przeciwnym razie false.

## TestCompare::AreEqual(const System::ArrayPtr\<T\>\&, const SharedPtr\<SCG::List\<U\>\>\&) method


Porównuje listy z tablicami w przypadku elementów nie będących wskaźnikami.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<T> &arrA, const SharedPtr<SCG::List<U>> &listB)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | [Array](../../array/) typ elementu. |
| U | Typ elementu listy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| arrA | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | [Array](../../array/). |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | Lista. |

### Wartość zwracana

true, jeśli rozmiary i dane są zgodne, w przeciwnym razie false.

## TestCompare::AreEqual(const System::ArrayPtr\<SharedPtr\<T\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) method


Porównuje listy z tablicami w przypadku elementów będących wskaźnikami.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<SharedPtr<T>> &arr, const SharedPtr<SCG::List<SharedPtr<U>>> &list)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | [Array](../../array/) typ elementu wskazywanego. |
| U | Typ elementu listy wskazywanego. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | [Array](../../array/). |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Lista. |

### Wartość zwracana

true, jeśli rozmiary i obiekty są zgodne, w przeciwnym razie false.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const System::ArrayPtr\<SharedPtr\<U\>\>\&) method


Porównuje listy z tablicami w przypadku elementów będących wskaźnikami.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &list, const System::ArrayPtr<SharedPtr<U>> &arr)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementu wskazywanego w liście. |
| U | [Array](../../array/) typ elementu wskazywanego. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Lista. |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | [Array](../../array/). |

### Wartość zwracana

true, jeśli rozmiary i obiekty są zgodne, w przeciwnym razie false.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, U\>\>\&, const SharedPtr\<SCG::Dictionary\<K, U\>\>\&) method


Porównuje słowniki niebędące wskaźnikami.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, U>> &dictA, const SharedPtr<SCG::Dictionary<K, U>> &dictB)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| K | Typ klucza. |
| U | Typ wartości. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | Słownik po lewej stronie. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | Słownik po prawej stronie. |

### Wartość zwracana

true, jeśli rozmiary słowników i dane są zgodne, w przeciwnym razie false.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>) method


Porównuje słowniki będące wskaźnikami.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictB)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| K | Typ klucza. |
| U | Typ elementu wskazywanego. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Słownik po lewej stronie. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Słownik po prawej stronie. |

### Wartość zwracana

true, jeśli rozmiary słowników i dane są zgodne, w przeciwnym razie false.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::Dictionary\<K2, U2\>\>\&) method


Porównuje słowniki różnych typów.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K1, U1>> &dictA, const SharedPtr<SCG::Dictionary<K2, U2>> &dictB)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| K1 | Typ klucza słownika po lewej stronie. |
| U1 | Typ wartości słownika po lewej stronie. |
| K2 | Typ klucza słownika po prawej stronie. |
| U2 | Typ wartości słownika po prawej stronie. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K1, U1\>\>\& | Słownik po lewej stronie. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K2, U2\>\>\& | Słownik po prawej stronie. |

### Wartość zwracana

Zawsze zwraca false, ponieważ konwersja typów jest tutaj zabroniona.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<T\>\>\&, const SharedPtr\<SCG::HashSet\<U\>\>\&) method


Porównuje zestawy hashset nie będące wskaźnikami.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<T>> &containerPtrA, const SharedPtr<SCG::HashSet<U>> &containerPtrB)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementu pierwszego hashsetu. |
| U | Typ elementu drugiego hashsetu. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| containerPtrA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<T\>\>\& | Hashset po lewej stronie. |
| containerPtrB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<U\>\>\& | Hashset po prawej stronie. |

### Wartość zwracana

true, jeśli rozmiary hashsetów i dane są zgodne, w przeciwnym razie false.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::HashSet\<SharedPtr\<U\>\>\>) method


Porównuje zestawy hashset będące wskaźnikami.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<SharedPtr<T>>> &contA, const SharedPtr<SCG::HashSet<SharedPtr<U>>> &contB)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementu wskazywanego w pierwszym hashsecie. |
| U | Typ elementu wskazywanego w drugim hashsecie. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| contA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Hashset po lewej stronie. |
| contB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Hashset po prawej stronie. |

### Wartość zwracana

true, jeśli rozmiary hashsetów i dane są zgodne, w przeciwnym razie false.

## TestCompare::AreEqual(const SCG::QueuePtr\<T\>\&, const SCG::QueuePtr\<U\>\&) method


Porównuje kolejki nie będące wskaźnikami.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<T> &queueA, const SCG::QueuePtr<U> &queueB)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementu pierwszej kolejki. |
| U | Typ elementu drugiej kolejki. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<T\>\& | Kolejka po lewej stronie. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<U\>\& | Kolejka po prawej stronie. |

### Wartość zwracana

true, jeśli rozmiary kolejek i dane są zgodne, w przeciwnym razie false.

## TestCompare::AreEqual(const SCG::QueuePtr\<SharedPtr\<T\>\>\&, const SCG::QueuePtr\<SharedPtr\<U\>\>\&) method


Porównuje kolejki będące wskaźnikami.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<SharedPtr<T>> &queueA, const SCG::QueuePtr<SharedPtr<U>> &queueB)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementu wskazywanego w pierwszej kolejce. |
| U | Typ elementu wskazywanego w drugiej kolejce. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | Kolejka po lewej stronie. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | Kolejka po prawej stronie. |

### Wartość zwracana

true, jeśli rozmiary kolejek i dane są zgodne, w przeciwnym razie false.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<T\>\>\&, const SharedPtr\<SCG::Stack\<U\>\>\&) method


Porównuje stosy nie będące wskaźnikami.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<T>> &stackA, const SharedPtr<SCG::Stack<U>> &stackB)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementu pierwszego stosu. |
| U | Typ elementu drugiego stosu. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<T\>\>\& | Stos po lewej stronie. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<U\>\>\& | Stos po prawej stronie. |

### Wartość zwracana

true, jeśli rozmiary stosów i dane są zgodne, w przeciwnym razie false.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::Stack\<SharedPtr\<U\>\>\>) method


Porównuje stosy będące wskaźnikami.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<SharedPtr<T>>> &stackA, const SharedPtr<SCG::Stack<SharedPtr<U>>> &stackB)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementu wskazywanego w pierwszym stosie. |
| U | Typ elementu wskazywanego w drugim stosie. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Stos po lewej stronie. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Stos po prawej stronie. |

### Wartość zwracana

true, jeśli rozmiary stosów i dane są zgodne, w przeciwnym razie false.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&) method


Porównuje posortowane słowniki nie będące wskaźnikami.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, U>> &dictA, const SharedPtr<SCG::SortedDictionary<K, U>> &dictB)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| K | Typ klucza. |
| U | Typ wartości. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | Słownik po lewej stronie. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | Słownik po prawej stronie. |

### Wartość zwracana

true, jeśli rozmiary słowników i dane są zgodne, w przeciwnym razie false.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>&, const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>) method


Porównuje posortowane słowniki będące wskaźnikami.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictB)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| K | Typ klucza. |
| U | Typ elementu wskazywanego. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Słownik po lewej stronie. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Słownik po prawej stronie. |

### Wartość zwracana

true, jeśli rozmiary słowników i dane są zgodne, w przeciwnym razie false.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K2, U2\>\>\&) method


Porównuje posortowane słowniki różnych typów.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K1, U1>> &dictA, const SharedPtr<SCG::SortedDictionary<K2, U2>> &dictB)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| K1 | Typ klucza słownika po lewej stronie. |
| U1 | Typ wartości słownika po lewej stronie. |
| K2 | Typ klucza słownika po prawej stronie. |
| U2 | Typ wartości słownika po prawej stronie. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K1, U1\>\>\& | Słownik po lewej stronie. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K2, U2\>\>\& | Słownik po prawej stronie. |

### Wartość zwracana

Zawsze zwraca false, ponieważ konwersja typów jest tutaj zabroniona.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, U\>\>\&, const SharedPtr\<SCG::SortedList\<K, U\>\>\&) method


Porównuje posortowane listy nie będące wskaźnikami.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, U>> &dictA, const SharedPtr<SCG::SortedList<K, U>> &dictB)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| K | Typ klucza. |
| U | Typ wartości. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | Lista po lewej stronie. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | Lista po prawej stronie. |

### Wartość zwracana

true, jeśli rozmiary list i dane są zgodne, w przeciwnym razie false.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>&, const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>) method


Porównuje posortowane listy będące wskaźnikami.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictB)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| K | Typ klucza. |
| U | Typ elementu wskazywanego. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Lista po lewej stronie. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Lista po prawej stronie. |

### Wartość zwracana

true, jeśli rozmiary list i dane są zgodne, w przeciwnym razie false.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedList\<K2, U2\>\>\&) method


Porównuje posortowane listy różnych typów.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K1, U1>> &dictA, const SharedPtr<SCG::SortedList<K2, U2>> &dictB)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| K1 | Typ klucza pierwszej listy. |
| U1 | Typ wartości pierwszej listy. |
| K2 | Typ klucza drugiej listy. |
| U2 | Typ wartości drugiej listy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K1, U1\>\>\& | Lista po lewej stronie. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K2, U2\>\>\& | Lista po prawej stronie. |

### Wartość zwracana

Zawsze zwraca false, ponieważ konwersja typów jest tutaj zabroniona.

## TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr\&, const System::Collections::Specialized::StringCollectionPtr\&) method


Porównuje kolekcje stringów.

```cpp
static bool System::TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr &arrA, const System::Collections::Specialized::StringCollectionPtr &arrB)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| arrA | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | Kolekcja po lewej stronie. |
| arrB | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | Kolekcja po prawej stronie. |

### Wartość zwracana

True, jeśli rozmiary i dane są zgodne, false otherwise.

## TestCompare::AreEqual(const System::SharedPtr\<SCG::IEnumerable\<T\>\>\&, const System::SharedPtr\<SCG::IEnumerable\<U\>\>\&) method


Porównuje instancje IEnumerable.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::SharedPtr<SCG::IEnumerable<T>> &et, const System::SharedPtr<SCG::IEnumerable<U>> &eu)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| et | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<T\>\>\& | Obiekt enumerable po lewej stronie. |
| eu | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<U\>\>\& | Obiekt enumerable po prawej stronie. |

### Wartość zwracana

True, jeśli rozmiary i dane są zgodne, false otherwise.

## Zobacz także

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