---
title: AreNotEqual()
second_title: Référence de l'API Aspose.Slides pour C++
description: La comparaison d'inégalité compare les arguments pour la traduction de l'assertion AreEqual.
type: docs
weight: 40
url: /fr/system.testpredicates/arenotequal/
---
## System::TestPredicates::AreNotEqual(const char *, const char *, T1\&&, T2\&&) fonction

La comparaison d'inégalité compare les arguments pour la traduction de l'assertion AreEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
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
| lhs | T1\&& | valeur LHS. |
| rhs | T2\&& | valeur RHS. |

### Valeur de retour

résultat d'assertion de style gtest.

## Voir aussi

* Espace de noms [System::TestPredicates](../)
* Bibliothèque [Aspose.Slides](../../)