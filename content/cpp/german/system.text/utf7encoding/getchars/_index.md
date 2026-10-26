---
title: GetChars()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest die Zeichen, die durch das Dekodieren eines Byte-Puffers entstehen.
type: docs
weight: 92
url: /de/system.text/utf7encoding/getchars/
---
## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) Methode


Liest die Zeichen, die aus der Dekodierung eines Bytepuffers resultieren.

```cpp
int System::Text::UTF7Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) um Bytes zu lesen. |
| byte_index | int | Offset des Eingabepuffers. |
| byte_count | int | Größe des Eingabepuffers. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) um Zeichen zu schreiben. |
| char_index | int | Offset des Ausgabepuffers. |

### Rückgabewert

Anzahl der geschriebenen Zeichen.

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) Methode


Liest die Zeichen, die aus der Dekodierung eines Bytepuffers resultieren.

```cpp
int System::Text::UTF7Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) um Bytes zu lesen. |
| byte_count | int | Größe des Eingabepuffers. |
| chars | char_t * | [Buffer](../../../system/buffer/) um Zeichen zu schreiben. |
| char_count | int | Größe des Ausgabepuffers. |

### Rückgabewert

Anzahl der geschriebenen Zeichen.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) Methode


Liest die Zeichen, die aus der Dekodierung eines Bytepuffers resultieren.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) um Bytes zu lesen. |
| byte_index | int | Offset des Eingabepuffers. |
| byte_count | int | Größe des Eingabepuffers. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) um Zeichen zu schreiben. |
| char_index | int | Offset des Ausgabepuffers. |

### Rückgabewert

Anzahl der geschriebenen Zeichen.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) Methode


Liest die Zeichen, die aus der Dekodierung eines Bytepuffers resultieren.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) um Bytes zu lesen. |
| index | int | Offset des Eingabepuffers. |
| count | int | Größe des Eingabepuffers. |

### Rückgabewert

[Buffer](../../../system/buffer/) dekodierter Zeichen.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>) Methode


Liest die Zeichen, die aus der Dekodierung eines Bytepuffers resultieren.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) um Bytes zu lesen. |

### Rückgabewert

[Buffer](../../../system/buffer/) dekodierter Zeichen.

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) Methode


Liest die Zeichen, die aus der Dekodierung eines Bytepuffers resultieren.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) um Bytes zu lesen. |
| byte_count | int | Größe des Eingabepuffers. |
| chars | char_t * | [Buffer](../../../system/buffer/) um Zeichen zu schreiben. |
| char_count | int | Größe des Ausgabepuffers. |

### Rückgabewert

Anzahl der geschriebenen Zeichen.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [UTF7Encoding](../)
* Namensraum [System::Text](../../)
* Library [Aspose.Slides](../../../)