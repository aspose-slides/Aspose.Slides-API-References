---
title: GetCharCount()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Byte-Puffers benötigt werden.
type: docs
weight: 79
url: /de/system.text/utf7encoding/getcharcount/
---
## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) method


Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Byte-Puffers benötigt werden.

```cpp
int System::Text::UTF7Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Zu dekodierende Bytes. |
| index | int | Anfang des Abschnitts. |
| count | int | Größe des Abschnitts. |

### Rückgabewert

Anzahl der Zeichen.

## UTF7Encoding::GetCharCount(const uint8_t *, int) method


Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Byte-Puffers benötigt werden.

```cpp
int System::Text::UTF7Encoding::GetCharCount(const uint8_t *bytes, int count) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | const **uint8_t** * | Zu dekodierende Bytes. |
| count | int | Anzahl der Bytes. |

### Rückgabewert

Anzahl der Zeichen.

## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) method


Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Byte-Puffers benötigt werden.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Zu dekodierende Bytes. |
| index | int | Anfang des Abschnitts. |
| count | int | Größe des Abschnitts. |

### Rückgabewert

Anzahl der Zeichen.

## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>) method


Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Byte-Puffers benötigt werden.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Zu dekodierende Bytes. |

### Rückgabewert

Anzahl der Zeichen.

## UTF7Encoding::GetCharCount(const uint8_t *, int) method


Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Byte-Puffers benötigt werden.

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | const **uint8_t** * | Zu dekodierende Bytes. |
| count | int | Anzahl der Bytes. |

### Rückgabewert

Anzahl der Zeichen.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [UTF7Encoding](../)
* Namensraum [System::Text](../../)
* Bibliothek [Aspose.Slides](../../../)