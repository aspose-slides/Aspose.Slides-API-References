---
title: TransformFinalBlock()
second_title: Referência da API Aspose.Slides para C++
description: Processa o último bloco de dados e calcula o hash.
type: docs
weight: 79
url: /pt/system.security.cryptography/hashalgorithm/transformfinalblock/
---
## HashAlgorithm::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) method

Processa o último bloco de dados e calcula o hash.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) para ler os dados. |
| inputOffset | int | Deslocamento do buffer de entrada. |
| inputCount | int | Número de bytes a processar. |

### Valor de Retorno

Hash calculado para toda a sequência de dados.

## Ver Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)