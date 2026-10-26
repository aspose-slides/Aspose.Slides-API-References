---
title: ToUInt16()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte due byte dall'array specificato a partire dall'indice specificato in valore intero senza segno a 16 bit.
type: docs
weight: 92
url: /it/system/bitconverter/touint16/
---
## BitConverter::ToUInt16(const System::ArrayPtr\<uint8_t\>\&, int) method

Converte due byte dall'array specificato a partire dall'indice specificato in un valore intero senza segno a 16 bit.

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) che contiene i byte da convertire |
| startIndex | int | [Index](../../index/) nell'array a cui iniziare a prelevare i byte per la conversione |

### Valore restituito

Valore intero senza segno a 16 bit risultante dalla conversione

## BitConverter::ToUInt16(const System::Details::ArrayView\<uint8_t\>\&, int) method

Converte due byte dall'array specificato a partire dall'indice specificato in un valore intero senza segno a 16 bit.

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView che contiene i byte da convertire |
| startIndex | int | [Index](../../index/) nell'array a cui iniziare a prelevare i byte per la conversione |

### Valore restituito

Valore intero senza segno a 16 bit risultante dalla conversione

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [BitConverter](../)
* Spazio dei nomi [System](../../)
* Library [Aspose.Slides](../../../)