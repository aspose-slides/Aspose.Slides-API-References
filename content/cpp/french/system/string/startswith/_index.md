---
title: StartsWith()
second_title: Référence API Aspose.Slides pour C++
description: Vérifie si la chaîne commence par la sous-chaîne spécifiée.
type: docs
weight: 469
url: /fr/system/string/startswith/
---
## String::StartsWith(const String\&) const méthode

Vérifie si la chaîne commence par la sous-chaîne spécifiée.

```cpp
bool System::String::StartsWith(const String &value) const
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | Chaîne de recherche. |

### Valeur de retour

true si la chaîne commence par la sous-chaîne spécifiée, false sinon.

## String::StartsWith(const String\&, System::StringComparison) const méthode

Vérifie si la chaîne commence par la sous-chaîne spécifiée.

```cpp
bool System::String::StartsWith(const String &value, System::StringComparison comparisonType) const
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | Chaîne de recherche. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode, voir [System::StringComparison](../../stringcomparison/) pour plus de détails. |

### Valeur de retour

true si la chaîne commence par la sous-chaîne spécifiée, false sinon.

## String::StartsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const méthode

Vérifie si la chaîne commence par la sous-chaîne spécifiée.

```cpp
bool System::String::StartsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | Chaîne de recherche. |
| ignoreCase | **bool** | Spécifie si la comparaison est insensible à la casse. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Culture à utiliser lors de la comparaison de chaînes. |

### Valeur de retour

true si la chaîne commence par la sous-chaîne spécifiée, false sinon.

## Voir aussi

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* classe [String](../)
* classe [CultureInfo](../../../system.globalization/cultureinfo/)
* espace de noms [System](../../)
* Library [Aspose.Slides](../../../)