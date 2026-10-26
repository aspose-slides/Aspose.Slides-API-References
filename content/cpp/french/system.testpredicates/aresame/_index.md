---
title: AreSame()
second_title: Aspose.Slides pour C++ Référence API
description: Are-same compare les arguments pour la traduction de l'assertion AreSame.
type: docs
weight: 66
url: /fr/system.testpredicates/aresame/
---
## System::TestPredicates::AreSame(const char *, const char *, const T1\&, const T2\&) fonction


Are-same compare les arguments pour l'assertion AreSame.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreSame(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```


### Paramètres de modèle

| Parameter | Description |
| --- | --- |
| T1 | type d'objet LHS. |
| T2 | type d'objet RHS. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | expression LHS. |
| rhs_expr | const char * | expression RHS. |
| lhs | const T1\& | valeur LHS. |
| rhs | const T2\& | valeur RHS. |

### Valeur de retour

résultat d'assertion au style gtest.

## Voir aussi

* Espace de noms [System::TestPredicates](../)
* Bibliothèque [Aspose.Slides](../../)