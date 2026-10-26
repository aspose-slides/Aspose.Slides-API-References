---
title: IsInstanceOf()
second_title: Référence API Aspose.Slides pour C++
description: Is-instance-of compare les arguments pour la traduction de l'assertion IsInstanceOf.
type: docs
weight: 118
url: /fr/system.testpredicates/isinstanceof/
---
## System::TestPredicates::IsInstanceOf(const char *, const char *, const TypeInfo\&, const T\&) fonction


Is-instance-of compare les arguments pour la traduction de l'assertion IsInstanceOf.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::IsInstanceOf(const char *lhs_expr, const char *rhs_expr, const TypeInfo &typeInfo, const T &obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Argument type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| typeInfo | const [TypeInfo](../../system/typeinfo/)\& | Un objet typeInfo qui représente un type contre lequel le type de **obj** doit être comparé |
| obj | const T\& | Un objet dont le type doit être comparé au type spécifié |

### Valeur de retour

Résultat d'assertion au style gtest.

## Voir aussi

* Classe [TypeInfo](../../system/typeinfo/)
* Espace de noms [System::TestPredicates](../)
* Bibliothèque [Aspose.Slides](../../)