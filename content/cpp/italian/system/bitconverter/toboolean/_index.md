---
title: ToBoolean()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte un byte dall'array specificato a partire dall'indice specificato in un valore booleano.
type: docs
weight: 27
url: /it/system/bitconverter/toboolean/
---
## BitConverter::ToBoolean(const System::ArrayPtr\<uint8_t\>\&, int) metodo

Converte un byte dall'array specificato a partire dall'indice specificato in un valore booleano.

```cpp
static bool System::BitConverter::ToBoolean(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) che contiene byte da convertire |
| startIndex | int | [Index](../../index/) nell'array al quale iniziare a prendere i byte per la conversione |

### Valore di ritorno

[Boolean](../../boolean/) valore risultante dalla conversione

## BitConverter::ToBoolean(const System::Details::ArrayView\<uint8_t\>\&, int) metodo

Converte un byte dall'array specificato a partire dall'indice specificato in un valore booleano.

```cpp
static bool System::BitConverter::ToBoolean(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView che contiene byte da convertire |
| startIndex | int | [Index](../../index/) nell'array al quale iniziare a prendere i byte per la conversione |

### Valore di ritorno

[Boolean](../../boolean/) valore risultante dalla conversione

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [BitConverter](../)
* Spazio dei nomi [System](../../)
* Library [Aspose.Slides](../../../)