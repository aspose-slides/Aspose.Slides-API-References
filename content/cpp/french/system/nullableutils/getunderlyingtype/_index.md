---
title: GetUnderlyingType()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie le type d'argument sous-jacent du type nullable spécifié.
type: docs
weight: 1
url: /fr/system/nullableutils/getunderlyingtype/
---
## NullableUtils::GetUnderlyingType(const System::TypeInfo\&) méthode

Renvoie le type de l'argument sous-jacent du type nullable spécifié.

```cpp
static const System::TypeInfo & System::NullableUtils::GetUnderlyingType(const System::TypeInfo &nullableType)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| nullableType | const [System::TypeInfo](../../typeinfo/)\& | Un objet System.Type qui décrit un type nullable générique fermé. |

### Valeur de retour

L'argument de type du paramètre nullableType, si le paramètre nullableType est un type nullable générique fermé ; sinon, null

## Voir aussi

* Classe [TypeInfo](../../typeinfo/)
* Classe [NullableUtils](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)