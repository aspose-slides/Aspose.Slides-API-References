---
title: Read()
second_title: Referência da API Aspose.Slides para C++
description: Lê um único caractere do fluxo de entrada.
type: docs
weight: 66
url: /pt/system.io/binaryreader/read/
---
## BinaryReader::Read() método


Lê um único caractere do fluxo de entrada.

```cpp
virtual int System::IO::BinaryReader::Read()
```


### Valor de retorno

Caractere lido codificado em UTF-16; se o caractere lido for representado por dois codepoints na codificação UTF-16, então apenas o high surragate é retornado.

## BinaryReader::Read(ArrayPtr\<uint8_t\>, int, int) método


Lê o número especificado de bytes do fluxo de entrada e os grava no array de bytes especificado.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<uint8_t> buffer, int index, int count)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | O array de bytes para onde escrever os bytes lidos |
| index | int | Uma posição baseada em zero em **buffer** onde iniciar a gravação |
| count | int | O número de bytes a ler |

### Valor de retorno

O número de bytes lidos

## BinaryReader::Read(ArrayPtr\<char_t\>, int, int) método


Lê o número especificado de caracteres do fluxo de entrada, converte-os para codificação UTF-16 e grava os caracteres UTF-16 resultantes no array de caracteres especificado, começando na posição especificada.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | O array de caracteres UTF-16 para onde escrever os caracteres lidos do fluxo de entrada |
| index | int | Um índice baseado em zero em **buffer** onde iniciar a gravação |
| count | int | O número de caracteres a ler do fluxo |

### Valor de retorno

O número de caracteres lidos do fluxo de entrada

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [BinaryReader](../)
* Espaço de nomes [System::IO](../../)
* Library [Aspose.Slides](../../../)