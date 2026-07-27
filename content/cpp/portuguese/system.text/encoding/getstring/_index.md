---
title: GetString()
second_title: Referência da API Aspose.Slides para C++
description: Decodifica um buffer de bytes em uma string.
type: docs
weight: 313
url: /pt/system.text/encoding/getstring/
---
## Encoding::GetString(uint8_t *, int) método

Decodifica um buffer de bytes em uma string.

```cpp
virtual String System::Text::Encoding::GetString(uint8_t *bytes, int byte_count)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) para ler bytes de. |
| byte_count | int | Tamanho do buffer de entrada. |

### Valor de Retorno

[String](../../../system/string/) de caracteres decodificados.

## Encoding::GetString(const ReadOnlySpan\<uint8_t\>\&) método

Decodifica um buffer de bytes em uma string.

```cpp
String System::Text::Encoding::GetString(const ReadOnlySpan<uint8_t> &bytes)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | const [ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) para ler bytes de. |

### Valor de Retorno

[String](../../../system/string/) de caracteres decodificados.

## Encoding::GetString(ArrayPtr\<uint8_t\>) método

Decodifica um buffer de bytes em uma string.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) para ler bytes de. |

### Valor de Retorno

[String](../../../system/string/) de caracteres decodificados.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&) método

Decodifica um buffer de bytes em uma string.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) para ler bytes de. |

### Valor de Retorno

[String](../../../system/string/) de caracteres decodificados.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>\&) método

Decodifica um buffer de bytes em uma string.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> &bytes)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | [Buffer](../../../system/buffer/) para ler bytes de. |

### Valor de Retorno

[String](../../../system/string/) de caracteres decodificados.

## Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) método

Decodifica um buffer de bytes em uma string.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) para ler bytes de. |
| index | int | Deslocamento do buffer de entrada. |
| count | int | Tamanho do buffer de entrada. |

### Valor de Retorno

[String](../../../system/string/) de caracteres decodificados.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&, int, int) método

Decodifica um buffer de bytes em uma string.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes, int index, int count)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) para ler bytes de. |
| index | int | Deslocamento do buffer de entrada. |
| count | int | Tamanho do buffer de entrada. |

### Valor de Retorno

[String](../../../system/string/) de caracteres decodificados.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>, int, int) método

Decodifica um buffer de bytes em uma string.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> bytes, int index, int count)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\> | [Buffer](../../../system/buffer/) para ler bytes de. |
| index | int | Deslocamento do buffer de entrada. |
| count | int | Tamanho do buffer de entrada. |

### Valor de Retorno

[String](../../../system/string/) de caracteres decodificados.

## Ver Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [Encoding](../)
* Classe [ReadOnlySpan](../../../system/readonlyspan/)
* Namespace [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)