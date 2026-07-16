---
title: Compare()
second_title: Référence de l'API Aspose.Slides pour C++
description: Compare deux sous-chaînes en renvoyant une valeur indiquant si la première est inférieure, égale ou supérieure à la seconde.
type: docs
weight: 820
url: /fr/system/string/compare/
---
## String::Compare(const String\&, int, const String\&, int, int, bool) méthode


Compare deux sous-chaînes en renvoyant une valeur indiquant si la première est inférieure, égale ou supérieure à la seconde.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase=false)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | Première chaîne à comparer. |
| indexA | int | Début de la sous-chaîne de la première chaîne. |
| strB | const [String](../)\& | Deuxième chaîne à comparer. |
| indexB | int | Début de la sous-chaîne de la deuxième chaîne. |
| length | int | Nombre de caractères à comparer. |
| ignoreCase | **bool** | Indique si la comparaison est insensible à la casse. |

### Valeur de retour

Valeur négative si la première sous-chaîne est inférieure à la seconde, zéro si elles sont identiques, valeur positive sinon.

## String::Compare(const String\&, int, const String\&, int, int, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) méthode


Compare deux sous-chaînes en renvoyant une valeur indiquant si la première est inférieure, égale ou supérieure à la seconde.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | Première chaîne à comparer. |
| indexA | int | Début de la sous-chaîne de la première chaîne. |
| strB | const [String](../)\& | Deuxième chaîne à comparer. |
| indexB | int | Début de la sous-chaîne de la deuxième chaîne. |
| length | int | Nombre de caractères à comparer. |
| ignoreCase | **bool** | Indique si la comparaison est insensible à la casse. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Culture à utiliser pour la comparaison. |

### Valeur de retour

Valeur négative si la première sous-chaîne est inférieure à la seconde, zéro si elles sont identiques, valeur positive sinon.

## String::Compare(const String\&, const String\&, System::StringComparison) méthode


Compare deux chaînes en renvoyant une valeur indiquant si la première est inférieure, égale ou supérieure à la seconde.

```cpp
static int System::String::Compare(const String &strA, const String &strB, System::StringComparison comparison_type)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | Première chaîne à comparer. |
| strB | const [String](../)\& | Deuxième chaîne à comparer. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode. |

### Valeur de retour

Valeur négative si la première sous-chaîne est inférieure à la seconde, zéro si elles sont identiques, valeur positive sinon.

## String::Compare(const String\&, int, const String\&, int, int, System::StringComparison) méthode


Compare deux chaînes en renvoyant une valeur indiquant si la première est inférieure, égale ou supérieure à la seconde.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, System::StringComparison comparison_type)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | Première chaîne à comparer. |
| indexA | int | Début de la sous-chaîne de la première chaîne. |
| strB | const [String](../)\& | Deuxième chaîne à comparer. |
| indexB | int | Début de la sous-chaîne de la deuxième chaîne. |
| length | int | Nombre de caractères à comparer. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode. |

### Valeur de retour

Valeur négative si la première sous-chaîne est inférieure à la seconde, zéro si elles sont identiques, valeur positive sinon.

## String::Compare(const String\&, const String\&, bool) méthode


Compare deux chaînes en renvoyant une valeur indiquant si la première est inférieure, égale ou supérieure à la seconde.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase=false)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | Première chaîne à comparer. |
| strB | const [String](../)\& | Deuxième chaîne à comparer. |
| ignoreCase | **bool** | Indique si la comparaison est insensible à la casse. |

### Valeur de retour

Valeur négative si la première sous-chaîne est inférieure à la seconde, zéro si elles sont identiques, valeur positive sinon.

## String::Compare(const String\&, const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) méthode


Compare deux chaînes en renvoyant une valeur indiquant si la première est inférieure, égale ou supérieure à la seconde.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | Première chaîne à comparer. |
| strB | const [String](../)\& | Deuxième chaîne à comparer. |
| ignoreCase | **bool** | Indique si la comparaison est insensible à la casse. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Culture à utiliser pour la comparaison. |

### Valeur de retour

Valeur négative si la première sous-chaîne est inférieure à la seconde, zéro si elles sont identiques, valeur positive sinon.

## Voir aussi

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Espace de noms [System](../../)
* Library [Aspose.Slides](../../../)