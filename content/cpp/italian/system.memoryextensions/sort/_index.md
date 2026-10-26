---
title: Sort()
second_title: Riferimento API di Aspose.Slides per C++
description: Ordina uno Span usando un comparatore personalizzato.
type: docs
weight: 339
url: /it/system.memoryextensions/sort/
---
## System::MemoryExtensions::Sort(const Span\<T\>\&, const SharedPtr\<TComparer\>\&) funzione


Ordina un [Span](../../system/span/) usando un comparatore personalizzato.

```cpp
template<typename T,typename TComparer> void System::MemoryExtensions::Sort(const Span<T> &span, const SharedPtr<TComparer> &comparer)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |
| TComparer | Il tipo dell'oggetto comparatore |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span da ordinare |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Puntatore intelligente all'oggetto comparatore per il confronto degli elementi |

## System::MemoryExtensions::Sort(Span\<T\>\&) funzione


Ordina un [Span](../../system/span/) usando il confronto predefinito.

```cpp
template<typename T> void System::MemoryExtensions::Sort(Span<T> &span)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Lo span da ordinare |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, const SharedPtr\<TComparer\>\&) funzione


Ordina coppie chiave-valore usando un comparatore personalizzato (chiavi e valori ordinati insieme)

```cpp
template<typename TKey,typename TValue,typename TComparer> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, const SharedPtr<TComparer> &comparer)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TKey | Il tipo delle chiavi |
| TValue | Il tipo dei valori |
| TComparer | Il tipo dell'oggetto comparatore |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Lo span delle chiavi da ordinare |
| values | [Span](../../system/span/)\<TValue\>\& | Lo span dei valori da ordinare (mantenendo la corrispondenza con le chiavi) |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Puntatore intelligente all'oggetto comparatore per il confronto delle chiavi |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, System::Comparison\<TKey\>) funzione


Ordina coppie chiave-valore usando un delegato di confronto.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, System::Comparison<TKey> comparer)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TKey | Il tipo delle chiavi |
| TValue | Il tipo dei valori |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Lo span delle chiavi da ordinare |
| values | [Span](../../system/span/)\<TValue\>\& | Lo span dei valori da ordinare |
| comparer | [System::Comparison](../../system/comparison/)\<TKey\> | [Comparison](../../system/comparison/) delegato per il confronto delle chiavi |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&) funzione


Ordina coppie chiave-valore usando il confronto predefinito.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TKey | Il tipo delle chiavi |
| TValue | Il tipo dei valori |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Lo span delle chiavi da ordinare |
| values | [Span](../../system/span/)\<TValue\>\& | Lo span dei valori da ordinare |

## Vedi anche

* Typedef [SharedPtr](../../system/sharedptr/)
* Classe [Span](../../system/span/)
* Classe [Comparison](../../system/comparison/)
* Namespace [System::MemoryExtensions](../)
* Libreria [Aspose.Slides](../../)