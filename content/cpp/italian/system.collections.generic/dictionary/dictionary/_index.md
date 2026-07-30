---
title: Dictionary()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un dizionario vuoto.
type: docs
weight: 1
url: /it/system.collections.generic/dictionary/dictionary/
---
## Dictionary::Dictionary() costruttore

Crea un dizionario vuoto.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary()
```

## Dictionary::Dictionary(const map_t\&) costruttore

Copia i dati dalla mappa.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const map_t &map)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | Mappa da cui copiare i dati. |

## Dictionary::Dictionary(int) costruttore

Sovraccarico che corrisponde alla creazione di un dizionario preallocato; in realtà non esegue alcuna allocazione.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| capacity | int | Capacità da allocare; ignorata. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) costruttore

Costruttore di copia.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../) da cui copiare i dati. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) costruttore

Costruttore di copia.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | Dizionario sorgente. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) oggetto da utilizzare. |

## Dictionary::Dictionary(const SharedPtr\<IEqualityComparer\<TKey\>\>\&) costruttore

Crea un dizionario vuoto.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) da utilizzare. |

## Dictionary::Dictionary(int, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) costruttore

Crea un dizionario vuoto.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| capacity | int | [Dictionary](../) capacità dopo la creazione; ignorata. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) da utilizzare. |

## Vedi anche

* Typedef [map_t](../map_t/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Dictionary](../)
* Classe [IDictionary](../../idictionary/)
* Classe [IEqualityComparer](../../iequalitycomparer/)
* Spazio dei nomi [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)