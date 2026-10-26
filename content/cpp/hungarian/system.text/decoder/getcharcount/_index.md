---
title: GetCharCount()
second_title: Aspose.Slides C++ API referencia
description: Lekéri a puffer dekódolásához szükséges karakterek számát.
type: docs
weight: 40
url: /hu/system.text/decoder/getcharcount/
---
## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) metódus


Lekéri a puffer dekódolásához szükséges karakterek számát.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dekódolandó bájtok. |
| index | int | [Buffer](../../../system/buffer/) eltolás. |
| count | int | Dekódolandó bájtok száma. |

### Visszatérési érték

A puffer dekódolásához szükséges karakterek száma.

## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) metódus


Lekéri a puffer dekódolásához szükséges karakterek számát.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dekódolandó bájtok. |
| index | int | [Buffer](../../../system/buffer/) eltolás. |
| count | int | Dekódolandó bájtok száma. |
| flush | **bool** | Ha igaz, a számítás után megtisztítja a belső dekóder állapotot. |

### Visszatérési érték

A puffer dekódolásához szükséges karakterek száma.

## Decoder::GetCharCount(const uint8_t *, int, bool) metódus


Lekéri a puffer dekódolásához szükséges karakterek számát.

```cpp
virtual int System::Text::Decoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | const **uint8_t** * | Dekódolandó bájtok. |
| count | int | Dekódolandó bájtok száma. |
| flush | **bool** | Ha igaz, a számítás után megtisztítja a belső dekóder állapotot. |

### Visszatérési érték

A puffer dekódolásához szükséges karakterek száma.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Decoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)