---
title: GetCharCount()
second_title: Aspose.Slides für C++ API Referenz
description: Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Puffers benötigt werden.
type: docs
weight: 40
url: /de/system.text/icudecoder/getcharcount/
---
## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) Methode


Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Puffers benötigt werden.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Zu dekodierende Bytes. |
| index | int | [Buffer](../../../system/buffer/) Versatz. |
| count | int | Anzahl der zu dekodierenden Bytes. |

### Rückgabewert

Anzahl der zum Dekodieren des Puffers erforderlichen Zeichen.

## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) Methode


Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Puffers benötigt werden.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Zu dekodierende Bytes. |
| index | int | [Buffer](../../../system/buffer/) Versatz. |
| count | int | Anzahl der zu dekodierenden Bytes. |
| flush | **bool** | Falls true, wird der interne Decoder-Zustand nach der Berechnung bereinigt. |

### Rückgabewert

Anzahl der zum Dekodieren des Puffers erforderlichen Zeichen.

## ICUDecoder::GetCharCount(const uint8_t *, int, bool) Methode


Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Puffers benötigt werden.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | const **uint8_t** * | Zu dekodierende Bytes. |
| count | int | Anzahl der zu dekodierenden Bytes. |
| flush | **bool** | Falls true, wird der interne Decoder-Zustand nach der Berechnung bereinigt. |

### Rückgabewert

Anzahl der zum Dekodieren des Puffers erforderlichen Zeichen.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)