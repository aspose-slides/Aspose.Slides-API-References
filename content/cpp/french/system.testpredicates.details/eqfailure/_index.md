---
title: EqFailure()
second_title: Référence de l'API Aspose.Slides pour C++
description: Formate l'échec d'assertion == pour la sortie.
type: docs
weight: 27
url: /fr/system.testpredicates.details/eqfailure/
---
## System::TestPredicates::Details::EqFailure(const char *, const char *, T1\&, T2\&) fonction


Formate l'échec d'assertion == pour la sortie.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::EqFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | Type de valeur LHS. |
| T2 | Type de valeur RHS. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Expression LHS. |
| rhs_expr | const char * | Expression RHS. |
| lhs | T1\& | Valeur LHS. |
| rhs | T2\& | Valeur RHS. |

### Valeur de retour

[Object](../../system/object/) texte d'échec enveloppé.

## Voir aussi

* Espace de noms [System::TestPredicates::Details](../)
* Bibliothèque [Aspose.Slides](../../)