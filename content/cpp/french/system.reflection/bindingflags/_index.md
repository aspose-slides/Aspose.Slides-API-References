---
title: BindingFlags
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit les membres et les modes de recherche et de liaison des types.
type: docs
weight: 157
url: /fr/system.reflection/bindingflags/
---
## BindingFlags enum

Définit les membres et les modes de recherche et de liaison des types.

```cpp
enum class BindingFlags
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Default | 0 | Aucune option spéciale. |
| IgnoreCase | 1 | Ignorer la casse du nom lors de la recherche d'un élément. |
| DeclaredOnly | 2 | Ne rechercher que les membres déclarés dans le type et pas dans les types de base. |
| Instance | 4 | Parcourir les membres d'instance. |
| Static | 8 | Parcourir les membres statiques. |
| Public | 16 | Parcourir les membres publics. |
| NonPublic | 32 | Parcourir les membres non publics. |
| FlattenHierarchy | 64 | Parcourir les membres statiques publics et protégés du type de base. |
| InvokeMethod | 256 | Invoque la méthode. |
| CreateInstance | 512 | Crée une instance du type reflété. |
| GetField | 1024 | Obtient la valeur du champ. |
| SetField | 2048 | Définit la valeur du champ. |
| GetProperty | 4096 | Obtient la valeur de la propriété. |
| SetProperty | 8192 | Définit la valeur de la propriété. |
| PutDispProperty | 16384 | Définit la propriété COM. |
| PutRefDispProperty | 32768 | Définit la propriété de référence COM. |
| ExactBinding | 65536 | La liaison du type doit être exacte, sans aucun changement de type. |
| SuppressChangeType | 131072 | Non pris en charge. |
| OptionalParamBinding | 262144 | Sélectionne la surcharge en fonction du nombre d'arguments. |
| IgnoreReturn | 16777216 | Ignore la valeur de retour de l'interop COM. |

## Voir aussi

* Espace de noms [System::Reflection](../)
* Bibliothèque [Aspose.Slides](../../)