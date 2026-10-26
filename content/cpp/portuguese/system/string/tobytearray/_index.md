---
title: ToByteArray()
second_title: Referência da API Aspose.Slides para C++
description: Converte string ou substring em array de bytes.
type: docs
weight: 508
url: /pt/system/string/tobytearray/
---
## String::ToByteArray(int32_t, int32_t, bool) const método


Converte string ou substring em array de bytes.

```cpp
ArrayPtr<uint8_t> System::String::ToByteArray(int32_t startIndex=0, int32_t length=INT32_MAX, bool LE=1) const
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| startIndex | **int32_t** | Índice inicial da substring. |
| length | **int32_t** | Comprimento da substring. |
| LE | **bool** | Se verdadeiro, codifica caracteres usando little endianness; caso contrário, use big endianness. |

### Valor de retorno

[Array](../../array/) contendo bytes que representam caracteres da string.

## Veja também

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [String](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)