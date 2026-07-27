---
title: ToBase64String()
second_title: Referência da API Aspose.Slides for C++
description: Codifica em Base-64 os elementos no array de bytes especificado e retorna os dados codificados como uma string.
type: docs
weight: 40
url: /pt/system/convert/tobase64string/
---
## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, bool) método

Codifica em Base-64 os elementos no array de bytes especificado e retorna os dados codificados como uma string.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, bool insert_line_breaks=false)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | O array de bytes a ser codificado |
| insert_line_breaks | **bool** | Especifica se caracteres de quebra de linha devem ser inseridos na string de saída após cada 76 caracteres base-64 |

### Valor de Retorno

A string contendo a representação codificada em base-64 do array de entrada

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, bool) método

Codifica em Base-64 um intervalo de elementos no array de bytes especificado e retorna os dados codificados como uma string.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, bool insert_line_breaks=false)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | O array de bytes contendo o intervalo de elementos a ser codificado |
| offset_in | int | Um índice de um elemento no array de entrada onde o intervalo a ser codificado começa |
| length | int | O comprimento do intervalo de elementos a ser codificado |
| insert_line_breaks | **bool** | Especifica se caracteres de quebra de linha devem ser inseridos na string de saída após cada 76 caracteres base-64 |

### Valor de Retorno

A string contendo a representação codificada em base-64 do intervalo de elementos do array de entrada

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, Base64FormattingOptions) método

Codifica em Base-64 os elementos no array de bytes especificado e retorna os dados codificados como uma string.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, Base64FormattingOptions options)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | O array de bytes a ser codificado |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Especifica opções de formatação dos dados codificados em base-64 |

### Valor de Retorno

A string contendo a representação codificada em base-64 do array de entrada

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, Base64FormattingOptions) método

Codifica em Base-64 um intervalo de elementos no array de bytes especificado e retorna os dados codificados como uma string.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, Base64FormattingOptions options)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | O array de bytes contendo o intervalo de elementos a ser codificado |
| offset_in | int | Um índice de um elemento no array de entrada onde o intervalo a ser codificado começa |
| length | int | O comprimento do intervalo de elementos a ser codificado |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Especifica opções de formatação dos dados codificados em base-64 |

### Valor de Retorno

A string contendo a representação codificada em base-64 do intervalo de elementos do array de entrada

## Veja Também

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Classe [String](../../string/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)