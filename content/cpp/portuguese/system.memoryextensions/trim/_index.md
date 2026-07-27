---
title: Trim()
second_title: Referência da API Aspose.Slides para C++
description: Remove o elemento especificado de ambas as extremidades de um span tipado.
type: docs
weight: 365
url: /pt/system.memoryextensions/trim/
---
## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, T) função


Remove o elemento especificado de ambas as extremidades de um span tipado.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, T trimElement)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span a ser recortado |
| trimElement | T | O elemento a ser recortado |

### Valor de retorno

Um novo span com o elemento especificado removido de ambas as extremidades

## System::MemoryExtensions::Trim(Span\<T\>\&, T) função


Remove o elemento especificado de ambas as extremidades de um span tipado mutável.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, T trimElement)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | O span mutável a ser recortado |
| trimElement | T | O elemento a ser recortado |

### Valor de retorno

Um novo span com o elemento especificado removido de ambas as extremidades

## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) função


Remove os elementos especificados de ambas as extremidades de um span tipado.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span a ser recortado |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Os elementos a serem recortados |

### Valor de retorno

Um novo span com os elementos especificados removidos de ambas as extremidades

## System::MemoryExtensions::Trim(Span\<T\>\&, const ReadOnlySpan\<T\>\&) função


Remove os elementos especificados de ambas as extremidades de um span tipado mutável.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | O span mutável a ser recortado |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Os elementos a serem recortados |

### Valor de retorno

Um novo span com os elementos especificados removidos de ambas as extremidades

## System::MemoryExtensions::Trim(const ReadOnlySpan\<char16_t\>\&) função


Remove caracteres de espaço em branco de ambas as extremidades de um span de caracteres.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::Trim(const ReadOnlySpan<char16_t> &span)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | O span de caracteres a ser recortado |

### Valor de retorno

Um novo span com os espaços em branco removidos de ambas as extremidades

## System::MemoryExtensions::Trim(Span\<char16_t\>\&) função


Remove caracteres de espaço em branco de ambas as extremidades de um span de caracteres mutável.

```cpp
Span<char16_t> System::MemoryExtensions::Trim(Span<char16_t> &span)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | O span de caracteres mutável a ser recortado |

### Valor de retorno

Um novo span com os espaços em branco removidos de ambas as extremidades

## Veja também

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)