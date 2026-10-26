---
title: ToSingle()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte quattro byte dall'array specificato a partire dall'indice specificato in un valore a virgola mobile a precisione singola.
type: docs
weight: 131
url: /it/system/bitconverter/tosingle/
---
## BitConverter::ToSingle(const System::ArrayPtr\<uint8_t\>\&, int) metodo

Converte quattro byte dall'array specificato a partire dall'indice specificato in un valore a virgola mobile a precisione singola.

```cpp
static float System::BitConverter::ToSingle(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) che contiene i byte da convertire |
| startIndex | int | [Index](../../index/) nell'array da cui iniziare a prendere i byte per la conversione |

### Valore di ritorno

Valore a virgola mobile a precisione singola risultante dalla conversione

## BitConverter::ToSingle(const System::Details::ArrayView\<uint8_t\>\&, int) metodo

Converte quattro byte dall'array specificato a partire dall'indice specificato in un valore a virgola mobile a precisione singola.

```cpp
static float System::BitConverter::ToSingle(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView che contiene i byte da convertire |
| startIndex | int | [Index](../../index/) nell'array da cui iniziare a prendere i byte per la conversione |

### Valore di ritorno

Valore a virgola mobile a precisione singola risultante dalla conversione

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)