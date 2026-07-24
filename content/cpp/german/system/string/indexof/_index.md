---
title: IndexOf()
second_title: Aspose.Slides für C++ API-Referenz
description: Vorwärtsnachschlagen des Teilstrings.
type: docs
weight: 625
url: /de/system/string/indexof/
---
## String::IndexOf(const String\&, System::StringComparison) const Methode


Vorwärtsnachschlagen des Teilstrings.

```cpp
int System::String::IndexOf(const String &str, System::StringComparison comparison_type) const
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const [String](../)\& | Teilstring, nach dem gesucht wird. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) Modus. |

### Rückgabewert

[Index](../../index/) des zuerst gefundenen Teilstrings oder -1, wenn nicht gefunden. Für einen leeren Suchstring wird immer 0 zurückgegeben.

## String::IndexOf(char_t, int) const Methode


Vorwärtsnachschlagen des Zeichens.

```cpp
int System::String::IndexOf(char_t c, int startIndex=0) const
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| c | char_t | Zeichen, nach dem gesucht wird. |
| startIndex | int | [Index](../../index/) zum Starten der Suche bei. |

### Rückgabewert

[Index](../../index/) der ersten Zeichenposition seit startIndex oder -1, wenn nicht gefunden.

## String::IndexOf(char_t, int, int) const Methode


Vorwärtsnachschlagen des Zeichens im Teilstring.

```cpp
int System::String::IndexOf(char_t c, int startIndex, int count) const
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| c | char_t | Zeichen, nach dem gesucht wird. |
| startIndex | int | [Index](../../index/) zum Starten der Suche bei. |
| count | int | Anzahl der Zeichen, die durchsucht werden sollen. |

### Rückgabewert

[Index](../../index/) der ersten Zeichenposition seit startIndex oder -1, wenn nicht gefunden.

## String::IndexOf(const String\&, int) const Methode


Vorwärtsnachschlagen des Teilstrings.

```cpp
int System::String::IndexOf(const String &str, int startIndex=0) const
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const [String](../)\& | Teilstring, nach dem gesucht wird. |
| startIndex | int | Position im Quellstring, ab der Suche gestartet wird. |

### Rückgabewert

[Index](../../index/) des zuerst gefundenen Teilstrings oder -1, wenn nicht gefunden. Für einen leeren Suchstring wird immer startIndex zurückgegeben.

## String::IndexOf(const String\&, int, System::StringComparison) const Methode


Vorwärtsnachschlagen des Teilstrings.

```cpp
int System::String::IndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const [String](../)\& | Teilstring, nach dem gesucht wird. |
| startIndex | int | Position im Quellstring, ab der Suche gestartet wird. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) Modus. |

### Rückgabewert

[Index](../../index/) des zuerst gefundenen Teilstrings oder -1, wenn nicht gefunden. Für einen leeren Suchstring wird immer startIndex zurückgegeben.

## String::IndexOf(const String\&, int, int, System::StringComparison) const Methode


Vorwärtsnachschlagen des Teilstrings.

```cpp
int System::String::IndexOf(const String &value, int startIndex, int count, System::StringComparison comparisonType) const
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../)\& | Teilstring, nach dem gesucht wird. |
| startIndex | int | Position im Quellstring, ab der Suche gestartet wird. |
| count | int | Anzahl der Zeichen, die durchsucht werden sollen. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) Modus. |

### Rückgabewert

[Index](../../index/) des zuerst gefundenen Teilstrings oder -1, wenn nicht gefunden. Für einen leeren Suchstring wird immer startIndex zurückgegeben.

## String::IndexOf(const String\&, int, int) const Methode


Vorwärtsnachschlagen des Teilstrings.

```cpp
int System::String::IndexOf(const String &str, int startIndex, int count) const
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const [String](../)\& | Teilstring, nach dem gesucht wird. |
| startIndex | int | Position im Quellstring, ab der Suche gestartet wird. |
| count | int | Anzahl der Zeichen, die durchsucht werden sollen. |

### Rückgabewert

[Index](../../index/) des zuerst gefundenen Teilstrings oder -1, wenn nicht gefunden. Für einen leeren Suchstring wird immer startIndex zurückgegeben.

## Siehe auch

* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)