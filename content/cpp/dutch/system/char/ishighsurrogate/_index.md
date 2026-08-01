---
title: IsHighSurrogate()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt of het teken op de opgegeven index in de opgegeven tekenreeks een UTF-16 high surrogate code-eenheid is.
type: docs
weight: 40
url: /nl/system/char/ishighsurrogate/
---
## Char::IsHighSurrogate(const String\&, int) methode


Bepaalt of het teken op de opgegeven index in de opgegeven tekenreeks een UTF-16 high surrogate code-eenheid is.


```cpp
static bool System::Char::IsHighSurrogate(const String &s, int index)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | const [String](../../string/)\& | Een tekenreeks |
| index | int | De index in de opgegeven tekenreeks van het te testen teken |

### Retourwaarde

True als het teken op de opgegeven index een UTF-16 high surrogate code-eenheid is, anders - false

## Char::IsHighSurrogate(const char_t *, int) methode


Bepaalt of het teken op de opgegeven index in de opgegeven tekenbuffer een high surrogate is.


```cpp
static bool System::Char::IsHighSurrogate(const char_t *str, int idx)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const char_t * | Pointer naar het begin van de tekenbuffer |
| idx | int | Een nulgebaseerde index in de opgegeven buffer van het te testen teken |

### Retourwaarde

True als het teken op de opgegeven index een high surrogate is, anders - false

## Char::IsHighSurrogate(char_t) methode


Bepaalt of het opgegeven teken een high surrogate is.


```cpp
static bool System::Char::IsHighSurrogate(char_t c)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| c | char_t | Het te testen teken |

### Retourwaarde

True als het opgegeven teken een high surrogate is, anders - false

## Zie ook

* Klasse [String](../../string/)
* Klasse [Char](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)