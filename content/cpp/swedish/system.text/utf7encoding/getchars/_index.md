---
title: GetChars()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar tecknen som resultat av avkodning av en bytebuffert.
type: docs
weight: 92
url: /sv/system.text/utf7encoding/getchars/
---
## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) method

Hämtar tecknen som resultat av avkodning av en bytebuffert.

```cpp
int System::Text::UTF7Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) att läsa byte från. |
| byte_index | int | Indata buffertoffset. |
| byte_count | int | Indata buffertstorlek. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) att placera tecken i. |
| char_index | int | Utdata buffertoffset. |

### Returvärde

Antal skrivna tecken.

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) method

Hämtar tecknen som resultat av avkodning av en bytebuffert.

```cpp
int System::Text::UTF7Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) att läsa byte från. |
| byte_count | int | Indata buffertstorlek. |
| chars | char_t * | [Buffer](../../../system/buffer/) att placera tecken i. |
| char_count | int | Utdata buffertstorlek. |

### Returvärde

Antal skrivna tecken.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) method

Hämtar tecknen som resultat av avkodning av en bytebuffert.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) att läsa byte från. |
| byte_index | int | Indata buffertoffset. |
| byte_count | int | Indata buffertstorlek. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) att placera tecken i. |
| char_index | int | Utdata buffertoffset. |

### Returvärde

Antal skrivna tecken.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) method

Hämtar tecknen som resultat av avkodning av en bytebuffert.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) att läsa byte från. |
| index | int | Indata buffertoffset. |
| count | int | Indata buffertstorlek. |

### Returvärde

[Buffer](../../../system/buffer/) av avkodade tecken.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>) method

Hämtar tecknen som resultat av avkodning av en bytebuffert.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) att läsa byte från. |

### Returvärde

[Buffer](../../../system/buffer/) av avkodade tecken.

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) method

Hämtar tecknen som resultat av avkodning av en bytebuffert.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) att läsa byte från. |
| byte_count | int | Indata buffertstorlek. |
| chars | char_t * | [Buffer](../../../system/buffer/) att placera tecken i. |
| char_count | int | Utdata buffertstorlek. |

### Returvärde

Antal skrivna tecken.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)