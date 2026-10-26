---
title: Equals()
second_title: Référence API Aspose.Slides pour C++
description: Comparaison d'égalité de chaînes. Plusieurs modes fournis par l'énumération StringComparison sont pris en charge.
type: docs
weight: 391
url: /fr/system/string/equals/
---
## String::Equals(const String\&, System::StringComparison) const méthode

[String](../) comparaison d'égalité. Plusieurs modes fournis par l'énumération StringComparison sont pris en charge.

```cpp
bool System::String::Equals(const String &str, System::StringComparison comparison_type) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) à comparer avec celui actuel. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode (voir [System::StringComparison](../../stringcomparison/) pour plus de détails). |

### Valeur de retour

true si les chaînes correspondent en utilisant le type de comparaison sélectionné, false sinon.

## String::Equals(const String\&) const méthode

[String](../) comparaison d'égalité. Utilise le mode de comparaison [System::StringComparison::Ordinal](../../stringcomparison/).

```cpp
bool System::String::Equals(const String &str) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) à comparer avec celui actuel. |

### Valeur de retour

true si les chaînes correspondent, false sinon.

## String::Equals(const String\&, const String\&) méthode

Compare deux chaînes en utilisant le mode de comparaison Ordial.

```cpp
static bool System::String::Equals(const String &strA, const String &strB)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | Première chaîne à comparer. |
| strB | const [String](../)\& | Deuxième chaîne à comparer. |

### Valeur de retour

true si les chaînes correspondent, false sinon.

## String::Equals(const String\&, const String\&, System::StringComparison) méthode

Compare deux chaînes.

```cpp
static bool System::String::Equals(const String &strA, const String &strB, System::StringComparison comparison_type)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | Première chaîne à comparer. |
| strB | const [String](../)\& | Deuxième chaîne à comparer. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode. |

### Valeur de retour

true si les chaînes correspondent, false sinon.

## Voir aussi

* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)