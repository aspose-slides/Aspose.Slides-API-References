---
title: ToInt16()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte due byte dall'array specificato a partire dall'indice specificato in un valore intero a 16-bit.
type: docs
weight: 53
url: /it/system/bitconverter/toint16/
---
## BitConverter::ToInt16(const System::ArrayPtr\<uint8_t\>\&, int) metodo

Converte due byte dall'array specificato a partire dall'indice specificato in un valore intero a 16-bit.

```cpp
static int16_t System::BitConverter::ToInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) che contiene i byte da convertire |
| startIndex | int | [Index](../../index/) nell'array al quale iniziare a prelevare i byte per la conversione |

### Valore restituito

Valore intero a 16-bit risultante dalla conversione

## BitConverter::ToInt16(const System::Details::ArrayView\<uint8_t\>\&, int) metodo

Converte due byte dall'array specificato a partire dall'indice specificato in un valore intero a 16-bit.

```cpp
static int16_t System::BitConverter::ToInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView che contiene i byte da convertire |
| startIndex | int | [Index](../../index/) nell'array al quale iniziare a prelevare i byte per la conversione |

### Valore restituito

Valore intero a 16-bit risultante dalla conversione

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [BitConverter](../)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)