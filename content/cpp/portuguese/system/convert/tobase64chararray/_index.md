---
title: ToBase64CharArray()
second_title: Referência da API Aspose.Slides for C++
description: Base-64 codifica um intervalo de elementos no array de bytes especificado e armazena os dados codificados como um array de caracteres Unicode.
type: docs
weight: 27
url: /pt/system/convert/tobase64chararray/
---
## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char16_t\>\&, int, bool) method


Base-64 codifica um intervalo de elementos no array de bytes especificado e armazena os dados codificados como um array de caracteres Unicode.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char16_t> &out_array, int offset_out, bool insert_line_breaks=false)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | O array de bytes contendo o intervalo de elementos a codificar |
| offset_in | int | Um índice de um elemento no array de entrada no qual o intervalo a codificar começa |
| length | int | O comprimento do intervalo de elementos a codificar |
| out_array | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | Uma referência constante ao array de saída onde os dados resultantes devem ser colocados |
| offset_out | int | Um índice no array de saída onde começar a colocar os dados resultantes |
| insert_line_breaks | **bool** | Especifica se os caracteres de quebra de linha devem ser inseridos no array de saída após cada 76 caracteres base-64 |

### Valor de Retorno

O número de caracteres gravados no array de saída

## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char_t\>\&, int, Base64FormattingOptions) method


Base-64 codifica um intervalo de elementos no array de bytes especificado e armazena os dados codificados como um array de caracteres Unicode.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char_t> &out_array, int offset_out, Base64FormattingOptions options)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | O array de bytes contendo o intervalo de elementos a codificar |
| offset_in | int | Um índice de um elemento no array de entrada no qual o intervalo a codificar começa |
| length | int | O comprimento do intervalo de elementos a codificar |
| out_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Uma referência constante ao array de saída onde os dados resultantes devem ser colocados |
| offset_out | int | Um índice no array de saída onde começar a colocar os dados resultantes |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Especifica opções de formatação dos dados codificados em base-64 |

### Valor de Retorno

O número de caracteres gravados no array de saída

## Veja Também

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Struct [Convert](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)