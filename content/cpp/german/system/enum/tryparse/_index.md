---
title: TryParse()
second_title: Aspose.Slides für C++ API Referenz
description: Versucht, die angegebene Zeichenkette in die entsprechende Aufzählungskonstante umzuwandeln.
type: docs
weight: 79
url: /de/system/enum/tryparse/
---
## Enum::TryParse(const String\&, E\&) Methode


Versucht, die angegebene Zeichenkette in die entsprechende Aufzählungskonstante umzuwandeln.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, E &result)
```


### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) das interpretiert wird, als den Namen der Aufzählungskonstante zu enthalten |
| result | E\& | Der Ausgabeparameter, der bei erfolgreicher Konvertierung das Ergebnis der Konvertierung der Funktion enthält |

### Return Value

Wahr, wenn die Konvertierung erfolgreich war, sonst - falsch

## Enum::TryParse(const String\&, bool, E\&) Methode


Versucht, die angegebene Zeichenkette in die entsprechende Aufzählungskonstante umzuwandeln.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, bool ignoreCase, E &result)
```


### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) das interpretiert wird, als den Namen der Aufzählungskonstante zu enthalten |
| ignoreCase | **bool** | Gibt an, ob die Groß-/Kleinschreibung beim Interpretieren der Zeichenkette ignoriert werden soll |
| result | E\& | Der Ausgabeparameter, der bei erfolgreicher Konvertierung das Ergebnis der Konvertierung der Funktionsrückgabe enthält |

### Return Value

Wahr, wenn die Konvertierung erfolgreich war, sonst - falsch

## Siehe auch

* Klasse [String](../../string/)
* Struktur [Enum](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)