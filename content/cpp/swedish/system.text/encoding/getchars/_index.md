---
title: GetChars()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar tecknen som resultat av avkodning av en bytebuffert.
type: docs
weight: 274
url: /sv/system.text/encoding/getchars/
---
## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) metod


Hämtar tecknen som resultat av avkodning av en bytebuffert.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) för att läsa bytes från. |
| byte_index | int | Inmatningsbuffertens förskjutning. |
| byte_count | int | Inmatningsbuffertens storlek. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) för att placera tecken i. |
| char_index | int | Utdatabuffertens förskjutning. |

### Returvärde

Antalet skrivna tecken.

## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) metod


Hämtar tecknen som resultat av avkodning av en bytebuffert.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) för att läsa bytes från. |
| index | int | Inmatningsbuffertens förskjutning. |
| count | int | Inmatningsbuffertens storlek. |

### Returvärde

[Buffer](../../../system/buffer/) av avkodade tecken.

## Encoding::GetChars(ArrayPtr\<uint8_t\>) metod


Hämtar tecknen som resultat av avkodning av en bytebuffert.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) för att läsa bytes från. |

### Returvärde

[Buffer](../../../system/buffer/) av avkodade tecken.

## Encoding::GetChars(const uint8_t *, int, char_t *, int) metod


Hämtar tecknen som resultat av avkodning av en bytebuffert.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) för att läsa bytes från. |
| byte_count | int | Inmatningsbuffertens storlek. |
| chars | char_t * | [Buffer](../../../system/buffer/) för att placera tecken i. |
| char_count | int | Utdatabuffertens storlek. |

### Returvärde

Antalet skrivna tecken.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [Encoding](../)
* Namnrymd [System::Text](../../)
* Bibliotek [Aspose.Slides](../../../)