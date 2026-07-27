---
title: TransformBlock()
second_title: Aspose.Slides para C++ Referência da API
description: Processa bloco de dados e copia os dados para o array de saída.
type: docs
weight: 66
url: /pt/system.security.cryptography/hashalgorithm/transformblock/
---
## HashAlgorithm::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) método


Processa bloco de dados e copia os dados para o array de saída.

```cpp
int System::Security::Cryptography::HashAlgorithm::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) para ler os dados de. |
| inputOffset | int | Deslocamento do buffer de entrada. |
| inputCount | int | Número de bytes a processar. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer de saída para copiar os dados; nullptr para não copiar. |
| outputOffset | int | Deslocamento do buffer de saída. |

### Valor de Retorno

Número de bytes gravados.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)