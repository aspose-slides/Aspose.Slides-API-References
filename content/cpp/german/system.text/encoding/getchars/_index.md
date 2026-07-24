---
title: GetChars()
second_title: Aspose.Slides für C++ API-Referenz
description: Liefert die Zeichen, die beim Dekodieren eines Byte-Puffers entstehen.
type: docs
weight: 274
url: /de/system.text/encoding/getchars/
---
## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) Methode

Liefert die Zeichen, die beim Dekodieren eines Byte-Puffers entstehen.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) zum Lesen von Bytes aus. |
| byte_index | int | Offset des Eingabepuffers. |
| byte_count | int | Größe des Eingabepuffers. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) zum Ablegen von Zeichen. |
| char_index | int | Offset des Ausgabepuffers. |

### Rückgabewert

Anzahl der geschriebenen Zeichen.

## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) Methode

Liefert die Zeichen, die beim Dekodieren eines Byte-Puffers entstehen.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) zum Lesen von Bytes aus. |
| index | int | Offset des Eingabepuffers. |
| count | int | Größe des Eingabepuffers. |

### Rückgabewert

[Buffer](../../../system/buffer/) der decodierten Zeichen.

## Encoding::GetChars(ArrayPtr\<uint8_t\>) Methode

Liefert die Zeichen, die beim Dekodieren eines Byte-Puffers entstehen.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) zum Lesen von Bytes aus. |

### Rückgabewert

[Buffer](../../../system/buffer/) der decodierten Zeichen.

## Encoding::GetChars(const uint8_t *, int, char_t *, int) Methode

Liefert die Zeichen, die beim Dekodieren eines Byte-Puffers entstehen.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) zum Lesen von Bytes aus. |
| byte_count | int | Größe des Eingabepuffers. |
| chars | char_t * | [Buffer](../../../system/buffer/) zum Ablegen von Zeichen. |
| char_count | int | Größe des Ausgabepuffers. |

### Rückgabewert

Anzahl der geschriebenen Zeichen.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Encoding](../)
* Namensraum [System::Text](../../)
* Bibliothek [Aspose.Slides](../../../)