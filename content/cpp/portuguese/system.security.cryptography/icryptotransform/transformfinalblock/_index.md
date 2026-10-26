---
title: TransformFinalBlock()
second_title: Aspose.Slides para C++ Referência da API
description: Processa o último bloco de dados e calcula o valor de saída.
type: docs
weight: 14
url: /pt/system.security.cryptography/icryptotransform/transformfinalblock/
---
## ICryptoTransform::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) method


Processa o último bloco de dados e calcula o valor de saída.

```cpp
virtual ArrayPtr<uint8_t> System::Security::Cryptography::ICryptoTransform::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) para ler dados de. |
| inputOffset | int | Deslocamento do buffer de entrada. |
| inputCount | int | Número de bytes a processar. |

### Valor de Retorno

Saída calculada para toda a sequência de entrada.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ICryptoTransform](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)