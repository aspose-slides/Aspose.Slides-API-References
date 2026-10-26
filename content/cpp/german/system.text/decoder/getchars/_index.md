---
title: GetChars()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt die Zeichen, die durch das Dekodieren eines Puffers entstehen.
type: docs
weight: 53
url: /de/system.text/decoder/getchars/
---
## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) Methode

Ermittelt die Zeichen, die durch das Dekodieren eines Puffers entstehen.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes zum Dekodieren. |
| byteIndex | int | Eingabepufferversatz. |
| byteCount | int | Eingabepuffergröße. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Zielzeichenpuffer. |
| charIndex | int | Zielarrayversatz. |

### Rückgabewert

Anzahl der geschriebenen Zeichen.

## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) Methode

Ermittelt die Zeichen, die durch das Dekodieren eines Puffers entstehen.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes zum Dekodieren. |
| byteIndex | int | Eingabepufferversatz. |
| byteCount | int | Eingabepuffergröße. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Zielzeichenpuffer. |
| charIndex | int | Zielarrayversatz. |
| flush | **bool** | Wenn **true**, bereinigt den internen Decoder-Zustand nach der Berechnung. |

### Rückgabewert

Anzahl der geschriebenen Zeichen.

## Decoder::GetChars(const uint8_t *, int, char_t *, int, bool) Methode

Ermittelt die Zeichen, die durch das Dekodieren eines Puffers entstehen.

```cpp
virtual int System::Text::Decoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes zum Dekodieren. |
| byteCount | int | Eingabepuffergröße. |
| chars | char_t * | Zielzeichenpuffer. |
| charCount | int | Zielarraygröße. |
| flush | **bool** | Wenn **true**, bereinigt den internen Decoder-Zustand nach der Berechnung. |

### Rückgabewert

Anzahl der geschriebenen Zeichen.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Decoder](../)
* Namensraum [System::Text](../../)
* Bibliothek [Aspose.Slides](../../../)