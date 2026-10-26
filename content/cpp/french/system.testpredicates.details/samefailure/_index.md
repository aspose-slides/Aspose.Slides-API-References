---
title: SameFailure()
second_title: Référence de l'API Aspose.Slides for C++
description: Formate l'échec d'assertion 'same' pour la sortie.
type: docs
weight: 53
url: /fr/system.testpredicates.details/samefailure/
---
## System::TestPredicates::Details::SameFailure(const char *, const char *, T1\&, T2\&) fonction

Formate l'échec d'assertion 'same' pour la sortie.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| T1 | type de valeur LHS. |
| T2 | type de valeur RHS. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | expression LHS. |
| rhs_expr | const char * | expression RHS. |
| lhs | T1\& | valeur LHS. |
| rhs | T2\& | valeur RHS. |

### Valeur de retour

[Object](../../system/object/) texte d'échec enveloppant.

## Voir aussi

* Espace de noms [System::TestPredicates::Details](../)
* Bibliothèque [Aspose.Slides](../../)