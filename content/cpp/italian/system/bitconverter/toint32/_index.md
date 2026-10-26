---
title: ToInt32()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte quattro byte dall'array specificato a partire dall'indice specificato in un valore intero a 32 bit.
type: docs
weight: 66
url: /it/system/bitconverter/toint32/
---
## BitConverter::ToInt32(const System::ArrayPtr\<uint8_t\>\&, int) metodo


Converte quattro byte dall'array specificato a partire dall'indice specificato in un valore intero a 32 bit.

```cpp
static int System::BitConverter::ToInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) che contiene i byte da convertire |
| startIndex | int | [Index](../../index/) nell'array da cui iniziare a prendere i byte per la conversione |

### Valore restituito

Valore intero a 32 bit risultante dalla conversione

## BitConverter::ToInt32(const System::Details::ArrayView\<uint8_t\>\&, int) metodo


Converte quattro byte dall'array specificato a partire dall'indice specificato in un valore intero a 32 bit.

```cpp
static int System::BitConverter::ToInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView che contiene i byte da convertire |
| startIndex | int | [Index](../../index/) nell'array da cui iniziare a prendere i byte per la conversione |

### Valore restituito

Valore intero a 32 bit risultante dalla conversione

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [BitConverter](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)