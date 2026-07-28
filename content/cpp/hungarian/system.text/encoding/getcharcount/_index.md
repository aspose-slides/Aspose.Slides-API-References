---
title: GetCharCount()
second_title: Aspose.Slides C++ API referencia
description: A bájtpuffer dekódolásához szükséges karakterek száma.
type: docs
weight: 261
url: /hu/system.text/encoding/getcharcount/
---
## Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) metódus


A bájtpuffer dekódolásához szükséges karakterek számát adja vissza.

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

## Encoding::GetCharCount(ArrayPtr\<uint8_t\>) metódus


A bájtpuffer dekódolásához szükséges karakterek számát adja vissza.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dekódolandó bájtok. |

### Visszatérési érték

Karakterek száma.

## Encoding::GetCharCount(const uint8_t *, int) metódus


A bájtpuffer dekódolásához szükséges karakterek számát adja vissza.

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

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)