---
title: LastIndexOf()
second_title: Aspose.Slides für C++ API-Referenz
description: Rückwärtssuche des Teilstrings.
type: docs
weight: 651
url: /de/system/string/lastindexof/
---
## String::LastIndexOf(const String\&, int) const Methode

Rückwärtssuche des Teilstrings.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex=INT32_MAX) const
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const [String](../)\& | Zu suchender Teilstring. |
| startIndex | int | Position im Quellstring, ab der die Suche gestartet wird. |

### Rückgabewert

[Index](../../index/) des zuletzt gefundenen Teilstrings oder -1, wenn nicht gefunden. Für einen leeren Suchstring wird immer die Stringlänge zurückgegeben.

## String::LastIndexOf(const String\&, System::StringComparison) const Methode

Rückwärtssuche des Teilstrings.

```cpp
int System::String::LastIndexOf(const String &str, System::StringComparison comparison_type) const
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const [String](../)\& | Zu suchender Teilstring. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) Modus. |

### Rückgabewert

[Index](../../index/) des zuletzt gefundenen Teilstrings oder -1, wenn nicht gefunden. Für einen leeren Suchstring wird immer die Stringlänge zurückgegeben.

## String::LastIndexOf(const String\&, int, System::StringComparison) const Methode

Rückwärtssuche des Teilstrings.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const [String](../)\& | Zu suchender Teilstring. |
| startIndex | int | Position im Quellstring, ab der die Suche gestartet wird. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) Modus. |

### Rückgabewert

[Index](../../index/) des zuletzt gefundenen Teilstrings oder -1, wenn nicht gefunden. Für einen leeren Suchstring wird immer die Stringlänge zurückgegeben.

## String::LastIndexOf(const String\&, int, int, StringComparison) const Methode

Rückwärtssuche des Teilstrings.

```cpp
int System::String::LastIndexOf(const String &value, int startIndex, int count, StringComparison comparisonType) const
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../)\& | Zu suchender Teilstring. |
| startIndex | int | Position im Quellstring, ab der die Suche gestartet wird. |
| count | int | Anzahl der zu durchsuchenden Zeichen. |
| comparisonType | [StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) Modus. |

### Rückgabewert

[Index](../../index/) des zuletzt gefundenen Teilstrings oder -1, wenn nicht gefunden. Für einen leeren Suchstring wird immer startIndex+count zurückgegeben.

## String::LastIndexOf(char_t) const Methode

Rückwärtssuche eines Zeichens.

```cpp
int System::String::LastIndexOf(char_t value) const
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | char_t | Zu suchendes Zeichen. |

### Rückgabewert

[Index](../../index/) der letzten Zeichenposition oder -1, wenn nicht gefunden.

## String::LastIndexOf(char_t, int32_t) const Methode

Rückwärtssuche eines Zeichens.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex) const
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | char_t | Zu suchendes Zeichen. |
| startIndex | **int32_t** | [Index](../../index/) um die Suche zu starten. |

### Rückgabewert

[Index](../../index/) der letzten Zeichenposition seit startIndex oder -1, wenn nicht gefunden.

## String::LastIndexOf(char_t, int32_t, int32_t) const Methode

Rückwärtssuche eines Zeichens.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex, int32_t count) const
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | char_t | Zu suchendes Zeichen. |
| startIndex | **int32_t** | [Index](../../index/) um die Suche zu starten. |
| count | **int32_t** | Anzahl der zu durchsuchenden Zeichen. |

### Rückgabewert

[Index](../../index/) der letzten Zeichenposition seit startIndex oder -1, wenn nicht gefunden.

## Siehe auch

* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)