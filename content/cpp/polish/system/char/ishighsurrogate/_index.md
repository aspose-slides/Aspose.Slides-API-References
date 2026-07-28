---
title: IsHighSurrogate()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Określa, czy znak znajdujący się pod określonym indeksem w podanym ciągu jest jednostką kodową wysokiego surogatu UTF-16.
type: docs
weight: 40
url: /pl/system/char/ishighsurrogate/
---
## Char::IsHighSurrogate(const String\&, int) metoda

Określa, czy znak znajdujący się pod określonym indeksem w podanym ciągu jest jednostką kodową wysokiego surogatu UTF-16.

```cpp
static bool System::Char::IsHighSurrogate(const String &s, int index)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| s | const [String](../../string/)\& | Łańcuch znaków |
| index | int | Indeks w określonym ciągu znaku do przetestowania |

### Wartość zwracana

True jeśli znak pod określonym indeksem jest jednostką kodową wysokiego surogatu UTF-16, w przeciwnym razie - false

## Char::IsHighSurrogate(const char_t *, int) metoda

Określa, czy znak znajdujący się pod określonym indeksem w podanym buforze znaków jest wysokim surogatem.

```cpp
static bool System::Char::IsHighSurrogate(const char_t *str, int idx)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const char_t * | Wskaźnik na początek bufora znaków |
| idx | int | Indeks zerowy w określonym buforze znaku do przetestowania |

### Wartość zwracana

True jeśli znak pod określonym indeksem jest wysokim surogatem, w przeciwnym razie - false

## Char::IsHighSurrogate(char_t) metoda

Określa, czy podany znak jest wysokim surogatem.

```cpp
static bool System::Char::IsHighSurrogate(char_t c)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| c | char_t | Znak do przetestowania |

### Wartość zwracana

True jeśli podany znak jest wysokim surogatem, w przeciwnym razie - false

## Zobacz także

* Klasa [String](../../string/)
* Klasa [Char](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)