---
title: GetByteCount()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Anzahl der Zeichen zurück, die zum Codieren eines Zeichenpuffers benötigt werden.
type: docs
weight: 27
url: /de/system.text/icuencoding/getbytecount/
---
## ICUEncoding::GetByteCount(const char_t *, int) Methode

Gibt die Anzahl der Zeichen zurück, die zum Codieren eines Zeichenpuffers benötigt werden.

```cpp
int System::Text::ICUEncoding::GetByteCount(const char_t *chars, int count) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | const char_t * | Zeichenpuffer. |
| count | int | [Buffer](../../../system/buffer/) Größe. |

### Rückgabewert

Erforderliche Puffergröße.

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>, int, int) Methode

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) Methode

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) Methode

RTTI.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

## ICUEncoding::GetByteCount(const String\&) Methode

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>) Methode

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

## ICUEncoding::GetByteCount(const char_t *, int) Methode

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ICUEncoding](../)
* Klasse [String](../../../system/string/)
* Namensraum [System::Text](../../)
* Bibliothek [Aspose.Slides](../../../)