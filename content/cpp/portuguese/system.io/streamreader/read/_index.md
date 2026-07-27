---
title: Read()
second_title: Aspose.Slides para C++ Referência da API
description: Lê um único caractere do fluxo.
type: docs
weight: 40
url: /pt/system.io/streamreader/read/
---
## StreamReader::Read() method


Lê um único caractere do fluxo.

```cpp
virtual int System::IO::StreamReader::Read() override
```


### Valor de Retorno

Caractere lido codificado em UTF-16; se o caractere lido for representado por dois code points na codificação UTF-16, apenas o surrogado alto é retornado.

## StreamReader::Read(ArrayPtr\<char_t\>, int, int) method


Lê o número especificado de caracteres do fluxo, converte-os para a codificação UTF-16 e grava os caracteres UTF-16 resultantes no array de caracteres especificado, começando na posição especificada.

```cpp
virtual int System::IO::StreamReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | O array de caracteres UTF-16 onde serão gravados os caracteres lidos do fluxo |
| index | int | Um índice baseado em zero em **buffer** onde iniciar a gravação |
| count | int | O número de caracteres a ler do fluxo |

### Valor de Retorno

O número de caracteres lidos do fluxo

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [StreamReader](../)
* Espaço de nomes [System::IO](../../)
* Library [Aspose.Slides](../../../)