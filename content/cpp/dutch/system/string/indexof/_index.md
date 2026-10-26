---
title: IndexOf()
second_title: Aspose.Slides voor C++ API-referentie
description: Voorwaartse zoekopdracht naar substring.
type: docs
weight: 625
url: /nl/system/string/indexof/
---
## String::IndexOf(const String\&, System::StringComparison) const methode


Voorwaartse zoekopdracht naar substring.

```cpp
int System::String::IndexOf(const String &str, System::StringComparison comparison_type) const
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | Substring om naar te zoeken. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modus. |

### Retourwaarde

[Index](../../index/) van de eerste gevonden substring of -1 als niet gevonden. Voor een lege zoekstring wordt altijd 0 geretourneerd.

## String::IndexOf(char_t, int) const methode


Voorwaartse zoekopdracht naar teken.

```cpp
int System::String::IndexOf(char_t c, int startIndex=0) const
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | Teken om naar te zoeken. |
| startIndex | int | [Index](../../index/) om de zoekopdracht te starten op. |

### Retourwaarde

[Index](../../index/) van de eerste tekenpositie vanaf startIndex of -1 als niet gevonden.

## String::IndexOf(char_t, int, int) const methode


Voorwaartse zoekopdracht naar teken in substring.

```cpp
int System::String::IndexOf(char_t c, int startIndex, int count) const
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | Teken om naar te zoeken. |
| startIndex | int | [Index](../../index/) om de zoekopdracht te starten op. |
| count | int | Aantal tekens om door te zoeken. |

### Retourwaarde

[Index](../../index/) van de eerste tekenpositie vanaf startIndex of -1 als niet gevonden.

## String::IndexOf(const String\&, int) const methode


Voorwaartse zoekopdracht naar substring.

```cpp
int System::String::IndexOf(const String &str, int startIndex=0) const
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | Substring om naar te zoeken. |
| startIndex | int | Positie in de bronstring om de zoekopdracht te starten. |

### Retourwaarde

[Index](../../index/) van de eerste gevonden substring of -1 als niet gevonden. Voor een lege zoekstring wordt altijd startIndex geretourneerd.

## String::IndexOf(const String\&, int, System::StringComparison) const methode


Voorwaartse zoekopdracht naar substring.

```cpp
int System::String::IndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | Substring om naar te zoeken. |
| startIndex | int | Positie in de bronstring om de zoekopdracht te starten. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modus. |

### Retourwaarde

[Index](../../index/) van de eerste gevonden substring of -1 als niet gevonden. Voor een lege zoekstring wordt altijd startIndex geretourneerd.

## String::IndexOf(const String\&, int, int, System::StringComparison) const methode


Voorwaartse zoekopdracht naar substring.

```cpp
int System::String::IndexOf(const String &value, int startIndex, int count, System::StringComparison comparisonType) const
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | Substring om naar te zoeken. |
| startIndex | int | Positie in de bronstring om de zoekopdracht te starten. |
| count | int | aantal tekens om door te zoeken. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modus. |

### Retourwaarde

[Index](../../index/) van de eerste gevonden substring of -1 als niet gevonden. Voor een lege zoekstring wordt altijd startIndex geretourneerd.

## String::IndexOf(const String\&, int, int) const methode


Voorwaartse zoekopdracht naar substring.

```cpp
int System::String::IndexOf(const String &str, int startIndex, int count) const
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | Substring om naar te zoeken. |
| startIndex | int | Positie in de bronstring om de zoekopdracht te starten. |
| count | int | aantal tekens om door te zoeken. |

### Retourwaarde

[Index](../../index/) van de eerste gevonden substring of -1 als niet gevonden. Voor een lege zoekstring wordt altijd startIndex geretourneerd.

## Zie ook

* Enum [StringComparison](../../stringcomparison/)
* Klasse [String](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)