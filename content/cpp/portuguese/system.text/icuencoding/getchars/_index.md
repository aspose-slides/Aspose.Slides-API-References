---
title: GetChars()
second_title: Referência da API Aspose.Slides para C++
description: Obtém os caracteres que resultam da decodificação de um buffer de bytes.
type: docs
weight: 66
url: /pt/system.text/icuencoding/getchars/
---
## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) method

Obtém os caracteres resultantes da decodificação de um buffer de bytes.

```cpp
int System::Text::ICUEncoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) para ler bytes de. |
| byte_count | int | Tamanho do buffer de entrada. |
| chars | char_t * | [Buffer](../../../system/buffer/) para gravar os caracteres. |
| char_count | int | Tamanho do buffer de saída. |

### Valor de Retorno

Número de caracteres gravados.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) method

Obtém os caracteres resultantes da decodificação de um buffer de bytes.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) para ler bytes de. |
| byte_index | int | Deslocamento do buffer de entrada. |
| byte_count | int | Tamanho do buffer de entrada. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) para gravar os caracteres. |
| char_index | int | Deslocamento do buffer de saída. |

### Valor de Retorno

Número de caracteres gravados.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int) method

Obtém os caracteres resultantes da decodificação de um buffer de bytes.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) para ler bytes de. |
| index | int | Deslocamento do buffer de entrada. |
| count | int | Tamanho do buffer de entrada. |

### Valor de Retorno

[Buffer](../../../system/buffer/) de caracteres decodificados.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>) method

Obtém os caracteres resultantes da decodificação de um buffer de bytes.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) para ler bytes de. |

### Valor de Retorno

[Buffer](../../../system/buffer/) de caracteres decodificados.

## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) method

Obtém os caracteres resultantes da decodificação de um buffer de bytes.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) para ler bytes de. |
| byte_count | int | Tamanho do buffer de entrada. |
| chars | char_t * | [Buffer](../../../system/buffer/) para gravar os caracteres. |
| char_count | int | Tamanho do buffer de saída. |

### Valor de Retorno

Número de caracteres gravados.

## Ver Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ICUEncoding](../)
* Namespace [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)