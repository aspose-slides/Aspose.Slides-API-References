---
title: AreEqual()
second_title: Aspose.Slides för C++ API-referens
description: Jämför arrayer av icke-pekare.
type: docs
weight: 1
url: /sv/system/testcompare/areequal/
---
## TestCompare::AreEqual(const SharedPtr\<Array\<T\>\>\&, const SharedPtr\<Array\<U\>\>\&) metod


Jämför arrayer av icke-pekare.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<T>> &arrA, const SharedPtr<Array<U>> &arrB)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Första array-elementtyp. |
| U | Andra array-elementtyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Vänster array. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<U\>\>\& | Höger array. |

### Returvärde

true om arraystorlekar och data matchar, false annars.

## TestCompare::AreEqual(const SharedPtr\<Array\<SharedPtr\<T\>\>\>\&, const SharedPtr\<Array\<SharedPtr\<U\>\>\>\&) metod


Jämför arrayer av pekare.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<SharedPtr<T>>> &arrA, const SharedPtr<Array<SharedPtr<U>>> &arrB)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Första array-pekartyp. |
| U | Andra array-pekartyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Vänster array. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Höger array. |

### Returvärde

true om arraystorlekar och objekt matchar, false annars.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const SharedPtr\<SCG::List\<U\>\>\&) metod


Jämför listor av icke-pekare.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const SharedPtr<SCG::List<U>> &listB)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Första listelementtyp. |
| U | Andra listelementtyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | Vänster lista. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | Höger lista. |

### Returvärde

true om storlekar och data matchar, false annars.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) metod


Jämför listor av pekare.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &listA, const SharedPtr<SCG::List<SharedPtr<U>>> &listB)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Första listpekartyp. |
| U | Andra listpekartyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Vänster lista. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Höger lista. |

### Returvärde

true om liststorlekar och objekt matchar, false annars.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const System::ArrayPtr\<U\>\&) metod


Jämför listor med arrayer i icke-pekarelement-fall.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const System::ArrayPtr<U> &arrB)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Listelementtyp. |
| U | [Array](../../array/) elementtyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | Lista. |
| arrB | const [System::ArrayPtr](../../arrayptr/)\<U\>\& | [Array](../../array/). |

### Returvärde

true om storlekar och data matchar, false annars.

## TestCompare::AreEqual(const System::ArrayPtr\<T\>\&, const SharedPtr\<SCG::List\<U\>\>\&) metod


Jämför listor med arrayer i icke-pekarelement-fall.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<T> &arrA, const SharedPtr<SCG::List<U>> &listB)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Array](../../array/) elementtyp. |
| U | Listelementtyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arrA | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | [Array](../../array/). |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | Lista. |

### Returvärde

true om storlekar och data matchar, false annars.

## TestCompare::AreEqual(const System::ArrayPtr\<SharedPtr\<T\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) metod


Jämför listor med arrayer i pekarelement-fall.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<SharedPtr<T>> &arr, const SharedPtr<SCG::List<SharedPtr<U>>> &list)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Array](../../array/) pekartyp. |
| U | Listpekartyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | [Array](../../array/). |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Lista. |

### Returvärde

true om storlekar och objekt matchar, false annars.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const System::ArrayPtr\<SharedPtr\<U\>\>\&) metod


Jämför listor med arrayer i pekarelement-fall.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &list, const System::ArrayPtr<SharedPtr<U>> &arr)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Listpekartyp. |
| U | [Array](../../array/) pekartyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Lista. |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | [Array](../../array/). |

### Returvärde

true om storlekar och objekt matchar, false annars.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, U\>\>\&, const SharedPtr\<SCG::Dictionary\<K, U\>\>\&) metod


Jämför ordböcker med icke-pekarmappade typer.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, U>> &dictA, const SharedPtr<SCG::Dictionary<K, U>> &dictB)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| K | Nyckeltyp. |
| U | Mappad typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | Vänster ordbok. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | Höger ordbok. |

### Returvärde

true om ordboksstorlekar och data matchar, false annars.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&) metod


Jämför ordböcker med pekarmappade typer.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictB)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| K | Nyckeltyp. |
| U | Mappad pekartyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Vänster ordbok. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Höger ordbok. |

### Returvärde

true om ordboksstorlekar och data matchar, false annars.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::Dictionary\<K2, U2\>\>\&) metod


Jämför ordböcker av olika typer.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K1, U1>> &dictA, const SharedPtr<SCG::Dictionary<K2, U2>> &dictB)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| K1 | Vänster ordboks nyckeltyp. |
| U1 | Vänster ordboks mappade typ. |
| K2 | Höger ordboks nyckeltyp. |
| U2 | Höger ordboks mappade typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K1, U1\>\>\& | Vänster ordbok. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K2, U2\>\>\& | Höger ordbok. |

### Returvärde

Alltid false eftersom typkonvertering är förbjuden här.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<T\>\>\&, const SharedPtr\<SCG::HashSet\<U\>\>\&) metod


Jämför hashset av icke-pekare.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<T>> &containerPtrA, const SharedPtr<SCG::HashSet<U>> &containerPtrB)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Första hashset-elementtyp. |
| U | Andra hashset-elementtyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| containerPtrA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<T\>\>\& | Vänster hashset. |
| containerPtrB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<U\>\>\& | Höger hashset. |

### Returvärde

true om hashset-storlekar och data matchar, false annars.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::HashSet\<SharedPtr\<U\>\>\>\&) metod


Jämför hashset av pekare.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<SharedPtr<T>>> &contA, const SharedPtr<SCG::HashSet<SharedPtr<U>>> &contB)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Första hashset-pekartyp. |
| U | Andra hashset-pekartyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| contA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Vänster hashset. |
| contB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Höger hashset. |

### Returvärde

true om hashset-storlekar och data matchar, false annars.

## TestCompare::AreEqual(const SCG::QueuePtr\<T\>\&, const SCG::QueuePtr\<U\>\&) metod


Jämför köer av icke-pekare.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<T> &queueA, const SCG::QueuePtr<U> &queueB)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Första kö-elementtyp. |
| U | Andra kö-elementtyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<T\>\& | Vänster kö. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<U\>\& | Höger kö. |

### Returvärde

true om kö-storlekar och data matchar, false annars.

## TestCompare::AreEqual(const SCG::QueuePtr\<SharedPtr\<T\>\>\&, const SCG::QueuePtr\<SharedPtr\<U\>\>\&) metod


Jämför köer av pekare.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<SharedPtr<T>> &queueA, const SCG::QueuePtr<SharedPtr<U>> &queueB)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Första kö-pekartyp. |
| U | Andra kö-pekartyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | Vänster kö. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | Höger kö. |

### Returvärde

true om kö-storlekar och data matchar, false annars.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<T\>\>\&, const SharedPtr\<SCG::Stack\<U\>\>\&) metod


Jämför stackar av icke-pekare.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<T>> &stackA, const SharedPtr<SCG::Stack<U>> &stackB)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Första stack-elementtyp. |
| U | Andra stack-elementtyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<T\>\>\& | Vänster stack. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<U\>\>\& | Höger stack. |

### Returvärde

true om stack-storlekar och data matchar, false annars.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::Stack\<SharedPtr\<U\>\>\>\&) metod


Jämför stackar av pekare.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<SharedPtr<T>>> &stackA, const SharedPtr<SCG::Stack<SharedPtr<U>>> &stackB)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Första stack-pekartyp. |
| U | Andra stack-pekartyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Vänster stack. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Höger stack. |

### Returvärde

true om stack-storlekar och data matchar, false annars.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&) metod


Jämför sorterade ordböcker av icke-pekarmappade typer.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, U>> &dictA, const SharedPtr<SCG::SortedDictionary<K, U>> &dictB)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| K | Nyckeltyp. |
| U | Mappad typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | Vänster ordbok. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | Höger ordbok. |

### Returvärde

true om ordboksstorlekar och data matchar, false annars.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&) metod


Jämför sorterade ordböcker av pekarmappade typer.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictB)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| K | Nyckeltyp. |
| U | Mappad pekartyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Vänster ordbok. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Höger ordbok. |

### Returvärde

true om ordboksstorlekar och data matchar, false annars.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K2, U2\>\>\&) metod


Jämför sorterade ordböcker av olika typer.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K1, U1>> &dictA, const SharedPtr<SCG::SortedDictionary<K2, U2>> &dictB)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| K1 | Vänster ordboks nyckeltyp. |
| U1 | Vänster ordboks mappade typ. |
| K2 | Höger ordboks nyckeltyp. |
| U2 | Höger ordboks mappade typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K1, U1\>\>\& | Vänster ordbok. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K2, U2\>\>\& | Höger ordbok. |

### Returvärde

Alltid false eftersom typkonvertering är förbjuden här.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, U\>\>\&, const SharedPtr\<SCG::SortedList\<K, U\>\>\&) metod


Jämför sorterade listor av icke-pekarmappade typer.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, U>> &dictA, const SharedPtr<SCG::SortedList<K, U>> &dictB)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| K | Nyckeltyp. |
| U | Mappad typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | Vänster lista. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | Höger lista. |

### Returvärde

true om list-storlekar och data matchar, false annars.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&) metod


Jämför sorterade listor av pekarmappade typer.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictB)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| K | Nyckeltyp. |
| U | Mappad pekartyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Vänster lista. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Höger lista. |

### Returvärde

true om list-storlekar och data matchar, false annars.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedList\<K2, U2\>\>\&) metod


Jämför sorterade listor av olika typer.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K1, U1>> &dictA, const SharedPtr<SCG::SortedList<K2, U2>> &dictB)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| K1 | Vänster list-nyckeltyp. |
| U1 | Vänster list-mappade typ. |
| K2 | Höger list-nyckeltyp. |
| U2 | Höger list-mappade typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K1, U1\>\>\& | Vänster lista. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K2, U2\>\>\& | Höger lista. |

### Returvärde

Alltid false eftersom typkonvertering är förbjuden här.

## TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr\&, const System::Collections::Specialized::StringCollectionPtr\&) metod


Jämför strängsamlingar.

```cpp
static bool System::TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr &arrA, const System::Collections::Specialized::StringCollectionPtr &arrB)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arrA | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | Vänster samling. |
| arrB | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | Höger samling. |

### Returvärde

True om storlekar och data matchar, false annars.

## TestCompare::AreEqual(const System::SharedPtr\<SCG::IEnumerable\<T\>\>\&, const System::SharedPtr\<SCG::IEnumerable\<U\>\>\&) metod


Jämför IEnumerable-instanser.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::SharedPtr<SCG::IEnumerable<T>> &et, const System::SharedPtr<SCG::IEnumerable<U>> &eu)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| et | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<T\>\>\& | Vänster enumerable-objekt. |
| eu | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<U\>\>\& | Höger enumerable-objekt. |

### Returvärde

True om storlekar och data matchar, false annars.

## Se även

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