---
title: TransformBlock()
second_title: Referência da API Aspose.Slides para C++
description: Processa bloco de dados e copia os dados para o array de saída.
type: docs
weight: 53
url: /pt/system.security.cryptography/tobase64transform/transformblock/
---
## ToBase64Transform::TransformBlock(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>, int32_t) método

Processa bloco de dados e copia os dados para o array de saída.

```cpp
int32_t System::Security::Cryptography::ToBase64Transform::TransformBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount, System::ArrayPtr<uint8_t> outputBuffer, int32_t outputOffset)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) para ler dados de. |
| inputOffset | **int32_t** | Deslocamento do buffer de entrada. |
| inputCount | **int32_t** | Número de bytes a processar. |
| outputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer de saída para copiar dados; nullptr para não copiar. |
| outputOffset | **int32_t** | Deslocamento do buffer de saída. |

### Valor de Retorno

Número de bytes gravados.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ToBase64Transform](../)
* Namespace [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)