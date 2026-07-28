---
title: IsSurrogate()
second_title: Aspose.Slides dla C++ - referencja API
description: Określa, czy podany znak jest jednostką kodową surrogatową UTF-16.
type: docs
weight: 14
url: /pl/system/char/issurrogate/
---
## Char::IsSurrogate(char_t) method

Określa, czy podany znak jest jednostką kodową surrogatową UTF-16.

```cpp
static bool System::Char::IsSurrogate(char_t c)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| c | char_t | Znak |

### Wartość zwracana

True if the specified character is a UTF-16 surrogate code unit, otherwise - false

## Char::IsSurrogate(const String\&, int) method

Określa, czy znak podanym indeksie w podanym ciągu jest jednostką kodową surrogatową UTF-16.

```cpp
static bool System::Char::IsSurrogate(const String &s, int index)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| s | const [String](../../string/)\& | Ciąg |
| index | int | Indeks znaku w podanym ciągu |

### Wartość zwracana

True if the character at the specified index is a UTF-16 surrogate code unit, otherwise - false

## Zobacz także

* Klasa [Char](../)
* Klasa [String](../../string/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)