---
title: EndsWith()
second_title: Référence de l'API Aspose.Slides pour C++
description: Vérifie si la chaîne se termine par la sous-chaine spécifiée.
type: docs
weight: 482
url: /fr/system/string/endswith/
---
## String::EndsWith(const String\&) const méthode

Vérifie si la chaîne se termine par la sous-chaine spécifiée.

```cpp
bool System::String::EndsWith(const String &value) const
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | Chaîne de recherche. |

### Valeur de retour

true if string ends with specified substring, false otherwise.

## String::EndsWith(const String\&, System::StringComparison) const méthode

Vérifie si la chaîne se termine par la sous-chaine spécifiée.

```cpp
bool System::String::EndsWith(const String &value, System::StringComparison comparisonType) const
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | Chaîne de recherche. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | mode [Comparison](../../comparison/), voir [System::StringComparison](../../stringcomparison/) pour plus de détails. |

### Valeur de retour

true if string ends with specified substring, false otherwise.

## String::EndsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const méthode

Vérifie si la chaîne se termine par la sous-chaine spécifiée.

```cpp
bool System::String::EndsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | Chaîne de recherche. |
| ignoreCase | **bool** | Spécifie si la comparaison est insensible à la casse. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Culture à utiliser lors de la comparaison de chaînes. |

### Valeur de retour

true if string ends with specified substring, false otherwise.

## Voir aussi

* Énumération [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)