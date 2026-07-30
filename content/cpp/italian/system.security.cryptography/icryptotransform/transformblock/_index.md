---
title: TransformBlock()
second_title: Riferimento API Aspose.Slides per C++
description: Elabora un blocco di dati e copia i dati nell'array di output.
type: docs
weight: 1
url: /it/system.security.cryptography/icryptotransform/transformblock/
---
## ICryptoTransform::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) metodo

Elabora un blocco di dati e copia i dati nell'array di output.

```cpp
virtual int System::Security::Cryptography::ICryptoTransform::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) da cui leggere i dati. |
| inputOffset | int | Offset del buffer di input. |
| inputCount | int | Numero di byte da elaborare. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer di output in cui copiare i dati; nullptr per non copiare. |
| outputOffset | int | Offset del buffer di output. |

### Valore di ritorno

Numero di byte scritti.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ICryptoTransform](../)
* Spazio dei nomi [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)