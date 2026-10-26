---
title: TransformFinalBlock()
second_title: Riferimento API di Aspose.Slides per C++
description: Elabora l'ultimo blocco di dati e calcola il valore di output.
type: docs
weight: 14
url: /it/system.security.cryptography/icryptotransform/transformfinalblock/
---
## ICryptoTransform::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) metodo

Elabora l'ultimo blocco di dati e calcola il valore di output.

```cpp
virtual ArrayPtr<uint8_t> System::Security::Cryptography::ICryptoTransform::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) da cui leggere i dati. |
| inputOffset | int | Offset del buffer di input. |
| inputCount | int | Numero di byte da elaborare. |

### Valore di ritorno

Output calcolato per l'intera sequenza di input.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ICryptoTransform](../)
* Spazio dei nomi [System::Security::Cryptography](../../)
* Libreria [Aspose.Slides](../../../)