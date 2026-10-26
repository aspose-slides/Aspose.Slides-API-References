---
title: GetByteCount()
second_title: Aspose.Slides för C++ API-referens
description: Hämta antalet tecken som behövs för att koda en teckenbuffert.
type: docs
weight: 235
url: /sv/system.text/encoding/getbytecount/
---
## Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) metod

Get the number of characters needed to encode a character buffer.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Teckenbuffert. |
| index | int | Delens början. |
| count | int | Delens storlek. |

### Returvärde

Krävd buffertstorlek.

## Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) metod

Get the number of characters needed to encode a character buffer.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Teckenbuffert. |
| index | int | Delens början. |
| count | int | Delens storlek. |

### Returvärde

Krävd buffertstorlek.

## Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) metod

Get the number of characters needed to encode a character buffer.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Teckenbuffert. |
| index | int | Delens början. |
| count | int | Delens storlek. |

### Returvärde

Krävd buffertstorlek.

## Encoding::GetByteCount(const String\&) metod

Get the number of characters needed to encode a string.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) för att koda. |

### Returvärde

Krävd buffertstorlek.

## Encoding::GetByteCount(ArrayPtr\<char_t\>) metod

Get the number of characters needed to encode a character buffer.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Teckenbuffert. |

### Returvärde

Krävd buffertstorlek.

## Encoding::GetByteCount(const char_t *, int) metod

Get the number of characters needed to encode a character buffer.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chars | const char_t * | Teckenbuffert. |
| count | int | [Buffer](../../../system/buffer/) storlek. |

### Returvärde

Krävd buffertstorlek.

## Se även

* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Klass [Encoding](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::Text](../../)
* Bibliotek [Aspose.Slides](../../../)