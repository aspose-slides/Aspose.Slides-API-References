---
title: ToDouble()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte otto byte dall'array specificato a partire dall'indice specificato in un valore a doppia precisione a virgola mobile.
type: docs
weight: 144
url: /it/system/bitconverter/todouble/
---
## BitConverter::ToDouble(const System::ArrayPtr\<uint8_t\>\&, int) metodo


Converte otto byte dall'array specificato a partire dall'indice specificato in un valore a virgola mobile a doppia precisione.

```cpp
static double System::BitConverter::ToDouble(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) che contiene i byte da convertire |
| startIndex | int | [Index](../../index/) nell'array a partire dal quale prendere i byte per la conversione |

### Valore restituito

Valore a virgola mobile a doppia precisione risultante dalla conversione

## BitConverter::ToDouble(const System::Details::ArrayView\<uint8_t\>\&, int) metodo


Converte otto byte dall'array specificato a partire dall'indice specificato in un valore a virgola mobile a doppia precisione.

```cpp
static double System::BitConverter::ToDouble(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView che contiene i byte da convertire |
| startIndex | int | [Index](../../index/) nell'array a partire dal quale prendere i byte per la conversione |

### Valore restituito

Valore a virgola mobile a doppia precisione risultante dalla conversione

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [BitConverter](../)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)