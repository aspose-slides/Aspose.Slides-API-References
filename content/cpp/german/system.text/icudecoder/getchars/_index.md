---
title: GetChars()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Zeichen zurück, die durch das Dekodieren eines Puffers entstehen.
type: docs
weight: 53
url: /de/system.text/icudecoder/getchars/
---
## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) Methode

Liefert die Zeichen, die aus dem Dekodieren eines Puffers resultieren.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Zu dekodierende Bytes. |
| byteIndex | int | Offset des Eingabepuffers. |
| byteCount | int | Größe des Eingabepuffers. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Zielzeichenpuffer. |
| charIndex | int | Offset des Zielarrays. |

### Rückgabewert

Anzahl der geschriebenen Zeichen.

## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) Methode

Liefert die Zeichen, die aus dem Dekodieren eines Puffers resultieren.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Zu dekodierende Bytes. |
| byteIndex | int | Offset des Eingabepuffers. |
| byteCount | int | Größe des Eingabepuffers. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Zielzeichenpuffer. |
| charIndex | int | Offset des Zielarrays. |
| flush | **bool** | Wenn true, wird der interne Decoder-Zustand nach der Berechnung bereinigt. |

### Rückgabewert

Anzahl der geschriebenen Zeichen.

## ICUDecoder::GetChars(const uint8_t *, int, char_t *, int, bool) Methode

Liefert die Zeichen, die aus dem Dekodieren eines Puffers resultieren.

```cpp
virtual int System::Text::ICUDecoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | const **uint8_t** * | Zu dekodierende Bytes. |
| byteCount | int | Größe des Eingabepuffers. |
| chars | char_t * | Zielzeichenpuffer. |
| charCount | int | Größe des Zielarrays. |
| flush | **bool** | Wenn true, wird der interne Decoder-Zustand nach der Berechnung bereinigt. |

### Rückgabewert

Anzahl der geschriebenen Zeichen.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ICUDecoder](../)
* Namensraum [System::Text](../../)
* Bibliothek [Aspose.Slides](../../../)