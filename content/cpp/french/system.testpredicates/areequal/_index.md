---
title: AreEqual()
second_title: Référence API Aspose.Slides pour C++
description: Compare les arguments pour l'assertion AreEqual.
type: docs
weight: 14
url: /fr/system.testpredicates/areequal/
---
## System::TestPredicates::AreEqual(const char *, const char *, T1&&, T2&&) fonction

Compare les arguments pour l'assertion AreEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
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
| lhs | T1&& | Valeur LHS. |
| rhs | T2&& | Valeur RHS. |

### Valeur de retour

Résultat d'assertion au style gtest.

## Voir aussi

* Espace de noms [System::TestPredicates](../)
* Bibliothèque [Aspose.Slides](../../)