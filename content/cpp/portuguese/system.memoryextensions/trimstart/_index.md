---
title: TrimStart()
second_title: Referência da API Aspose.Slides para C++
description: Remove o elemento especificado do início de um span tipado.
type: docs
weight: 391
url: /pt/system.memoryextensions/trimstart/
---
## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const T\&) função

Remove o elemento especificado do início de um span tipado.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const T &trimElement)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span a ser reduzido |
| trimElement | const T\& | O elemento a ser removido |

### Valor de retorno

Um novo span com o elemento especificado removido do início

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const T\&) função

Remove o elemento especificado do início de um span tipado mutável.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const T &trimElement)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | O span mutável a ser reduzido |
| trimElement | const T\& | O elemento a ser removido |

### Valor de retorno

Um novo span com o elemento especificado removido do início

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) função

Remove os elementos especificados do início de um span tipado.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span a ser reduzido |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Os elementos a serem removidos |

### Valor de retorno

Um novo span com os elementos especificados removidos do início

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const ReadOnlySpan\<T\>\&) função

Remove os elementos especificados do início de um span tipado mutável.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | O span mutável a ser reduzido |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Os elementos a serem removidos |

### Valor de retorno

Um novo span com os elementos especificados removidos do início

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&) função

Remove caracteres de espaço em branco do início de um span de caracteres.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | O span de caracteres a ser reduzido |

### Valor de retorno

Um novo span com os espaços em branco removidos do início

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&) função

Remove caracteres de espaço em branco do início de um span de caracteres mutável.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | O span de caracteres mutável a ser reduzido |

### Valor de retorno

Um novo span com os espaços em branco removidos do início

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, char16_t) função

Remove o caractere especificado do início de um span de caracteres.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | O span de caracteres a ser reduzido |
| trimchar | char16_t | O caractere a ser removido |

### Valor de retorno

Um novo span com o caractere especificado removido do início

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, char16_t) função

Remove o caractere especificado do início de um span de caracteres mutável.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, char16_t trimchar)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | O span de caracteres mutável a ser reduzido |
| trimchar | char16_t | O caractere a ser removido |

### Valor de retorno

Um novo span com o caractere especificado removido do início

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) função

Remove os caracteres especificados do início de um span de caracteres.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | O span de caracteres a ser reduzido |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Os caracteres a serem removidos |

### Valor de retorno

Um novo span com os caracteres especificados removidos do início

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) função

Remove os caracteres especificados do início de um span de caracteres mutável.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | O span de caracteres mutável a ser reduzido |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Os caracteres a serem removidos |

### Valor de retorno

Um novo span com os caracteres especificados removidos do início

## Ver também

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)