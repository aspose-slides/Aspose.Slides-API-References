---
title: Copy()
second_title: Aspose.Slides para C++ Referência da API
description: Implementa a semântica public static void Copy(IntPtr source, byte[] destination, int startIndex, int length).
type: docs
weight: 1
url: /pt/system.runtime.interopservices/marshal/copy/
---
## Marshal::Copy(const IntPtr, container\&&, int, int) método

Implementa a semântica public static void Copy(IntPtr source, byte[] destination, int startIndex, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const IntPtr source, container &&destination, int startIndex, int length)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| container | Tipo de contêiner de destino. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | const IntPtr | Ponteiro de dados de origem. |
| destination | container\&& | Contêiner para copiar os dados. |
| startIndex | int | Índice inicial da origem. |
| length | int | Número de elementos a copiar. |

## Marshal::Copy(const void *, container\&&, int, int) método

Implementa a semântica public static void Copy(IntPtr source, byte[] destination, int startIndex, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const void *source, container &&destination, int startIndex, int length)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| container | Tipo de contêiner de destino. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | const void * | Ponteiro de dados de origem. |
| destination | container\&& | Contêiner para copiar os dados. |
| startIndex | int | Índice inicial da origem. |
| length | int | Número de elementos a copiar. |

## Marshal::Copy(const container\&, int, void *, int) método

Implementa public static void Copy(char[] source, int startIndex, IntPtr destination, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, void *destination, int length)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| container | Tipo de contêiner de origem. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | const container\& | Ponteiro de dados de origem. |
| startIndex | int | Índice inicial da origem. |
| destination | void * | Ponteiro de dados de destino. |
| length | int | Número de elementos a copiar. |

## Marshal::Copy(const container\&, int, IntPtr, int) método

Implementa public static void Copy(char[] source, int startIndex, IntPtr destination, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, IntPtr destination, int length)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| container | Tipo de contêiner de origem. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | const container\& | Ponteiro de dados de origem. |
| startIndex | int | Índice inicial da origem. |
| destination | IntPtr | Ponteiro de dados de destino. |
| length | int | Número de elementos a copiar. |

## Veja Também

* Classe [Marshal](../)
* Espaço de nomes [System::Runtime::InteropServices](../../)
* Biblioteca [Aspose.Slides](../../../)