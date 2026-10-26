---
title: GetByteCount()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar antalet tecken som behövs för att koda en teckenbuffer.
type: docs
weight: 157
url: /sv/system.text/utf7encoding/getbytecount/
---
## UTF7Encoding::GetByteCount(const char_t *, int) metod

Hämtar antalet tecken som behövs för att koda en teckenbuffer.

```cpp
int System::Text::UTF7Encoding::GetByteCount(const char_t *chars, int count) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chars | const char_t * | Teckenbuffer. |
| count | int | [Buffer](../../../system/buffer/) storlek. |

### Returvärde

Krävt buffertstorlek.

## UTF7Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) metod

Hämtar antalet tecken som behövs för att koda en teckenbuffer.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Teckenbuffer. |
| index | int | Uttagets början. |
| count | int | Uttagets storlek. |

### Returvärde

Krävt buffertstorlek.

## UTF7Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) metod

Hämtar antalet tecken som behövs för att koda en teckenbuffer.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Teckenbuffer. |
| index | int | Uttagets början. |
| count | int | Uttagets storlek. |

### Returvärde

Krävt buffertstorlek.

## UTF7Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) metod

Hämtar antalet tecken som behövs för att koda en teckenbuffer.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Teckenbuffer. |
| index | int | Uttagets början. |
| count | int | Uttagets storlek. |

### Returvärde

Krävt buffertstorlek.

## UTF7Encoding::GetByteCount(const String\&) metod

Hämtar antalet tecken som behövs för att koda en sträng.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) att koda. |

### Returvärde

Krävt buffertstorlek.

## UTF7Encoding::GetByteCount(ArrayPtr\<char_t\>) metod

Hämtar antalet tecken som behövs för att koda en teckenbuffer.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Teckenbuffer. |

### Returvärde

Krävt buffertstorlek.

## UTF7Encoding::GetByteCount(const char_t *, int) metod

Hämtar antalet tecken som behövs för att koda en teckenbuffer.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chars | const char_t * | Teckenbuffer. |
| count | int | [Buffer](../../../system/buffer/) storlek. |

### Returvärde

Krävt buffertstorlek.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [UTF7Encoding](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::Text](../../)
* Bibliotek [Aspose.Slides](../../../)