---
title: Get()
second_title: Riferimento API di Aspose.Slides per C++
description: Funzione per ottenere l'elemento N-esimo della tupla fornita. Sovraccarico per oggetto base.
type: docs
weight: 2406
url: /it/system/get/
---
## System::Get(const SharedPtr\<Object\>\&) funzione


Funzione per ottenere l'elemento N-esimo della tupla fornita. Sovraccarico per oggetto base.

```cpp
template<std::size_t> auto System::Get(const SharedPtr<Object> &object)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| N | indice dell'elemento. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | oggetto da ispezionare. |

### Valore di ritorno

value of N-th tuple element casted to object.

## System::Get(const T\&) funzione


Funzione per ottenere l'elemento N-esimo della tupla fornita. Sovraccarico per oggetti con metodo Deconstruct.

```cpp
template<std::size_t,typename T> auto System::Get(const T &object)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| N | indice dell'elemento. |
| T | type of inspected object. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| object | const T\& | oggetto da ispezionare. |

### Valore di ritorno

value of N-th tuple element.

## System::Get(const SharedPtr\<T\>\&) funzione


Funzione per ottenere l'elemento N-esimo della tupla fornita. Sovraccarico per puntatori condivisi.

```cpp
template<std::size_t,typename T> auto System::Get(const SharedPtr<T> &pointer)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| N | indice dell'elemento. |
| T | type of inspected object. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | oggetto da ispezionare. |

### Valore di ritorno

value of N-th tuple element.

## System::Get(T\&, const Index\&) funzione


Implementazione per espressioni collection[index].

```cpp
template<typename T> auto & System::Get(T &collection, const Index &index)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di collezione. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| collection | T\& | Oggetto della collezione. |
| index | const [Index](../index/)\& | Indice dell'elemento di tipo [System.Index](../index/). |

### Valore di ritorno

Collection element at the calculated offset.

## System::Get(T\&, const Range\&) funzione


Restituisce una fetta della collezione specificata definita dall'intervallo fornito.

```cpp
template<typename T> auto System::Get(T &collection, const Range &range)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| collection | T\& | La collezione da suddividere. |
| range | const [Range](../range/)\& | L'intervallo che specifica i limiti della fetta. |

### Valore di ritorno

Una vista o una fetta della collezione dall'offset di inizio calcolato e dalla lunghezza.

## System::Get(const ValueTuple\<Args...\>\&) funzione


Ottiene l'elemento N-esimo della tupla di valore.

```cpp
template<std::size_t,typename...> auto System::Get(const ValueTuple<Args...> &tuple)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| N | indice dell'elemento. |
| Args | tuple elements. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tuple | const [ValueTuple](../valuetuple/)\<Args...\>\& | tupla da cui ottenere l'elemento. |

### Valore di ritorno

value of N-th tuple element.

## Vedi anche

* Typedef [SharedPtr](../sharedptr/)
* Classe [Object](../object/)
* Classe [Index](../index/)
* Classe [Range](../range/)
* Classe [ValueTuple](../valuetuple/)
* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)