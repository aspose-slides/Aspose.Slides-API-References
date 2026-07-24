---
title: GetBytes()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt die Bytes, die durch die Kodierung eines Puffers entstehen.
type: docs
weight: 53
url: /de/system.text/icuencoder/getbytes/
---
## ICUEncoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) Methode


Ermittelt die Bytes, die durch die Kodierung eines Puffers entstehen.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Zu kodierende Zeichen. |
| charIndex | int | Offset des Quellarrays. |
| charCount | int | Länge des Quellunterarrays. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ziel-Byte-Puffer. |
| byteIndex | int | Offset des Zielpuffers. |
| flush | **bool** | Falls true, wird der interne Encoder-Zustand nach der Berechnung bereinigt. |

### Rückgabewert

Anzahl der geschriebenen Bytes.

## ICUEncoder::GetBytes(const char_t *, int, uint8_t *, int, bool) Methode


Ermittelt die Bytes, die durch die Kodierung eines Puffers entstehen.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | const char_t * | Zu kodierende Zeichen. |
| charCount | int | Länge des Quellarrays. |
| bytes | **uint8_t** * | Ziel-Byte-Puffer. |
| byteCount | int | Größe des Zielpuffers. |
| flush | **bool** | Falls true, wird der interne Encoder-Zustand nach der Berechnung bereinigt. |

### Rückgabewert

Anzahl der geschriebenen Bytes.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ICUEncoder](../)
* Namensraum [System::Text](../../)
* Bibliothek [Aspose.Slides](../../../)