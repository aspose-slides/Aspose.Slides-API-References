---
title: TransformBlock()
second_title: Referência da API Aspose.Slides para C++
description: Processa um bloco de dados e copia os dados para o array de saída.
type: docs
weight: 1
url: /pt/system.security.cryptography/icryptotransform/transformblock/
---
## ICryptoTransform::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) método


Processa um bloco de dados e copia os dados para o array de saída.

```cpp
virtual int System::Security::Cryptography::ICryptoTransform::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) para ler dados de. |
| inputOffset | int | Deslocamento do buffer de entrada. |
| inputCount | int | Número de bytes a processar. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer de saída onde copiar os dados; nullptr para não copiar. |
| outputOffset | int | Deslocamento do buffer de saída. |

### Valor de Retorno

Número de bytes escritos.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ICryptoTransform](../)
* Namespace [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)