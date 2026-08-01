---
title: LastIndexOf()
second_title: Aspose.Slides voor C++ API-referentie
description: Achterwaartse substring-zoekopdracht.
type: docs
weight: 651
url: /nl/system/string/lastindexof/
---
## String::LastIndexOf(const String\&, int) const method

Achterwaartse substring-zoekopdracht.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex=INT32_MAX) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const [String](../)\& | Substring om te zoeken. |
| startIndex | int | Positie in de bronstring om de zoekopdracht te starten. |

### Retourwaarde

[Index](../../index/) van de laatst gevonden substring of -1 indien niet gevonden. Voor een lege zoekstring retourneert altijd de lengte van de string.

## String::LastIndexOf(const String\&, System::StringComparison) const method

Achterwaartse substring-zoekopdracht.

```cpp
int System::String::LastIndexOf(const String &str, System::StringComparison comparison_type) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const [String](../)\& | Substring om te zoeken. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modus. |

### Retourwaarde

[Index](../../index/) van de laatst gevonden substring of -1 indien niet gevonden. Voor een lege zoekstring retourneert altijd de lengte van de string.

## String::LastIndexOf(const String\&, int, System::StringComparison) const method

Achterwaartse substring-zoekopdracht.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const [String](../)\& | Substring om te zoeken. |
| startIndex | int | Positie in de bronstring om de zoekopdracht te starten. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modus. |

### Retourwaarde

[Index](../../index/) van de laatst gevonden substring of -1 indien niet gevonden. Voor een lege zoekstring retourneert altijd de lengte van de string.

## String::LastIndexOf(const String\&, int, int, StringComparison) const method

Achterwaartse substring-zoekopdracht.

```cpp
int System::String::LastIndexOf(const String &value, int startIndex, int count, StringComparison comparisonType) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../)\& | Substring om te zoeken. |
| startIndex | int | Positie in de bronstring om de zoekopdracht te starten. |
| count | int | Aantal tekens om door te zoeken. |
| comparisonType | [StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modus. |

### Retourwaarde

[Index](../../index/) van de laatst gevonden substring of -1 indien niet gevonden. Voor een lege zoekstring retourneert altijd startIndex+count.

## String::LastIndexOf(char_t) const method

Achterwaartse teken-zoekopdracht.

```cpp
int System::String::LastIndexOf(char_t value) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | char_t | Teken om te zoeken. |

### Retourwaarde

[Index](../../index/) van de laatst gevonden tekenpositie of -1 indien niet gevonden.

## String::LastIndexOf(char_t, int32_t) const method

Achterwaartse teken-zoekopdracht.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | char_t | Teken om te zoeken. |
| startIndex | **int32_t** | [Index](../../index/) om de zoekopdracht te starten bij. |

### Retourwaarde

[Index](../../index/) van de laatst gevonden tekenpositie vanaf startIndex of -1 indien niet gevonden.

## String::LastIndexOf(char_t, int32_t, int32_t) const method

Achterwaartse teken-zoekopdracht.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex, int32_t count) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | char_t | Teken om te zoeken. |
| startIndex | **int32_t** | [Index](../../index/) om de zoekopdracht te starten bij. |
| count | **int32_t** | Aantal tekens om door te zoeken. |

### Retourwaarde

[Index](../../index/) van de laatst gevonden tekenpositie vanaf startIndex of -1 indien niet gevonden.

## Zie ook

* Enum [StringComparison](../../stringcomparison/)
* Klasse [String](../)
* Namespace [System](../../)
* Bibliotheek [Aspose.Slides](../../../)