---
title: ToString()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte tutti i valori dell'array di byte specificato nella loro rappresentazione stringa esadecimale. Il caso delle lettere da utilizzare nella notazione esadecimale e il separatore inserito tra ogni coppia di byte adiacenti sono specificati tramite i relativi argomenti.
type: docs
weight: 157
url: /it/system/bitconverter/tostring/
---
## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, bool, const String\&) metodo

Converte tutti i valori dell'array di byte specificato nella loro rappresentazione stringa esadecimale. Il caso delle lettere da utilizzare nella notazione esadecimale e il separatore inserito tra ogni coppia di byte adiacenti sono specificati tramite i relativi argomenti.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, bool uppercase=1, const String &separator=u"-")
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) che contiene i byte da convertire |
| uppercase | **bool** | Specifica il caso delle lettere da utilizzare nella rappresentazione esadecimale risultante |
| separator | const [String](../../string/)\& | Una stringa usata come separatore inserita tra ogni coppia di byte adiacenti nella stringa risultante |

### Valore restituito

[String](../../string/) contenente la rappresentazione esadecimale dell'array di byte specificato

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int) metodo

Converte i valori dell'array di byte specificato nella loro rappresentazione stringa esadecimale a partire dall'indice specificato.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) che contiene i byte da convertire |
| startIndex | int | [Index](../../index/) nell'array specificato a partire dal quale avviare la conversione |

### Valore restituito

[String](../../string/) contenente la rappresentazione esadecimale dell'intervallo specificato di elementi dell'array specificato

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int, int) metodo

Converte un intervallo di valori dell'array di byte specificato nella loro rappresentazione stringa esadecimale.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex, int length)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) che contiene i byte da convertire |
| startIndex | int | [Index](../../index/) nell'array specificato a partire dal quale inizia l'intervallo degli elementi dell'array di byte da convertire |
| length | int | La lunghezza dell'intervallo degli elementi dell'array di byte da convertire |

### Valore restituito

[String](../../string/) contenente la rappresentazione esadecimale dell'intervallo specificato di elementi dell'array specificato

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [String](../../string/)
* Classe [BitConverter](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)