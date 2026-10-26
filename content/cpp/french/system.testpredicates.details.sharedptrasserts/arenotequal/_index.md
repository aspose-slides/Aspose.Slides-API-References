---
title: AreNotEqual()
second_title: Référence API Aspose.Slides pour C++
description: Compare les arguments de non-égalité pour la traduction de l'assertion AreNotEqual.
type: docs
weight: 131
url: /fr/system.testpredicates.details.sharedptrasserts/arenotequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreNotEqual(const char *, const char *, const T1\&, const T2\&) fonction

Compare la non-égalité des arguments pour l'assertion AreNotEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::AreNotEqual(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | Type d'objet LHS. |
| T2 | Type d'objet RHS. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Expression LHS. |
| rhs_expr | const char * | Expression RHS. |
| lhs | const T1\& | Valeur LHS. |
| rhs | const T2\& | Valeur RHS. |

### Valeur de retour

Résultat d'assertion au style gtest.

## Voir aussi

* Espace de noms [System::TestPredicates::Details::SharedPtrAsserts](../)
* Bibliothèque [Aspose.Slides](../../)