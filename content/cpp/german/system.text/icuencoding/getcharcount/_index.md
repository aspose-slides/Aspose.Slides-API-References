---
title: GetCharCount()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Byte-Puffers erforderlich sind.
type: docs
weight: 53
url: /de/system.text/icuencoding/getcharcount/
---
## ICUEncoding::GetCharCount(const uint8_t *, int) method


Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Byte-Puffers erforderlich sind.

```cpp
int System::Text::ICUEncoding::GetCharCount(const uint8_t *bytes, int count) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes zum Dekodieren. |
| count | int | Anzahl der Bytes. |

### Rückgabewert

Anzahl der Zeichen.

## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) method


Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Byte-Puffers erforderlich sind.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes zum Dekodieren. |
| index | int | Anfang des Ausschnitts. |
| count | int | Größe des Ausschnitts. |

### Rückgabewert

Anzahl der Zeichen.

## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>) method


Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Byte-Puffers erforderlich sind.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes zum Dekodieren. |

### Rückgabewert

Anzahl der Zeichen.

## ICUEncoding::GetCharCount(const uint8_t *, int) method


Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Byte-Puffers erforderlich sind.

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes zum Dekodieren. |
| count | int | Anzahl der Bytes. |

### Rückgabewert

Anzahl der Zeichen.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)