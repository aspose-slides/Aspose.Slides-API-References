---
title: IsSurrogatePair()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer om de två angivna tecknen utgör ett UTF-16-surrogatpar.
type: docs
weight: 27
url: /sv/system/char/issurrogatepair/
---
## Char::IsSurrogatePair(char_t, char_t) metod

Bestämmer om de två angivna tecknen utgör ett UTF-16-surrogatpar.

```cpp
static bool System::Char::IsSurrogatePair(char_t highSurrogate, char_t lowSurrogate)
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| highSurrogate | char_t | Ett tecken som testas för att vara ett högt surrogat |
| lowSurrogate | char_t | Ett tecken som testas för att vara ett lågt surrogat |

### Returvärde

True if the specified characters form a surrogate pair, otherwise - false

## Char::IsSurrogatePair(const String\&, int) metod

Bestämmer om två på varandra följande tecken i den angivna teckenbufferten är ett surrogatpar.

```cpp
static bool System::Char::IsSurrogatePair(const String &str, int index)
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../string/)\& | En sträng |
| index | int | Ett nollbaserat index i den angivna bufferten där den teckensekvens som ska testas börjar |

### Returvärde

True if the specified characters are a surrogate pair, otherwise - false

## Se också

* Klass [Char](../)
* Klass [String](../../string/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)