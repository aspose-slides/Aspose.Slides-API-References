---
title: IsHighSurrogate()
second_title: Aspose.Slides für C++ API Referenz
description: Bestimmt, ob das Zeichen an dem angegebenen Index in der angegebenen Zeichenkette eine UTF-16 High Surrogate-Codeeinheit ist.
type: docs
weight: 40
url: /de/system/char/ishighsurrogate/
---
## Char::IsHighSurrogate(const String\&, int) Methode

Bestimmt, ob das Zeichen an dem angegebenen Index in der angegebenen Zeichenkette ein UTF-16 High Surrogate-Codeeinheit ist.

```cpp
static bool System::Char::IsHighSurrogate(const String &s, int index)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | const [String](../../string/)\& | Eine Zeichenkette |
| index | int | Der Index in der angegebenen Zeichenkette des zu prüfenden Zeichens |

### Rückgabewert

True, wenn das Zeichen an dem angegebenen Index ein UTF-16 High Surrogate-Codeeinheit ist, sonst - false

## Char::IsHighSurrogate(const char_t *, int) Methode

Bestimmt, ob das Zeichen an dem angegebenen Index im angegebenen Zeichenpuffer ein High Surrogate ist.

```cpp
static bool System::Char::IsHighSurrogate(const char_t *str, int idx)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const char_t * | Zeiger auf den Anfang des Zeichenpuffers |
| idx | int | Ein nullbasierter Index im angegebenen Puffer des zu prüfenden Zeichens |

### Rückgabewert

True, wenn das Zeichen an dem angegebenen Index ein High Surrogate ist, sonst - false

## Char::IsHighSurrogate(char_t) Methode

Bestimmt, ob das angegebene Zeichen ein High Surrogate ist.

```cpp
static bool System::Char::IsHighSurrogate(char_t c)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| c | char_t | Das zu prüfende Zeichen |

### Rückgabewert

True, wenn das angegebene Zeichen ein High Surrogate ist, sonst - false

## Siehe auch

* Klasse [String](../../string/)
* Klasse [Char](../)
* Namespace [System](../../)
* Bibliothek [Aspose.Slides](../../../)