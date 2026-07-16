---
title: AreNotSameImpl()
second_title: Référence de l'API Aspose.Slides pour C++
description: Are-not-same compare les pointeurs intelligents.
type: docs
weight: 105
url: /fr/system.testpredicates/arenotsameimpl/
---
## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1&, const T2&, long long) fonction

Are-not-same compare les pointeurs intelligents.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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
| s | long long | paramètre de service qui sert de sélecteur de l'implémentation de la fonction ; la valeur du paramètre est ignorée |

### Valeur de retour

résultat d'assertion au style gtest.

## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1&, const T2&, int) fonction

Are-not-same compare les valeurs non pointeurs.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
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

résultat d'assertion au style gtest.

## Voir aussi

* Struct [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)