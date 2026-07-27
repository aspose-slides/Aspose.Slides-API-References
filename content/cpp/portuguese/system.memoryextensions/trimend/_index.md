---
title: TrimEnd()
second_title: Referência de API do Aspose.Slides para C++
description: Remove o elemento especificado do final de um span tipado.
type: docs
weight: 378
url: /pt/system.memoryextensions/trimend/
---
## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const T\&) função

Remove o elemento especificado do final de um span tipado.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const T &trimElement)
```

### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span a ser reduzido |
| trimElement | const T\& | O elemento a ser removido |

### Valor de retorno

Um novo span com o elemento especificado removido do final

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const T\&) função

Remove o elemento especificado do final de um span tipado mutável.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const T &trimElement)
```

### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | O span mutável a ser reduzido |
| trimElement | const T\& | O elemento a ser removido |

### Valor de retorno

Um novo span com o elemento especificado removido do final

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) função

Remove os elementos especificados do final de um span tipado.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span a ser reduzido |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Os elementos a serem removidos |

### Valor de retorno

Um novo span com os elementos especificados removidos do final

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const ReadOnlySpan\<T\>\&) função

Remove os elementos especificados do final de um span tipado mutável.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | O span mutável a ser reduzido |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Os elementos a serem removidos |

### Valor de retorno

Um novo span com os elementos especificados removidos do final

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&) função

Remove caracteres de espaço em branco do final de um span de caracteres.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | O span de caracteres a ser reduzido |

### Valor de retorno

Um novo span com espaços em branco removidos do final

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&) função

Remove caracteres de espaço em branco do final de um span de caracteres mutável.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | O span de caracteres mutável a ser reduzido |

### Valor de retorno

Um novo span com espaços em branco removidos do final

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, char16_t) função

Remove o caractere especificado do final de um span de caracteres.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | O span de caracteres a ser reduzido |
| trimchar | char16_t | O caractere a ser removido |

### Valor de retorno

Um novo span com o caractere especificado removido do final

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, char16_t) função

Remove o caractere especificado do final de um span de caracteres mutável.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, char16_t trimchar)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | O span de caracteres mutável a ser reduzido |
| trimchar | char16_t | O caractere a ser removido |

### Valor de retorno

Um novo span com o caractere especificado removido do final

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) função

Remove os caracteres especificados do final de um span de caracteres.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimChars)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | O span de caracteres a ser reduzido |
| trimChars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Os caracteres a serem removidos |

### Valor de retorno

Um novo span com os caracteres especificados removidos do final

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) função

Remove os caracteres especificados do final de um span de caracteres mutável.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | O span de caracteres mutável a ser reduzido |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Os caracteres a serem removidos |

### Valor de retorno

Um novo span com os caracteres especificados removidos do final

## Ver também

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Espaço de nomes [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)