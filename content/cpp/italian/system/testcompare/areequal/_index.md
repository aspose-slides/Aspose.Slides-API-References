---
title: AreEqual()
second_title: Riferimento API di Aspose.Slides per C++
description: Confronta array di non-puntatori.
type: docs
weight: 1
url: /it/system/testcompare/areequal/
---
## TestCompare::AreEqual(const SharedPtr\<Array\<T\>\>\&, const SharedPtr\<Array\<U\>\>\&) metodo

Confronta array di non puntatori.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<T>> &arrA, const SharedPtr<Array<U>> &arrB)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo del primo elemento dell'array. |
| U | Tipo del secondo elemento dell'array. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Array LHS. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<U\>\>\& | Array RHS. |

### Valore di ritorno

true se le dimensioni e i dati corrispondono, false altrimenti.

## TestCompare::AreEqual(const SharedPtr\<Array\<SharedPtr\<T\>\>\>\&, const SharedPtr\<Array\<SharedPtr\<U\>\>\>\&) metodo

Confronta array di puntatori.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<SharedPtr<T>>> &arrA, const SharedPtr<Array<SharedPtr<U>>> &arrB)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo del primo elemento puntato dell'array. |
| U | Tipo del secondo elemento puntato dell'array. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Array LHS. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Array RHS. |

### Valore di ritorno

true se le dimensioni e gli oggetti corrispondono, false altrimenti.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const SharedPtr\<SCG::List\<U\>\>\&) metodo

Confronta liste di non puntatori.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const SharedPtr<SCG::List<U>> &listB)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo del primo elemento della lista. |
| U | Tipo del secondo elemento della lista. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | Lista LHS. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | Lista RHS. |

### Valore di ritorno

true se le dimensioni e i dati corrispondono, false altrimenti.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) metodo

Confronta liste di puntatori.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &listA, const SharedPtr<SCG::List<SharedPtr<U>>> &listB)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo del primo elemento puntato della lista. |
| U | Tipo del secondo elemento puntato della lista. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Lista LHS. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Lista RHS. |

### Valore di ritorno

true se le dimensioni e gli oggetti corrispondono, false altrimenti.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const System::ArrayPtr\<U\>\&) metodo

Confronta liste con array nel caso di elementi non puntatori.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const System::ArrayPtr<U> &arrB)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo dell'elemento della lista. |
| U | [Array](../../array/) tipo dell'elemento. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | Lista. |
| arrB | const [System::ArrayPtr](../../arrayptr/)\<U\>\& | [Array](../../array/). |

### Valore di ritorno

true se le dimensioni e i dati corrispondono, false altrimenti.

## TestCompare::AreEqual(const System::ArrayPtr\<T\>\&, const SharedPtr\<SCG::List\<U\>\>\&) metodo

Confronta liste con array nel caso di elementi non puntatori.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<T> &arrA, const SharedPtr<SCG::List<U>> &listB)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | [Array](../../array/) tipo dell'elemento. |
| U | Tipo dell'elemento della lista. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arrA | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | [Array](../../array/). |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | Lista. |

### Valore di ritorno

true se le dimensioni e i dati corrispondono, false altrimenti.

## TestCompare::AreEqual(const System::ArrayPtr\<SharedPtr\<T\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) metodo

Confronta liste con array nel caso di elementi puntatori.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<SharedPtr<T>> &arr, const SharedPtr<SCG::List<SharedPtr<U>>> &list)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | [Array](../../array/) tipo puntato. |
| U | Tipo puntato della lista. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | [Array](../../array/). |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Lista. |

### Valore di ritorno

true se le dimensioni e gli oggetti corrispondono, false altrimenti.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const System::ArrayPtr\<SharedPtr\<U\>\>\&) metodo

Confronta liste con array nel caso di elementi puntatori.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &list, const System::ArrayPtr<SharedPtr<U>> &arr)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo puntato della lista. |
| U | [Array](../../array/) tipo puntato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Lista. |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | [Array](../../array/). |

### Valore di ritorno

true se le dimensioni e gli oggetti corrispondono, false altrimenti.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, U\>\>\&, const SharedPtr\<SCG::Dictionary\<K, U\>\>\&) metodo

Confronta dizionari di tipi mappati non puntatore.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, U>> &dictA, const SharedPtr<SCG::Dictionary<K, U>> &dictB)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| K | Tipo della chiave. |
| U | Tipo mappato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | Dizionario LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | Dizionario RHS. |

### Valore di ritorno

true se le dimensioni e i dati corrispondono, false altrimenti.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>) metodo

Confronta dizionari di tipi mappati puntatore.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictB)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| K | Tipo della chiave. |
| U | Tipo puntato mappato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Dizionario LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Dizionario RHS. |

### Valore di ritorno

true se le dimensioni e i dati corrispondono, false altrimenti.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::Dictionary\<K2, U2\>\>\&) metodo

Confronta dizionari di tipi diversi.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K1, U1>> &dictA, const SharedPtr<SCG::Dictionary<K2, U2>> &dictB)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| K1 | Tipo della chiave del dizionario LHS. |
| U1 | Tipo mappato del dizionario LHS. |
| K2 | Tipo della chiave del dizionario RHS. |
| U2 | Tipo mappato del dizionario RHS. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K1, U1\>\>\& | Dizionario LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K2, U2\>\>\& | Dizionario RHS. |

### Valore di ritorno

Restituisce sempre false poiché la conversione di tipo è vietata qui.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<T\>\>\&, const SharedPtr\<SCG::HashSet\<U\>\>\&) metodo

Confronta hashset di non puntatori.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<T>> &containerPtrA, const SharedPtr<SCG::HashSet<U>> &containerPtrB)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo del primo elemento dell'hashset. |
| U | Tipo del secondo elemento dell'hashset. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| containerPtrA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<T\>\>\& | Hashset LHS. |
| containerPtrB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<U\>\>\& | Hashset RHS. |

### Valore di ritorno

true se le dimensioni e i dati corrispondono, false altrimenti.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::HashSet\<SharedPtr\<U\>\>\>\&) metodo

Confronta hashset di puntatori.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<SharedPtr<T>>> &contA, const SharedPtr<SCG::HashSet<SharedPtr<U>>> &contB)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo del primo elemento puntato dell'hashset. |
| U | Tipo del secondo elemento puntato dell'hashset. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Hashset LHS. |
| contB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Hashset RHS. |

### Valore di ritorno

true se le dimensioni e i dati corrispondono, false altrimenti.

## TestCompare::AreEqual(const SCG::QueuePtr\<T\>\&, const SCG::QueuePtr\<U\>\&) metodo

Confronta code di non puntatori.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<T> &queueA, const SCG::QueuePtr<U> &queueB)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo del primo elemento della coda. |
| U | Tipo del secondo elemento della coda. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<T\>\& | Coda LHS. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<U\>\& | Coda RHS. |

### Valore di ritorno

true se le dimensioni e i dati corrispondono, false altrimenti.

## TestCompare::AreEqual(const SCG::QueuePtr\<SharedPtr\<T\>\>\&, const SCG::QueuePtr\<SharedPtr\<U\>\>\&) metodo

Confronta code di puntatori.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<SharedPtr<T>> &queueA, const SCG::QueuePtr<SharedPtr<U>> &queueB)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo del primo elemento puntato della coda. |
| U | Tipo del secondo elemento puntato della coda. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | Coda LHS. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | Coda RHS. |

### Valore di ritorno

true se le dimensioni e i dati corrispondono, false altrimenti.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<T\>\>\&, const SharedPtr\<SCG::Stack\<U\>\>\&) metodo

Confronta stack di non puntatori.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<T>> &stackA, const SharedPtr<SCG::Stack<U>> &stackB)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo del primo elemento dello stack. |
| U | Tipo del secondo elemento dello stack. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<T\>\>\& | Stack LHS. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<U\>\>\& | Stack RHS. |

### Valore di ritorno

true se le dimensioni e i dati corrispondono, false altrimenti.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::Stack\<SharedPtr\<U\>\>\>\&) metodo

Confronta stack di puntatori.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<SharedPtr<T>>> &stackA, const SharedPtr<SCG::Stack<SharedPtr<U>>> &stackB)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo del primo elemento puntato dello stack. |
| U | Tipo del secondo elemento puntato dello stack. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Stack LHS. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Stack RHS. |

### Valore di ritorno

true se le dimensioni e i dati corrispondono, false altrimenti.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&) metodo

Confronta dizionari ordinati di tipi mappati non puntatore.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, U>> &dictA, const SharedPtr<SCG::SortedDictionary<K, U>> &dictB)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| K | Tipo della chiave. |
| U | Tipo mappato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | Dizionario LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | Dizionario RHS. |

### Valore di ritorno

true se le dimensioni e i dati corrispondono, false altrimenti.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>) metodo

Confronta dizionari ordinati di tipi mappati puntatore.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictB)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| K | Tipo della chiave. |
| U | Tipo puntato mappato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Dizionario LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Dizionario RHS. |

### Valore di ritorno

true se le dimensioni e i dati corrispondono, false altrimenti.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K2, U2\>\>\&) metodo

Confronta dizionari ordinati di tipi diversi.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K1, U1>> &dictA, const SharedPtr<SCG::SortedDictionary<K2, U2>> &dictB)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| K1 | Tipo della chiave del dizionario LHS. |
| U1 | Tipo mappato del dizionario LHS. |
| K2 | Tipo della chiave del dizionario RHS. |
| U2 | Tipo mappato del dizionario RHS. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K1, U1\>\>\& | Dizionario LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K2, U2\>\>\& | Dizionario RHS. |

### Valore di ritorno

Restituisce sempre false poiché la conversione di tipo è vietata qui.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, U\>\>\&, const SharedPtr\<SCG::SortedList\<K, U\>\>\&) metodo

Confronta liste ordinate di tipi mappati non puntatore.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, U>> &dictA, const SharedPtr<SCG::SortedList<K, U>> &dictB)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| K | Tipo della chiave. |
| U | Tipo mappato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | Lista LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | Lista RHS. |

### Valore di ritorno

true se le dimensioni e i dati corrispondono, false altrimenti.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>) metodo

Confronta liste ordinate di tipi mappati puntatore.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictB)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| K | Tipo della chiave. |
| U | Tipo puntato mappato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Lista LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Lista RHS. |

### Valore di ritorno

true se le dimensioni e i dati corrispondono, false altrimenti.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedList\<K2, U2\>\>\&) metodo

Confronta liste ordinate di tipi diversi.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K1, U1>> &dictA, const SharedPtr<SCG::SortedList<K2, U2>> &dictB)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| K1 | Tipo della chiave della lista LHS. |
| U1 | Tipo mappato della lista LHS. |
| K2 | Tipo della chiave della lista RHS. |
| U2 | Tipo mappato della lista RHS. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K1, U1\>\>\& | Lista LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K2, U2\>\>\& | Lista RHS. |

### Valore di ritorno

Restituisce sempre false poiché la conversione di tipo è vietata qui.

## TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr\&, const System::Collections::Specialized::StringCollectionPtr\&) metodo

Confronta collezioni di stringhe.

```cpp
static bool System::TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr &arrA, const System::Collections::Specialized::StringCollectionPtr &arrB)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arrA | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | Collezione LHS. |
| arrB | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | Collezione RHS. |

### Valore di ritorno

true se le dimensioni e i dati corrispondono, false altrimenti.

## TestCompare::AreEqual(const System::SharedPtr\<SCG::IEnumerable\<T\>\>\&, const System::SharedPtr\<SCG::IEnumerable\<U\>\>\&) metodo

Confronta istanze di IEnumerable.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::SharedPtr<SCG::IEnumerable<T>> &et, const System::SharedPtr<SCG::IEnumerable<U>> &eu)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| et | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<T\>\>\& | Oggetto enumerable LHS. |
| eu | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<U\>\>\& | Oggetto enumerable RHS. |

### Valore di ritorno

true se le dimensioni e i dati corrispondono, false altrimenti.

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Classe [Array](../../array/)
* Classe [List](../../../system.collections.generic/list/)
* Classe [Dictionary](../../../system.collections.generic/dictionary/)
* Classe [HashSet](../../../system.collections.generic/hashset/)
* Classe [QueuePtr](../../../system.collections.generic/queueptr/)
* Classe [Stack](../../../system.collections.generic/stack/)
* Classe [SortedDictionary](../../../system.collections.generic/sorteddictionary/)
* Classe [SortedList](../../../system.collections.generic/sortedlist/)
* Classe [StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)
* Classe [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struttura [TestCompare](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)