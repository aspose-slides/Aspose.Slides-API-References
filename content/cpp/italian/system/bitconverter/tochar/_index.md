---
title: ToChar()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte due byte dall'array specificato a partire dall'indice specificato in un valore char_t.
type: docs
weight: 40
url: /it/system/bitconverter/tochar/
---
## BitConverter::ToChar(const System::ArrayPtr\<uint8_t\>\&, int) metodo

Converte due byte dall'array specificato a partire dall'indice specificato in un valore char_t.

```cpp
static char_t System::BitConverter::ToChar(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) che contiene i byte da convertire |
| startIndex | int | [Index](../../index/) nell'array al quale iniziare a prelevare i byte per la conversione |

### Valore di ritorno

valore char_t risultante dalla conversione

## BitConverter::ToChar(const System::Details::ArrayView\<uint8_t\>\&, int) metodo

Converte due byte dall'array specificato a partire dall'indice specificato in un valore char_t.

```cpp
static char_t System::BitConverter::ToChar(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView che contiene i byte da convertire |
| startIndex | int | [Index](../../index/) nell'array al quale iniziare a prelevare i byte per la conversione |

### Valore di ritorno

valore char_t risultante dalla conversione

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [BitConverter](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)