---
title: operator!=()
second_title: Référence de l'API Aspose.Slides pour C++
description: Opérateur de comparaison d'inégalité.
type: docs
weight: 313
url: /fr/system/string/operator_not_equal/
---
## String::operator!=(const String\&) const méthode

Opérateur de comparaison d’inégalité.

```cpp
bool System::String::operator!=(const String &str) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) à comparer avec celle en cours. |

### Valeur de retour

false si les deux chaînes sont nulles ou si les deux ne sont pas nulles et correspondent, true sinon.

## String::operator!=(std::nullptr_t) const méthode

Vérifie si la chaîne n'est pas nulle. Applique la même logique que l'appel [IsNull()](../isnull/).

```cpp
bool System::String::operator!=(std::nullptr_t) const
```

### Valeur de retour

false si la chaîne est nulle, true sinon.

## Voir aussi

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)