---
title: GetCharCount()
second_title: Aspose.Slides C++ API referenciája
description: Megadja a bájtpuffer dekódolásához szükséges karakterek számát.
type: docs
weight: 53
url: /hu/system.text/icuencoding/getcharcount/
---
## ICUEncoding::GetCharCount(const uint8_t *, int) metódus

Megadja a bájtpuffer dekódolásához szükséges karakterek számát.

```cpp
int System::Text::ICUEncoding::GetCharCount(const uint8_t *bytes, int count) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | const **uint8_t** * | Dekódolandó bájtok. |
| count | int | Bájtok száma. |

### Visszatérési érték

Karakterek száma.

## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) metódus

Megadja a bájtpuffer dekódolásához szükséges karakterek számát.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dekódolandó bájtok. |
| index | int | Szelet kezdete. |
| count | int | Szelet mérete. |

### Visszatérési érték

Karakterek száma.

## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>) metódus

Megadja a bájtpuffer dekódolásához szükséges karakterek számát.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dekódolandó bájtok. |

### Visszatérési érték

Karakterek száma.

## ICUEncoding::GetCharCount(const uint8_t *, int) metódus

Megadja a bájtpuffer dekódolásához szükséges karakterek számát.

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | const **uint8_t** * | Dekódolandó bájtok. |
| count | int | Bájtok száma. |

### Visszatérési érték

Karakterek száma.

## Lásd még

* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Osztály [ICUEncoding](../)
* Névtér [System::Text](../../)
* Könyvtár [Aspose.Slides](../../../)