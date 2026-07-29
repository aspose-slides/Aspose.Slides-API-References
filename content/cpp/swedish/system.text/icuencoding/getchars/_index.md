---
title: GetChars()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar tecknen som erhålls genom att avkoda en bytebuffert.
type: docs
weight: 66
url: /sv/system.text/icuencoding/getchars/
---
## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) metod

Hämtar tecknen som erhålls genom att avkoda en bytebuffert.

```cpp
int System::Text::ICUEncoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) för att läsa byte från. |
| byte_count | int | Storlek på inputbufferten. |
| chars | char_t * | [Buffer](../../../system/buffer/) för att skriva tecken till. |
| char_count | int | Storlek på outputbufferten. |

### Returvärde

Antal skrivna tecken.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) metod

Hämtar tecknen som erhålls genom att avkoda en bytebuffert.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) för att läsa byte från. |
| byte_index | int | Offset för inputbufferten. |
| byte_count | int | Storlek på inputbufferten. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) för att skriva tecken till. |
| char_index | int | Offset för outputbufferten. |

### Returvärde

Antal skrivna tecken.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int) metod

Hämtar tecknen som erhålls genom att avkoda en bytebuffert.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) för att läsa byte från. |
| index | int | Offset för inputbufferten. |
| count | int | Storlek på inputbufferten. |

### Returvärde

[Buffer](../../../system/buffer/) av avkodade tecken.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>) metod

Hämtar tecknen som erhålls genom att avkoda en bytebuffert.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) för att läsa byte från. |

### Returvärde

[Buffer](../../../system/buffer/) av avkodade tecken.

## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) metod

Hämtar tecknen som erhålls genom att avkoda en bytebuffert.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) för att läsa byte från. |
| byte_count | int | Storlek på inputbufferten. |
| chars | char_t * | [Buffer](../../../system/buffer/) för att skriva tecken till. |
| char_count | int | Storlek på outputbufferten. |

### Returvärde

Antal skrivna tecken.

## Se också

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [ICUEncoding](../)
* Namnrymd [System::Text](../../)
* Bibliotek [Aspose.Slides](../../../)