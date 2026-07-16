---
title: AreEqual()
second_title: Référence de l'API Aspose.Slides for C++
description: Compare les arguments pour la traduction de l'assertion AreEqual.
type: docs
weight: 92
url: /fr/system.testpredicates.details.sharedptrasserts/areequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqual(const char *, const char *, const T1\&, const T2\&) function

Compare les arguments pour la traduction de l'assertion AreEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::AreEqual(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
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

Résultat d'assertion au style gtest.

## Voir aussi

* Espace de noms [System::TestPredicates::Details::SharedPtrAsserts](../)
* Bibliothèque [Aspose.Slides](../../)