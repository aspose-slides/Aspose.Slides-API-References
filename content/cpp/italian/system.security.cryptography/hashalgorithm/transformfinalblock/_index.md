---
title: TransformFinalBlock()
second_title: Riferimento API di Aspose.Slides per C++
description: Elabora l'ultimo blocco di dati e calcola l'hash.
type: docs
weight: 79
url: /it/system.security.cryptography/hashalgorithm/transformfinalblock/
---
## HashAlgorithm::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) metodo

Elabora l'ultimo blocco di dati e calcola l'hash.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) da cui leggere i dati. |
| inputOffset | int | Offset del buffer di input. |
| inputCount | int | Numero di byte da elaborare. |

### Valore di ritorno

Hash calcolato per l'intera sequenza di dati.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)