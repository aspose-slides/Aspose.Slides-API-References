---
title: GetCharCount()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Puffers benötigt werden.
type: docs
weight: 40
url: /de/system.text/decoder/getcharcount/
---
## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) method

Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Puffers benötigt werden.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Zu dekodierende Bytes. |
| index | int | [Buffer](../../../system/buffer/) Versatz. |
| count | int | Anzahl der zu dekodierenden Bytes. |

### Rückgabewert

Anzahl der zum Dekodieren des Puffers erforderlichen Zeichen.

## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) method

Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Puffers benötigt werden.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Zu dekodierende Bytes. |
| index | int | [Buffer](../../../system/buffer/) Versatz. |
| count | int | Anzahl der zu dekodierenden Bytes. |
| flush | **bool** | Wenn true, bereinigt den internen Decoder-Zustand nach der Berechnung. |

### Rückgabewert

Anzahl der zum Dekodieren des Puffers erforderlichen Zeichen.

## Decoder::GetCharCount(const uint8_t *, int, bool) method

Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Puffers benötigt werden.

```cpp
virtual int System::Text::Decoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | const **uint8_t** * | Zu dekodierende Bytes. |
| count | int | Anzahl der zu dekodierenden Bytes. |
| flush | **bool** | Wenn true, bereinigt den internen Decoder-Zustand nach der Berechnung. |

### Rückgabewert

Anzahl der zum Dekodieren des Puffers erforderlichen Zeichen.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Decoder](../)
* Namensraum [System::Text](../../)
* Bibliothek [Aspose.Slides](../../../)