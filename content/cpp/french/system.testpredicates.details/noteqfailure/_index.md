---
title: NotEqFailure()
second_title: Référence de l'API Aspose.Slides pour C++
description: Formate l'échec d'assertion != pour la sortie.
type: docs
weight: 40
url: /fr/system.testpredicates.details/noteqfailure/
---
## System::TestPredicates::Details::NotEqFailure(const char *, const char *, T1\&, T2\&) fonction

Formate l'échec d'assertion != pour la sortie.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::NotEqFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### Paramètres de modèle

| Parameter | Description |
| --- | --- |
| T1 | type de valeur LHS. |
| T2 | type de valeur RHS. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | expression LHS. |
| rhs_expr | const char * | expression RHS. |
| lhs | T1\& | valeur LHS. |
| rhs | T2\& | valeur RHS. |

### Valeur de retour

[Object](../../system/object/) texte d'échec d'enveloppe.

## Voir aussi

* Espace de noms [System::TestPredicates::Details](../)
* Bibliothèque [Aspose.Slides](../../)