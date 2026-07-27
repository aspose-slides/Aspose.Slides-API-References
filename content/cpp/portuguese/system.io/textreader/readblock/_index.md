---
title: ReadBlock()
second_title: Referência da API Aspose.Slides para C++
description: Lê o número máximo especificado de caracteres do leitor de texto atual e grava os dados em um buffer, começando no índice especificado.
type: docs
weight: 53
url: /pt/system.io/textreader/readblock/
---
## TextReader::ReadBlock(ArrayPtr\<char_t\>, int, int) método

Lê o número máximo especificado de caracteres do leitor de texto atual e grava os dados em um buffer, começando no índice especificado.

```cpp
virtual int System::IO::TextReader::ReadBlock(ArrayPtr<char_t> buffer, int index, int count)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Um buffer de caracteres para gravar os dados lidos |
| index | int | Um índice baseado em zero em **buffer** para iniciar a gravação |
| count | int | O número máximo de caracteres a ser lido |

### Valor de Retorno

O número real de caracteres lidos

## Ver também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TextReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)