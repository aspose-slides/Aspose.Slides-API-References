---
title: FieldAttributes
second_title: Référence de l'API Aspose.Slides pour C++
description: Attributs de champ reflétés.
type: docs
weight: 170
url: /fr/system.reflection/fieldattributes/
---
## FieldAttributes enum

Attributs de champ reflétés.

```cpp
enum class FieldAttributes
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| FieldAccessMask | 7 | Masque d'accès aux membres. Utilisez ce masque pour récupérer les informations d'accessibilité. |
| PrivateScope | 0 | Membres non référencables. |
| Private | 1 | Membres privés. |
| FamANDAssem | 2 | Membres privés et limités à l'assembly. |
| Assembly | 3 | Membres limités à l'assembly. |
| Family | 4 | Membres accessibles par le type et ses sous-types. |
| FamORAssem | 5 | Membres accessibles par le type, les sous-types et l'assembly. |
| Public | 6 | Membres accessibles par tous. |
| Static | 16 | Membres statiques par opposition aux membres d'instance. |
| InitOnly | 32 | Membres const qui ne peuvent être initialisés qu'une fois et ne peuvent pas être modifiés. |
| Literal | 64 | Membres constants au moment de la compilation. |
| NotSerialized | 128 | Membres non sérialisés. |
| SpecialName | 512 | Champ spécial parmi les noms ci-dessous. |
| PinvokeImpl | 8192 | Implémentation interop transmise. |
| ReservedMask | 38144 | Drapeaux réservés pour l'utilisation en temps d'exécution uniquement. |
| RTSpecialName | 1024 | Le runtime doit vérifier l'encodage du nom. |
| HasFieldMarshal | 4096 | Informations de marshaling présentes. |
| HasDefault | 32768 | Valeur par défaut présente. |
| HasFieldRVA | 256 | RVA présent. |

## Voir aussi

* Espace de noms [System::Reflection](../)
* Bibliothèque [Aspose.Slides](../../)