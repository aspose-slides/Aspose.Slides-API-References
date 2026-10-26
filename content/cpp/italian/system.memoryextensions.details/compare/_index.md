---
title: Compare()
second_title: Riferimento API di Aspose.Slides per C++
description: Confronta due smart pointer.
type: docs
weight: 1
url: /it/system.memoryextensions.details/compare/
---
## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const SharedPtr\<U\>\&) funzione

Confronta due smart pointer.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const SharedPtr<U> &b)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo del primo smart pointer |
| U | Tipo del secondo smart pointer |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Primo smart pointer |
| b | const [SharedPtr](../../system/sharedptr/)\<U\>\& | Secondo smart pointer |

### Valore restituito

[Comparison](../../system/comparison/) risultato (0 se uguale, -1 se a < b, 1 se a > b)

## System::MemoryExtensions::Details::Compare(const T\&, const T\&) funzione

Confronta due valori aritmetici.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::Compare(const T &a, const T &b)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo aritmetico |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | const T\& | Primo valore |
| b | const T\& | Secondo valore |

### Valore restituito

[Comparison](../../system/comparison/) risultato (0 se uguale, -1 se a < b, 1 se a > b)

## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const U\&) funzione

Confronta un smart pointer con un valore.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const U &b)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo puntato dal smart pointer |
| U | Tipo del valore |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Smart pointer |
| b | const U\& | Valore |

### Valore restituito

[Comparison](../../system/comparison/) risultato (0 se uguale, -1 se a < b, 1 se a > b)

## Vedi anche

* Typedef [SharedPtr](../../system/sharedptr/)
* Spazio dei nomi [System::MemoryExtensions::Details](../)
* Libreria [Aspose.Slides](../../)