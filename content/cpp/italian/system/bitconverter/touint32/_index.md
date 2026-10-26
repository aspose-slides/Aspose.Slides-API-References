---
title: ToUInt32()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte quattro byte dall'array specificato a partire dall'indice specificato in un valore intero non firmato a 32-bit.
type: docs
weight: 105
url: /it/system/bitconverter/touint32/
---
## BitConverter::ToUInt32(const System::ArrayPtr\<uint8_t\>\&, int) metodo

Converte quattro byte dall'array specificato a partire dall'indice specificato in un valore intero non firmato a 32 bit.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) che contiene i byte da convertire |
| startIndex | int | [Index](../../index/) nell'array da cui iniziare a prendere i byte per la conversione |

### Valore di ritorno

Valore intero non firmato a 32 bit risultante dalla conversione

## BitConverter::ToUInt32(const System::Details::ArrayView\<uint8_t\>\&, int) metodo

Converte quattro byte dall'array specificato a partire dall'indice specificato in un valore intero non firmato a 32 bit.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView che contiene i byte da convertire |
| startIndex | int | [Index](../../index/) nell'array da cui iniziare a prendere i byte per la conversione |

### Valore di ritorno

Valore intero non firmato a 32 bit risultante dalla conversione

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [BitConverter](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)