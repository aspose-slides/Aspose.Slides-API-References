---
title: GetByteCount()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt die Anzahl der Zeichen, die zum Codieren eines Zeichenpuffers benötigt werden.
type: docs
weight: 235
url: /de/system.text/encoding/getbytecount/
---
## Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) Methode

Ermittelt die Anzahl der Zeichen, die zum Codieren eines Zeichenpuffers erforderlich sind.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Zeichenpuffer. |
| index | int | Slice-Beginn. |
| count | int | Slice-Größe. |

### Rückgabewert

Erforderliche Puffergröße.

## Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) Methode

Ermittelt die Anzahl der Zeichen, die zum Codieren eines Zeichenpuffers erforderlich sind.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Zeichenpuffer. |
| index | int | Slice-Beginn. |
| count | int | Slice-Größe. |

### Rückgabewert

Erforderliche Puffergröße.

## Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) Methode

Ermittelt die Anzahl der Zeichen, die zum Codieren eines Zeichenpuffers erforderlich sind.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Zeichenpuffer. |
| index | int | Slice-Beginn. |
| count | int | Slice-Größe. |

### Rückgabewert

Erforderliche Puffergröße.

## Encoding::GetByteCount(const String\&) Methode

Ermittelt die Anzahl der Zeichen, die zum Codieren einer Zeichenkette erforderlich sind.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) zum Kodieren. |

### Rückgabewert

Erforderliche Puffergröße.

## Encoding::GetByteCount(ArrayPtr\<char_t\>) Methode

Ermittelt die Anzahl der Zeichen, die zum Codieren eines Zeichenpuffers erforderlich sind.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Zeichenpuffer. |

### Rückgabewert

Erforderliche Puffergröße.

## Encoding::GetByteCount(const char_t *, int) Methode

Ermittelt die Anzahl der Zeichen, die zum Codieren eines Zeichenpuffers erforderlich sind.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | const char_t * | Zeichenpuffer. |
| count | int | [Buffer](../../../system/buffer/) Größe. |

### Rückgabewert

Erforderliche Puffergröße.

## Siehe Auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Encoding](../)
* Klasse [String](../../../system/string/)
* Namensraum [System::Text](../../)
* Library [Aspose.Slides](../../../)