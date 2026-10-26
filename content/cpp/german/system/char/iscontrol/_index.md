---
title: IsControl()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob das Zeichen am angegebenen Index im angegebenen Zeichenpuffer als Unicode-Steuerzeichen klassifiziert wird.
type: docs
weight: 66
url: /de/system/char/iscontrol/
---
## Char::IsControl(const char_t *, int) Methode


Bestimmt, ob das Zeichen am angegebenen Index im angegebenen Zeichenpuffer als Unicode-Steuerzeichen klassifiziert wird.

```cpp
static bool System::Char::IsControl(const char_t *str, int idx)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const char_t * | Zeiger auf den Anfang des Zeichenpuffers |
| idx | int | Ein nullbasierter Index im angegebenen Puffer des zu testenden Zeichens |

### Rückgabewert

True if the character at the specified index is a Unicode control character, otherwise - false

## Char::IsControl(char_t) Methode


Bestimmt, ob das angegebene Zeichen als Unicode-Steuerzeichen klassifiziert wird.

```cpp
static bool System::Char::IsControl(char_t c)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| c | char_t | Das zu testende Zeichen |

### Rückgabewert

True if the specified character is a Unicode control character, otherwise - false

## Siehe auch

* Klasse [Char](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)