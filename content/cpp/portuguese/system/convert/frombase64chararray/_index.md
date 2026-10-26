---
title: FromBase64CharArray()
second_title: Referência da API Aspose.Slides para C++
description: Decodifica dados codificados em base-64 representados como um intervalo no array de caracteres Unicode.
type: docs
weight: 53
url: /pt/system/convert/frombase64chararray/
---
## Convert::FromBase64CharArray(const ArrayPtr\<char_t\>\&, int, int) método


Decodifica dados codificados em base-64 representados como um intervalo no array de caracteres Unicode.

```cpp
static ArrayPtr<uint8_t> System::Convert::FromBase64CharArray(const ArrayPtr<char_t> &in_array, int offset, int length)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | O array contendo os dados a decodificar |
| offset | int | A posição no array de entrada onde o intervalo a ser decodificado começa |
| length | int | O comprimento do intervalo a ser decodificado |

### Valor de Retorno

Um array de bytes contendo os dados decodificados

## Veja Também

* Typedef [ArrayPtr](../../arrayptr/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)