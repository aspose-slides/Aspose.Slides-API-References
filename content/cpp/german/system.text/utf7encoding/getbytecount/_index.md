---
title: GetByteCount()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt die Anzahl der Zeichen, die zum Codieren eines Zeichenpuffers benötigt werden.
type: docs
weight: 157
url: /de/system.text/utf7encoding/getbytecount/
---
## UTF7Encoding::GetByteCount(const char_t *, int) Methode

Ermittelt die Anzahl der Zeichen, die zum Codieren eines Zeichenpuffers benötigt werden.

```cpp
int System::Text::UTF7Encoding::GetByteCount(const char_t *chars, int count) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | const char_t * | Zeichenpuffer. |
| count | int | [Buffer](../../../system/buffer/) Größe. |

### Rückgabewert

Erforderliche Puffergröße.

## UTF7Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) Methode

Ermittelt die Anzahl der Zeichen, die zum Codieren eines Zeichenpuffers benötigt werden.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Zeichenpuffer. |
| index | int | Start des Ausschnitts. |
| count | int | Ausschnitt-Größe. |

### Rückgabewert

Erforderliche Puffergröße.

## UTF7Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) Methode

Ermittelt die Anzahl der Zeichen, die zum Codieren eines Zeichenpuffers benötigt werden.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Zeichenpuffer. |
| index | int | Start des Ausschnitts. |
| count | int | Ausschnitt-Größe. |

### Rückgabewert

Erforderliche Puffergröße.

## UTF7Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) Methode

Ermittelt die Anzahl der Zeichen, die zum Codieren eines Zeichenpuffers benötigt werden.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Zeichenpuffer. |
| index | int | Start des Ausschnitts. |
| count | int | Ausschnitt-Größe. |

### Rückgabewert

Erforderliche Puffergröße.

## UTF7Encoding::GetByteCount(const String\&) Methode

Ermittelt die Anzahl der Zeichen, die zum Codieren einer Zeichenkette benötigt werden.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) zum Codieren. |

### Rückgabewert

Erforderliche Puffergröße.

## UTF7Encoding::GetByteCount(ArrayPtr\<char_t\>) Methode

Ermittelt die Anzahl der Zeichen, die zum Codieren eines Zeichenpuffers benötigt werden.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Zeichenpuffer. |

### Rückgabewert

Erforderliche Puffergröße.

## UTF7Encoding::GetByteCount(const char_t *, int) Methode

Ermittelt die Anzahl der Zeichen, die zum Codieren eines Zeichenpuffers benötigt werden.

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

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [UTF7Encoding](../)
* Klasse [String](../../../system/string/)
* Namensraum [System::Text](../../)
* Library [Aspose.Slides](../../../)