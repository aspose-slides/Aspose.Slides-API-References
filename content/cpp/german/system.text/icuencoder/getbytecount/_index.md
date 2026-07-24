---
title: GetByteCount()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt die Anzahl der Bytes, die zum Kodieren eines Puffers benötigt werden.
type: docs
weight: 40
url: /de/system.text/icuencoder/getbytecount/
---
## ICUEncoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) Methode


Ermittelt die Anzahl der Bytes, die zum Kodieren eines Puffers benötigt werden.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Zu codierende Zeichen. |
| index | int | [Buffer](../../../system/buffer/) Versatz. |
| count | int | Anzahl der zu codierenden Zeichen. |
| flush | **bool** | Wenn true, wird der interne Encoder-Zustand nach der Berechnung bereinigt. |

### Rückgabewert

Anzahl der Bytes, die zum Kodieren des Puffers erforderlich sind.

## ICUEncoder::GetByteCount(const char_t *, int, bool) Methode


Ermittelt die Anzahl der Bytes, die zum Kodieren eines Puffers benötigt werden.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(const char_t *chars, int count, bool flush)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | const char_t * | Zu codierende Zeichen. |
| count | int | Anzahl der zu codierenden Zeichen. |
| flush | **bool** | Wenn true, wird der interne Encoder-Zustand nach der Berechnung bereinigt. |

### Rückgabewert

Anzahl der Bytes, die zum Kodieren des Puffers erforderlich sind.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)