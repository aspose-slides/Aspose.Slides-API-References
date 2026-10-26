---
title: GetCharCount()
second_title: Aspose.Slides C++ API-referencia
description: A bytepuffer dekódolásához szükséges karakterek számát adja vissza.
type: docs
weight: 79
url: /hu/system.text/utf7encoding/getcharcount/
---
## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) metódus

A bytepuffer dekódolásához szükséges karakterek számát adja vissza.

```cpp
int System::Text::UTF7Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dekódolandó bájtok. |
| index | int | Szelet kezdete. |
| count | int | Szelet mérete. |

### Visszatérési érték

Karakterek száma.

## UTF7Encoding::GetCharCount(const uint8_t *, int) metódus

A bytepuffer dekódolásához szükséges karakterek számát adja vissza.

```cpp
int System::Text::UTF7Encoding::GetCharCount(const uint8_t *bytes, int count) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | const **uint8_t** * | Dekódolandó bájtok. |
| count | int | Bájtok száma. |

### Visszatérési érték

Karakterek száma.

## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) metódus

A bytepuffer dekódolásához szükséges karakterek számát adja vissza.

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

## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>) metódus

A bytepuffer dekódolásához szükséges karakterek számát adja vissza.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dekódolandó bájtok. |

### Visszatérési érték

Karakterek száma.

## UTF7Encoding::GetCharCount(const uint8_t *, int) metódus

A bytepuffer dekódolásához szükséges karakterek számát adja vissza.

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
* Osztály [UTF7Encoding](../)
* Névtér [System::Text](../../)
* Könyvtár [Aspose.Slides](../../../)