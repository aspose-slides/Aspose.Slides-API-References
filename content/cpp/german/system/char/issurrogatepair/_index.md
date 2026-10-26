---
title: IsSurrogatePair()
second_title: Aspose.Slides für C++ API Referenz
description: Bestimmt, ob die beiden angegebenen Zeichen ein UTF-16 Surrogat-Paar bilden.
type: docs
weight: 27
url: /de/system/char/issurrogatepair/
---
## Char::IsSurrogatePair(char_t, char_t) Methode

Bestimmt, ob die beiden angegebenen Zeichen ein UTF-16-Surrogat-Paar bilden.

```cpp
static bool System::Char::IsSurrogatePair(char_t highSurrogate, char_t lowSurrogate)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| highSurrogate | char_t | Ein Zeichen, das auf ein High Surrogate geprüft wird |
| lowSurrogate | char_t | Ein Zeichen, das auf ein Low Surrogate geprüft wird |

### Rückgabewert

True, wenn die angegebenen Zeichen ein Surrogat-Paar bilden, sonst - false

## Char::IsSurrogatePair(const String\&, int) Methode

Bestimmt, ob zwei aufeinanderfolgende Zeichen im angegebenen Zeichenpuffer ein Surrogat-Paar bilden.

```cpp
static bool System::Char::IsSurrogatePair(const String &str, int index)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const [String](../../string/)\& | Eine Zeichenkette |
| index | int | Ein nullbasierter Index im angegebenen Puffer, an dem die zu testende Zeichenfolge beginnt |

### Rückgabewert

True, wenn die angegebenen Zeichen ein Surrogat-Paar bilden, sonst - false

## Siehe auch

* Klasse [Char](../)
* Klasse [String](../../string/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)