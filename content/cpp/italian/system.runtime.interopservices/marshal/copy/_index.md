---
title: Copy()
second_title: Riferimento API Aspose.Slides per C++
description: Implementa la semantica public static void Copy(IntPtr source, byte[] destination, int startIndex, int length).
type: docs
weight: 1
url: /it/system.runtime.interopservices/marshal/copy/
---
## Marshal::Copy(const IntPtr, container\&&, int, int) metodo

Implementa la semantica public static void Copy(IntPtr source, byte[] destination, int startIndex, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const IntPtr source, container &&destination, int startIndex, int length)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| container | Tipo di contenitore di destinazione. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | const IntPtr | Puntatore ai dati di origine. |
| destination | container\&& | Contenitore in cui copiare i dati. |
| startIndex | int | Indice iniziale della sorgente. |
| length | int | Numero di elementi da copiare. |

## Marshal::Copy(const void *, container\&&, int, int) metodo

Implementa la semantica public static void Copy(IntPtr source, byte[] destination, int startIndex, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const void *source, container &&destination, int startIndex, int length)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| container | Tipo di contenitore di destinazione. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | const void * | Puntatore ai dati di origine. |
| destination | container\&& | Contenitore in cui copiare i dati. |
| startIndex | int | Indice iniziale della sorgente. |
| length | int | Numero di elementi da copiare. |

## Marshal::Copy(const container\&, int, void *, int) metodo

Implementa la semantica public static void Copy(char[] source, int startIndex, IntPtr destination, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, void *destination, int length)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| container | Tipo di contenitore di origine. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | const container\& | Puntatore ai dati di origine. |
| startIndex | int | Indice iniziale della sorgente. |
| destination | void * | Puntatore ai dati di destinazione. |
| length | int | Numero di elementi da copiare. |

## Marshal::Copy(const container\&, int, IntPtr, int) metodo

Implementa la semantica public static void Copy(char[] source, int startIndex, IntPtr destination, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, IntPtr destination, int length)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| container | Tipo di contenitore di origine. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | const container\& | Puntatore ai dati di origine. |
| startIndex | int | Indice iniziale della sorgente. |
| destination | IntPtr | Puntatore ai dati di destinazione. |
| length | int | Numero di elementi da copiare. |

## Vedi anche

* Classe [Marshal](../)
* Spazio dei nomi [System::Runtime::InteropServices](../../)
* Libreria [Aspose.Slides](../../../)