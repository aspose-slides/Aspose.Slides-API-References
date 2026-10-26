---
title: GetByteCount()
second_title: Aspose.Slides fuer C++ API-Referenz
description: Ermittelt die Anzahl der Bytes, die zum Kodieren eines Puffers benoetigt werden.
type: docs
weight: 40
url: /de/system.text/encoder/getbytecount/
---
## Encoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) method

Ermittelt die Anzahl der Bytes, die zum Kodieren eines Puffers benötigt werden.

```cpp
virtual int System::Text::Encoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Characters to encode. |
| index | int | [Buffer](../../../system/buffer/) Versatz. |
| count | int | Number of characters to encode. |
| flush | **bool** | Wenn true, wird der interne Encoder-Zustand nach der Berechnung bereinigt. |

### Rückgabewert

Anzahl der Bytes, die zum Kodieren des Puffers erforderlich sind.

## Encoder::GetByteCount(const char_t *, int, bool) method

Ermittelt die Anzahl der Bytes, die zum Kodieren eines Puffers benötigt werden.

```cpp
virtual int System::Text::Encoder::GetByteCount(const char_t *chars, int count, bool flush)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | const char_t * | Characters to encode. |
| count | int | Number of characters to encode. |
| flush | **bool** | Wenn true, wird der interne Encoder-Zustand nach der Berechnung bereinigt. |

### Rückgabewert

Anzahl der Bytes, die zum Kodieren des Puffers erforderlich sind.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Encoder](../)
* Namensraum [System::Text](../../)
* Bibliothek [Aspose.Slides](../../../)