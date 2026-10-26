---
title: MakeArray()
second_title: Riferimento API di Aspose.Slides per C++
description: Una funzione di fabbrica che costruisce un nuovo oggetto Array, lo riempie con gli elementi della lista di inizializzazione specificata e restituisce un puntatore intelligente che punta all'oggetto Array.
type: docs
weight: 2029
url: /it/system/makearray/
---
## System::MakeArray(std::initializer_list\<T\>) funzione


Una funzione di fabbrica che costruisce un nuovo oggetto [Array](../array/), lo riempie con gli elementi della lista di inizializzazione specificata e restituisce un puntatore intelligente che punta all'oggetto [Array](../array/).

```cpp
template<typename T> ArrayPtr<T> System::MakeArray(std::initializer_list<T> init)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi dell'oggetto [Array](../array/) che la funzione costruisce |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| init | std::initializer_list\<T\> | La lista di inizializzazione contenente gli elementi con cui riempire l'array |

### Valore di ritorno

Un puntatore intelligente che punta all'oggetto [Array](../array/) costruito

## System::MakeArray(Args\&&...) funzione


Una funzione di fabbrica che costruisce un nuovo oggetto [Array](../array/) passando gli argomenti specificati al suo costruttore.

```cpp
template<class T,class...> ArrayPtr<T> System::MakeArray(Args &&... args)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi dell'oggetto [Array](../array/) che la funzione costruisce |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| args | Args\&&... | Gli argomenti che vengono passati al costruttore dell'oggetto [Array](../array/) in fase di costruzione |

### Valore di ritorno

Un puntatore intelligente che punta all'oggetto [Array](../array/) costruito

## System::MakeArray(Integral, Args\&&...) funzione


Una funzione di fabbrica che costruisce un nuovo oggetto [Array](../array/) passando gli argomenti specificati al suo costruttore.

```cpp
template<class T,class Integral,class...> std::enable_if<std::is_integral<Integral>::value, ArrayPtr<T>>::type System::MakeArray(Integral size, Args &&... args)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi dell'oggetto [Array](../array/) che la funzione costruisce |
| Integral | Tipo della dimensione dell'array. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size | Integral | Dimensione dell'array che viene creato. |
| args | Args\&&... | Gli argomenti che vengono passati al costruttore dell'oggetto [Array](../array/) in fase di costruzione |

### Valore di ritorno

Un puntatore intelligente che punta all'oggetto [Array](../array/) costruito

## Vedi anche

* Typedef [ArrayPtr](../arrayptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)