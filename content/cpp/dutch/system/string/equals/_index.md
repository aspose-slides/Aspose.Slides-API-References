---
title: Equals()
second_title: Aspose.Slides voor C++ API-referentie
description: String gelijkheidsvergelijking. Meerdere modi die door de StringComparison-enumeratie worden ondersteund.
type: docs
weight: 391
url: /nl/system/string/equals/
---
## String::Equals(const String\&, System::StringComparison) const method

[String](../) gelijkheidsvergelijking. Meerdere modi die door de StringComparison-enumeratie worden ondersteund.

```cpp
bool System::String::Equals(const String &str, System::StringComparison comparison_type) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) om te vergelijken met de huidige. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modus (zie [System::StringComparison](../../stringcomparison/) voor details). |

### Retourwaarde

true als de strings overeenkomen met de geselecteerde vergelijkingsmodus, false anders.

## String::Equals(const String\&) const method

[String](../) gelijkheidsvergelijking. Gebruikt de [System::StringComparison::Ordinal](../../stringcomparison/) vergelijkingsmodus.

```cpp
bool System::String::Equals(const String &str) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) om te vergelijken met de huidige. |

### Retourwaarde

true als de strings overeenkomen, false anders.

## String::Equals(const String\&, const String\&) method

Vergelijkt twee strings met de Ordial-vergelijkingsmodus.

```cpp
static bool System::String::Equals(const String &strA, const String &strB)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| strA | const [String](../)\& | Eerste string om te vergelijken. |
| strB | const [String](../)\& | Tweede string om te vergelijken. |

### Retourwaarde

true als de strings overeenkomen, false anders.

## String::Equals(const String\&, const String\&, System::StringComparison) method

```cpp
static bool System::String::Equals(const String &strA, const String &strB, System::StringComparison comparison_type)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| strA | const [String](../)\& | Eerste string om te vergelijken. |
| strB | const [String](../)\& | Tweede string om te vergelijken. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modus. |

### Retourwaarde

true als de strings overeenkomen, false anders.

## Zie ook

* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)