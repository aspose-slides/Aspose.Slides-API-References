---
title: GetBytes()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar de byte som resultat av att koda en teckenbuffert.
type: docs
weight: 248
url: /sv/system.text/encoding/getbytes/
---
## Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) metod


Hämtar de byte som resultat av att koda en teckenbuffert.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tecken att koda. |
| char_index | int | Början på teckenavsnittet. |
| char_count | int | Antal tecken att konvertera. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) för att lagra tecken i. |
| byte_index | int | Utdata buffertoffset. |

### Returvärde

Antal skrivna byte.

## Encoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) metod


Hämtar de byte som resultat av att koda en teckenbuffert.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Tecken att koda. |
| char_index | int | Början på teckenavsnittet. |
| char_count | int | Antal tecken att konvertera. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) för att lagra tecken i. |
| byte_index | int | Utdata buffertoffset. |

### Returvärde

Antal skrivna byte.

## Encoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) metod


Hämtar de byte som resultat av att koda en teckenbuffert.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | Tecken att koda. |
| char_index | int | Början på teckenavsnittet. |
| char_count | int | Antal tecken att konvertera. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) för att lagra tecken i. |
| byte_index | int | Utdata buffertoffset. |

### Returvärde

Antal skrivna byte.

## Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) metod


Hämtar de byte som resultat av att koda en teckenbuffert.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) för att koda. |
| char_index | int | Början på teckenavsnittet. |
| char_count | int | Antal tecken att konvertera. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) för att lagra tecken i. |
| byte_index | int | Utdata buffertoffset. |

### Returvärde

Antal skrivna byte.

## Encoding::GetBytes(const String\&) metod


Hämtar de byte som resultat av att koda en teckenbuffert.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) för att koda. |

### Returvärde

[Buffer](../../../system/buffer/) som innehåller representation av de kodade tecknen.

## Encoding::GetBytes(ArrayPtr\<char_t\>, int, int) metod


Hämtar de byte som resultat av att koda en teckenbuffert.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tecken att koda. |
| index | int | Början på teckenavsnittet. |
| count | int | Antal tecken att konvertera. |

### Returvärde

[Buffer](../../../system/buffer/) som innehåller representation av de kodade tecknen.

## Encoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) metod


Hämtar de byte som resultat av att koda en teckenbuffert.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | Tecken att koda. |
| index | int | Början på teckenavsnittet. |
| count | int | Antal tecken att konvertera. |

### Returvärde

[Buffer](../../../system/buffer/) som innehåller representation av de kodade tecknen.

## Encoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) metod


Hämtar de byte som resultat av att koda en teckenbuffert.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Tecken att koda. |
| index | int | Början på teckenavsnittet. |
| count | int | Antal tecken att konvertera. |

### Returvärde

[Buffer](../../../system/buffer/) som innehåller representation av de kodade tecknen.

## Encoding::GetBytes(ArrayPtr\<char_t\>) metod


Hämtar de byte som resultat av att koda en teckenbuffert.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tecken att koda. |

### Returvärde

[Buffer](../../../system/buffer/) som innehåller representation av de kodade tecknen.

## Encoding::GetBytes(const char_t *, int, uint8_t *, int) metod


Hämtar de byte som resultat av att koda en teckenbuffert.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chars | const char_t * | Tecken att koda. |
| char_count | int | Antal tecken att konvertera. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) för att lagra tecken i. |
| byte_count | int | Storlek på utdata buffert. |

### Returvärde

Antal skrivna byte.

## Se även

* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Klass [Encoding](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::Text](../../)
* Bibliotek [Aspose.Slides](../../../)