---
title: Read()
second_title: Referência da API Aspose.Slides for C++
description: Lê um único caractere do fluxo.
type: docs
weight: 40
url: /pt/system.io/stringreader/read/
---
## StringReader::Read() método


Lê um único caractere do fluxo.

```cpp
virtual int System::IO::StringReader::Read() override
```


### Valor de Retorno

Um caractere lido ou -1 se nenhum caractere foi lido

## StringReader::Read(ArrayPtr\<char_t\>, int, int) método


Lê o número especificado de caracteres do fluxo para o array de caracteres especificado, começando na posição especificada.

```cpp
virtual int System::IO::StringReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | O array de caracteres para onde gravar os caracteres lidos do fluxo |
| index | int | Um índice baseado em zero em **buffer** onde começar a gravar |
| count | int | O número de caracteres a ler do fluxo |

### Valor de Retorno

O número de caracteres lidos do fluxo

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StringReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)