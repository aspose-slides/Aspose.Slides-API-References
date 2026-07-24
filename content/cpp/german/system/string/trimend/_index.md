---
title: TrimEnd()
second_title: Aspose.Slides für C++ API-Referenz
description: Entfernt alle Leerzeichen am Ende der Zeichenkette.
type: docs
weight: 703
url: /de/system/string/trimend/
---
## String::TrimEnd() const Methode

Entfernt alle Leerzeichen-Zeichen vom Ende der Zeichenkette.

```cpp
String System::String::TrimEnd() const
```

### Rückgabewert

[String](../) ohne Leerzeichen am Anfang.

## String::TrimEnd(char_t) const Methode

Entfernt alle Vorkommen des übergebenen Zeichens vom Ende der Zeichenkette.

```cpp
String System::String::TrimEnd(char_t ch) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ch | char_t | Symbol zum Entfernen. |

### Rückgabewert

Entfernungsergebnis.

## String::TrimEnd(const String\&) const Methode

Entfernt alle Vorkommen der übergebenen Zeichen vom Ende der Zeichenkette.

```cpp
String System::String::TrimEnd(const String &anyOf) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) der zu entfernenden Zeichen. |

### Rückgabewert

[String](../) ohne entfernte Zeichen.

## String::TrimEnd(const ArrayPtr\<char_t\>\&) const Methode

Entfernt alle Vorkommen der übergebenen Zeichen vom Ende der Zeichenkette.

```cpp
String System::String::TrimEnd(const ArrayPtr<char_t> &anyOf) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) der zu entfernenden Zeichen. |

### Rückgabewert

[String](../) ohne entfernte Zeichen.

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [String](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)