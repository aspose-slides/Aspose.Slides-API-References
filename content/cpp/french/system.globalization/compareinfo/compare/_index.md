---
title: Compare()
second_title: Référence de l'API Aspose.Slides pour C++
description: Compare des chaînes. Non implémenté.
type: docs
weight: 66
url: /fr/system.globalization/compareinfo/compare/
---
## CompareInfo::Compare(const String\&, const String\&) const method

Compare des chaînes. Non implémenté.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, const String &string2) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Chaîne LHS. |
| string2 | const [String](../../../system/string/)\& | Chaîne RHS. |

### Valeur de retour

Valeur négative si la chaîne LHS précède celle de RHS, zéro si elles correspondent, valeur positive sinon.

## CompareInfo::Compare(const String\&, const String\&, CompareOptions) const method

Compare des chaînes. Seuls les modes Ordinal et OrdinalIgnoreCase sont pris en charge.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &a, const String &b, CompareOptions options) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| a | const [String](../../../system/string/)\& | Chaîne LHS. |
| b | const [String](../../../system/string/)\& | Chaîne RHS. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) type de comparaison. |

### Valeur de retour

Valeur négative si la chaîne LHS précède celle de RHS, zéro si elles correspondent, valeur positive sinon.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int) const method

Compare une section d'une chaîne avec une section d'une deuxième chaîne. Non implémenté.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Première chaîne. |
| offset1 | int | Indice de départ des caractères dans **string1**. |
| length1 | int | Nombre de caractères dans **string1** à comparer. |
| string2 | const [String](../../../system/string/)\& | Deuxième chaîne. |
| offset2 | int | Indice de départ des caractères dans **string2**. |
| length2 | int | Nombre de caractères dans **string2** à comparer. |

### Valeur de retour

Valeur négative si la première section de chaîne précède la seconde, zéro si elles correspondent, valeur positive sinon.

## CompareInfo::Compare(const String\&, int, const String\&, int, CompareOptions) const method

Compare la section finale d'une chaîne avec la section finale d'une deuxième chaîne en utilisant des méthodes de comparaison de chaînes. Non implémenté.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2, CompareOptions options) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Première chaîne. |
| offset1 | int | Indice de départ des caractères dans **string1**. |
| string2 | const [String](../../../system/string/)\& | Deuxième chaîne. |
| offset2 | int | Indice de départ des caractères dans **string2**. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) options de comparaison. |

### Valeur de retour

Valeur négative si la première section de chaîne précède la seconde, zéro si elles correspondent, valeur positive sinon.

## CompareInfo::Compare(const String\&, int, const String\&, int) const method

Compare la section finale d'une chaîne avec la section finale d'une deuxième chaîne. Non implémenté.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Première chaîne. |
| offset1 | int | Indice de départ des caractères dans **string1**. |
| string2 | const [String](../../../system/string/)\& | Deuxième chaîne. |
| offset2 | int | Indice de départ des caractères dans **string2**. |

### Valeur de retour

Valeur négative si la première section de chaîne précède la seconde, zéro si elles correspondent, valeur positive sinon.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int, CompareOptions) const method

Compare une section d'une chaîne avec une section d'une deuxième chaîne en utilisant des méthodes de comparaison de chaînes. Non implémenté.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2, CompareOptions options) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Première chaîne. |
| offset1 | int | Indice de départ des caractères dans **string1**. |
| length1 | int | Nombre de caractères dans **string1** à comparer. |
| string2 | const [String](../../../system/string/)\& | Deuxième chaîne. |
| offset2 | int | Indice de départ des caractères dans **string2**. |
| length2 | int | Nombre de caractères dans **string2** à comparer. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) options de comparaison. |

### Valeur de retour

Valeur négative si la première section de chaîne précède la seconde, zéro si elles correspondent, valeur positive sinon.

## Voir aussi

* Enum [CompareOptions](../../compareoptions/)
* Class [String](../../../system/string/)
* Class [CompareInfo](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)