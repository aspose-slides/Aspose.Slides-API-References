---
title: Read()
second_title: Referência da API Aspose.Slides para C++
description: Lê um único caractere do fluxo.
type: docs
weight: 40
url: /pt/system.io/textreader/read/
---
## TextReader::Read() método

Lê um único caractere do fluxo.

```cpp
virtual int System::IO::TextReader::Read()
```

### Valor de Retorno

Caractere lido codificado em UTF-16; se o caractere lido for representado por dois codepoints na codificação UTF-16, apenas o surrogado alto é retornado.

## TextReader::Read(ArrayPtr\<char_t\>, int, int) método

Lê o número especificado de caracteres do fluxo e grava-os no array de caracteres especificado, começando na posição especificada.

```cpp
virtual int System::IO::TextReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | O array de caracteres UTF-16 para o qual gravar os caracteres lidos do fluxo |
| index | int | Um índice baseado em 0 em **buffer** no qual começar a gravação |
| count | int | O número de caracteres a ler do fluxo |

### Valor de Retorno

O número de caracteres lidos do fluxo

## Ver Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [TextReader](../)
* Espaço de nomes [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)