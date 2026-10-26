---
title: AreNotSame()
second_title: Référence API Aspose.Slides pour C++
description: Are-not-same compare les arguments pour la traduction de l'assertion AreSame.
type: docs
weight: 92
url: /fr/system.testpredicates/arenotsame/
---
## System::TestPredicates::AreNotSame(const char *, const char *, const T1\&, const T2\&) fonction

Are-not-same compare les arguments pour la traduction de l'assertion AreSame.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSame(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | type d'objet LHS. |
| T2 | type d'objet RHS. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | expression LHS. |
| rhs_expr | const char * | expression RHS. |
| lhs | const T1\& | valeur LHS. |
| rhs | const T2\& | valeur RHS. |

### Valeur de retour

résultat d'assertion de style gtest.

## Voir aussi

* Espace de noms [System::TestPredicates](../)
* Bibliothèque [Aspose.Slides](../../)