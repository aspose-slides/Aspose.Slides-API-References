---
title: GetByteCount()
second_title: Aspose.Slides for C++ API referencia
description: Lekéri a puffer kódolásához szükséges bájtok számát.
type: docs
weight: 40
url: /hu/system.text/encoder/getbytecount/
---
## Encoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) metódus

Lekéri a puffer kódolásához szükséges bájtok számát.

```cpp
virtual int System::Text::Encoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | A kódolandó karakterek. |
| index | int | [Buffer](../../../system/buffer/) eltolás. |
| count | int | A kódolandó karakterek száma. |
| flush | **bool** | Ha igaz, a számítás után megtisztítja a belső kódoló állapotot. |

### Visszatérési érték

A puffer kódolásához szükséges bájtok száma.

## Encoder::GetByteCount(const char_t *, int, bool) metódus

Lekéri a puffer kódolásához szükséges bájtok számát.

```cpp
virtual int System::Text::Encoder::GetByteCount(const char_t *chars, int count, bool flush)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chars | const char_t * | A kódolandó karakterek. |
| count | int | A kódolandó karakterek száma. |
| flush | **bool** | Ha igaz, a számítás után megtisztítja a belső kódoló állapotot. |

### Visszatérési érték

A puffer kódolásához szükséges bájtok száma.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [Encoder](../)
* Névtér [System::Text](../../)
* Könyvtár [Aspose.Slides](../../../)