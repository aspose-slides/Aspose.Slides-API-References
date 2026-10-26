---
title: Trim()
second_title: Aspose.Slides für C++ API-Referenz
description: Entfernt alle Leerzeichen-Charaktere sowohl am Anfang als auch am Ende der Zeichenkette.
type: docs
weight: 677
url: /de/system/string/trim/
---
## String::Trim() const Methode


Entfernt alle Leerzeichen-Charaktere sowohl am Anfang als auch am Ende der Zeichenkette.

```cpp
String System::String::Trim() const
```


### Rückgabewert

[String](../) ohne Leerzeichen am Anfang oder Ende.

## String::Trim(char_t) const Methode


Entfernt alle Vorkommen des übergebenen Zeichens sowohl am Anfang als auch am Ende der Zeichenkette.

```cpp
String System::String::Trim(char_t ch) const
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ch | char_t | Zu entfernendes Symbol. |

### Rückgabewert

Entfernungsergebnis.

## String::Trim(const String\&) const Methode


Entfernt alle Vorkommen der übergebenen Zeichen sowohl am Anfang als auch am Ende der Zeichenkette.

```cpp
String System::String::Trim(const String &anyOf) const
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) von Zeichen zum Entfernen. |

### Rückgabewert

[String](../) ohne entfernte Zeichen.

## String::Trim(const ArrayPtr\<char_t\>\&) const Methode


Entfernt alle Vorkommen der übergebenen Zeichen sowohl am Anfang als auch am Ende der Zeichenkette.

```cpp
String System::String::Trim(const ArrayPtr<char_t> &anyOf) const
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) von Zeichen zum Entfernen. |

### Rückgabewert

[String](../) ohne entfernte Zeichen.

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [String](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)