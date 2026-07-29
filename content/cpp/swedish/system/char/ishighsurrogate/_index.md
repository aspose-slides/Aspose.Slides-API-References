---
title: IsHighSurrogate()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer om tecknet på det angivna indexet i den angivna strängen är en UTF-16 hög surrogatkod enhet.
type: docs
weight: 40
url: /sv/system/char/ishighsurrogate/
---
## Char::IsHighSurrogate(const String\&, int) metod

Bestämmer om tecknet på det angivna indexet i den angivna strängen är en UTF-16 hög surrogatkod enhet.

```cpp
static bool System::Char::IsHighSurrogate(const String &s, int index)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const [String](../../string/)\& | En sträng |
| index | int | Index i den angivna strängen för tecknet som ska testas |

### Returvärde

Sant om tecknet på det angivna indexet är en UTF-16 hög surrogatkod enhet, annars - falskt

## Char::IsHighSurrogate(const char_t *, int) metod

Bestämmer om tecknet på det angivna indexet i den angivna teckenbufferten är ett högsurrogat.

```cpp
static bool System::Char::IsHighSurrogate(const char_t *str, int idx)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const char_t * | Pekare till början av teckenbufferten |
| idx | int | Nollbaserat index i den angivna bufferten för tecknet som ska testas |

### Returvärde

Sant om tecknet på det angivna indexet är ett högsurrogat, annars - falskt

## Char::IsHighSurrogate(char_t) metod

Bestämmer om det angivna tecknet är ett högsurrogat.

```cpp
static bool System::Char::IsHighSurrogate(char_t c)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| c | char_t | Tecknet som ska testas |

### Returvärde

Sant om det angivna tecknet är ett högsurrogat, annars - falskt

## Se även

* Klass [String](../../string/)
* Klass [Char](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)