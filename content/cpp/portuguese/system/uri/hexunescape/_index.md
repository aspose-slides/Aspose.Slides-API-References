---
title: HexUnescape()
second_title: Aspose.Slides para C++ Referência da API
description: Converte a representação hexadecimal especificada de um caractere em um caractere.
type: docs
weight: 443
url: /pt/system/uri/hexunescape/
---
## Uri::HexUnescape(const String\&, int32_t\&) método


Converte a representação hexadecimal especificada de um caractere em um caractere.

```cpp
static char16_t System::Uri::HexUnescape(const String &pattern, int32_t &index)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pattern | const [String](../../string/)\& | Uma string contendo a representação hexadecimal de um caractere |
| index | **int32_t**\& | A posição em **pattern** onde a representação hexadecimal de um caractere começa |

### Valor de Retorno

O caractere representado pela codificação hexadecimal na posição **index**. Se o caractere na posição **index** não estiver codificado em hexadecimal, o caractere na posição **index** será retornado. O valor de **index** é incrementado para apontar para o caractere que segue o retornado.

## Veja Também

* Classe [String](../../string/)
* Classe [Uri](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)