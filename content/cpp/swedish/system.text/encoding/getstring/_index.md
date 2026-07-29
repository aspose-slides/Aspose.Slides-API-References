---
title: GetString()
second_title: Aspose.Slides för C++ API-referens
description: Avkodar en buffert av byte till en sträng.
type: docs
weight: 313
url: /sv/system.text/encoding/getstring/
---
## Encoding::GetString(uint8_t *, int) metod


Avkodar en buffert av byte till en sträng.

```cpp
virtual String System::Text::Encoding::GetString(uint8_t *bytes, int byte_count)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) för att läsa byte från. |
| byte_count | int | Storlek på indatabuffert. |

### Returvärde

[String](../../../system/string/) av avkodade tecken.

## Encoding::GetString(const ReadOnlySpan\<uint8_t\>\&) metod


Avkodar en buffert av byte till en sträng.

```cpp
String System::Text::Encoding::GetString(const ReadOnlySpan<uint8_t> &bytes)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | const [ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) för att läsa byte från. |

### Returvärde

[String](../../../system/string/) av avkodade tecken.

## Encoding::GetString(ArrayPtr\<uint8_t\>) metod


Avkodar en buffert av byte till en sträng.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) för att läsa byte från. |

### Returvärde

[String](../../../system/string/) av avkodade tecken.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&) metod


Avkodar en buffert av byte till en sträng.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) för att läsa byte från. |

### Returvärde

[String](../../../system/string/) av avkodade tecken.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>\&) metod


Avkodar en buffert av byte till en sträng.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> &bytes)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | [Buffer](../../../system/buffer/) för att läsa byte från. |

### Returvärde

[String](../../../system/string/) av avkodade tecken.

## Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) metod


Avkodar en buffert av byte till en sträng.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) för att läsa byte från. |
| index | int | Indatabuffertens förskjutning. |
| count | int | Storlek på indatabuffert. |

### Returvärde

[String](../../../system/string/) av avkodade tecken.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&, int, int) metod


Avkodar en buffert av byte till en sträng.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes, int index, int count)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) för att läsa byte från. |
| index | int | Indatabuffertens förskjutning. |
| count | int | Storlek på indatabuffert. |

### Returvärde

[String](../../../system/string/) av avkodade tecken.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>, int, int) metod


Avkodar en buffert av byte till en sträng.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> bytes, int index, int count)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\> | [Buffer](../../../system/buffer/) för att läsa byte från. |
| index | int | Indatabuffertens förskjutning. |
| count | int | Storlek på indatabuffert. |

### Returvärde

[String](../../../system/string/) av avkodade tecken.

## Se även

* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Klass [String](../../../system/string/)
* Klass [Encoding](../)
* Klass [ReadOnlySpan](../../../system/readonlyspan/)
* Namnrymd [System::Text](../../)
* Bibliotek [Aspose.Slides](../../../)