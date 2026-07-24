---
title: GetChars()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Zeichen zurück, die sich aus der Dekodierung eines Byte-Puffers ergeben.
type: docs
weight: 66
url: /de/system.text/icuencoding/getchars/
---
## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) Methode


Liefert die Zeichen, die sich aus der Dekodierung eines Byte-Puffers ergeben.

```cpp
int System::Text::ICUEncoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) zum Lesen von Bytes aus. |
| byte_count | int | Eingabe-Puffergröße. |
| chars | char_t * | [Buffer](../../../system/buffer/) zum Ablegen von Zeichen. |
| char_count | int | Ausgabe-Puffergröße. |

### Rückgabewert

Anzahl der geschriebenen Zeichen.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) Methode


Liefert die Zeichen, die sich aus der Dekodierung eines Byte-Puffers ergeben.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) zum Lesen von Bytes aus. |
| byte_index | int | Eingabe-Puffer-Offset. |
| byte_count | int | Eingabe-Puffergröße. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) zum Ablegen von Zeichen. |
| char_index | int | Ausgabe-Puffer-Offset. |

### Rückgabewert

Anzahl der geschriebenen Zeichen.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int) Methode


Liefert die Zeichen, die sich aus der Dekodierung eines Byte-Puffers ergeben.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) zum Lesen von Bytes aus. |
| index | int | Eingabe-Puffer-Offset. |
| count | int | Eingabe-Puffergröße. |

### Rückgabewert

[Buffer](../../../system/buffer/) der dekodierten Zeichen.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>) Methode


Liefert die Zeichen, die sich aus der Dekodierung eines Byte-Puffers ergeben.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) zum Lesen von Bytes aus. |

### Rückgabewert

[Buffer](../../../system/buffer/) der dekodierten Zeichen.

## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) Methode


Liefert die Zeichen, die sich aus der Dekodierung eines Byte-Puffers ergeben.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) zum Lesen von Bytes aus. |
| byte_count | int | Eingabe-Puffergröße. |
| chars | char_t * | [Buffer](../../../system/buffer/) zum Ablegen von Zeichen. |
| char_count | int | Ausgabe-Puffergröße. |

### Rückgabewert

Anzahl der geschriebenen Zeichen.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ICUEncoding](../)
* Namensraum [System::Text](../../)
* Library [Aspose.Slides](../../../)