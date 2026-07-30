---
title: ToUInt64()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte otto byte dall'array specificato a partire dall'indice specificato in valore intero senza segno a 64-bit.
type: docs
weight: 118
url: /it/system/bitconverter/touint64/
---
## BitConverter::ToUInt64(const System::ArrayPtr\<uint8_t\>\&, int) metodo


Converte otto byte dall'array specificato a partire dall'indice specificato in valore intero senza segno a 64 bit.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) che contiene i byte da convertire |
| startIndex | int | [Index](../../index/) nell'array al quale iniziare a prendere i byte per la conversione |

### Valore di ritorno

Valore intero senza segno a 64 bit risultante dalla conversione

## BitConverter::ToUInt64(const System::Details::ArrayView\<uint8_t\>\&, int) metodo


Converte otto byte dall'array specificato a partire dall'indice specificato in valore intero senza segno a 64 bit.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView che contiene i byte da convertire |
| startIndex | int | [Index](../../index/) nell'array al quale iniziare a prendere i byte per la conversione |

### Valore di ritorno

Valore intero senza segno a 64 bit risultante dalla conversione

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)