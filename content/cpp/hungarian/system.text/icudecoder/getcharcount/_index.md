---
title: GetCharCount()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a puffer dekódolásához szükséges karakterek számát.
type: docs
weight: 40
url: /hu/system.text/icudecoder/getcharcount/
---
## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) metódus

A puffer dekódolásához szükséges karakterek számát adja vissza.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dekódolandó bájtok. |
| index | int | [Buffer](../../../system/buffer/) eltolás. |
| count | int | Dekódolandó bájtok száma. |

### Visszatérési érték

A puffer dekódolásához szükséges karakterek száma.

## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) metódus

A puffer dekódolásához szükséges karakterek számát adja vissza.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dekódolandó bájtok. |
| index | int | [Buffer](../../../system/buffer/) eltolás. |
| count | int | Dekódolandó bájtok száma. |
| flush | **bool** | Ha true, a számítás után megtisztítja a belső dekóder állapotot. |

### Visszatérési érték

A puffer dekódolásához szükséges karakterek száma.

## ICUDecoder::GetCharCount(const uint8_t *, int, bool) metódus

A puffer dekódolásához szükséges karakterek számát adja vissza.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | const **uint8_t** * | Dekódolandó bájtok. |
| count | int | Dekódolandó bájtok száma. |
| flush | **bool** | Ha true, a számítás után megtisztítja a belső dekóder állapotot. |

### Visszatérési érték

A puffer dekódolásához szükséges karakterek száma.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)