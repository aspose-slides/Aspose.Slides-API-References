---
title: GetByteCount()
second_title: Aspose.Slides C++ API hivatkozás
description: Meghatározza a puffer kódolásához szükséges bájtok számát.
type: docs
weight: 40
url: /hu/system.text/icuencoder/getbytecount/
---
## ICUEncoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) metódus

Meghatározza a puffer kódolásához szükséges bájtok számát.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | A kódolandó karakterek. |
| index | int | [Buffer](../../../system/buffer/) eltolás. |
| count | int | Kódolandó karakterek száma. |
| flush | **bool** | Ha igaz, törli a belső kódoló állapotot a számítás után. |

### Visszatérési érték

A puffer kódolásához szükséges bájtok száma.

## ICUEncoder::GetByteCount(const char_t *, int, bool) metódus

Meghatározza a puffer kódolásához szükséges bájtok számát.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(const char_t *chars, int count, bool flush)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chars | const char_t * | A kódolandó karakterek. |
| count | int | Kódolandó karakterek száma. |
| flush | **bool** | Ha igaz, törli a belső kódoló állapotot a számítás után. |

### Visszatérési érték

A puffer kódolásához szükséges bájtok száma.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [ICUEncoder](../)
* Névtér [System::Text](../../)
* Könyvtár [Aspose.Slides](../../../)