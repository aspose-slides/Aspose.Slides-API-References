---
title: Compare()
second_title: Referência da API Aspose.Slides para C++
description: Compara dois ponteiros inteligentes.
type: docs
weight: 1
url: /pt/system.memoryextensions.details/compare/
---
## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const SharedPtr\<U\>\&) função

Compara dois ponteiros inteligentes.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const SharedPtr<U> &b)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo do primeiro ponteiro inteligente |
| U | Tipo do segundo ponteiro inteligente |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Primeiro ponteiro inteligente |
| b | const [SharedPtr](../../system/sharedptr/)\<U\>\& | Segundo ponteiro inteligente |

### Valor de retorno

[Comparison](../../system/comparison/) resultado (0 se igual, -1 se a < b, 1 se a > b)

## System::MemoryExtensions::Details::Compare(const T\&, const T\&) função

Compara dois valores aritméticos.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::Compare(const T &a, const T &b)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo aritmético |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| a | const T\& | Primeiro valor |
| b | const T\& | Segundo valor |

### Valor de retorno

[Comparison](../../system/comparison/) resultado (0 se igual, -1 se a < b, 1 se a > b)

## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const U\&) função

Compara um ponteiro inteligente com um valor.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const U &b)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo apontado pelo ponteiro inteligente |
| U | Tipo do valor |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Ponteiro inteligente |
| b | const U\& | Valor |

### Valor de retorno

[Comparison](../../system/comparison/) resultado (0 se igual, -1 se a < b, 1 se a > b)

## Veja também

* Typedef [SharedPtr](../../system/sharedptr/)
* Espaço de nomes [System::MemoryExtensions::Details](../)
* Biblioteca [Aspose.Slides](../../)