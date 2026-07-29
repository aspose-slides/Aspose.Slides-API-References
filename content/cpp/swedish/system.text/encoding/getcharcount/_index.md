---
title: GetCharCount()
second_title: Aspose.Slides för C++ API-referens
description: Hämta antalet tecken som behövs för att avkoda en bytebuffer.
type: docs
weight: 261
url: /sv/system.text/encoding/getcharcount/
---
## Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) metod


Get the number of characters needed to decode a byte buffer.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte att avkoda. |
| index | int | Skivans början. |
| count | int | Skivans storlek. |

### Returvärde

Number of characters.

## Encoding::GetCharCount(ArrayPtr\<uint8_t\>) metod


Get the number of characters needed to decode a byte buffer.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte att avkoda. |

### Returvärde

Number of characters.

## Encoding::GetCharCount(const uint8_t *, int) metod


Get the number of characters needed to decode a byte buffer.

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | const **uint8_t** * | Byte att avkoda. |
| count | int | Antal byte. |

### Returvärde

Number of characters.

## Se också

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [Encoding](../)
* Namnrymd [System::Text](../../)
* Bibliotek [Aspose.Slides](../../../)