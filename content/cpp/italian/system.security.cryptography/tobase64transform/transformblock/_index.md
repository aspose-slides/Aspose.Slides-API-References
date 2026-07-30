---
title: TransformBlock()
second_title: Riferimento API Aspose.Slides per C++
description: Elabora un blocco di dati e copia i dati nell'array di output.
type: docs
weight: 53
url: /it/system.security.cryptography/tobase64transform/transformblock/
---
## ToBase64Transform::TransformBlock(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>, int32_t) metodo


Elabora un blocco di dati e copia i dati nell'array di output.

```cpp
int32_t System::Security::Cryptography::ToBase64Transform::TransformBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount, System::ArrayPtr<uint8_t> outputBuffer, int32_t outputOffset)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) per leggere i dati da. |
| inputOffset | **int32_t** | Offset del buffer di input. |
| inputCount | **int32_t** | Numero di byte da elaborare. |
| outputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer di output in cui copiare i dati; nullptr per non copiare. |
| outputOffset | **int32_t** | Offset del buffer di output. |

### Valore di ritorno

Numero di byte scritti.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ToBase64Transform](../)
* Spazio dei nomi [System::Security::Cryptography](../../)
* Libreria [Aspose.Slides](../../../)