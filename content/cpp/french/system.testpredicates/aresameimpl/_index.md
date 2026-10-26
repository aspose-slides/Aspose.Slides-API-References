---
title: AreSameImpl()
second_title: Référence API Aspose.Slides pour C++
description: Are-same compare les pointeurs intelligents.
type: docs
weight: 79
url: /fr/system.testpredicates/aresameimpl/
---
## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) function

Are-same compare les pointeurs intelligents.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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
| s | long long | Un paramètre de service qui sert de sélecteur de l'implémentation de la fonction ; la valeur du paramètre est ignorée |

### Valeur de retour

résultat d'assertion au format gtest.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) function

Are-same compare les exceptions.

```cpp
template<typename T1,typename T2> std::enable_if<IsExceptionWrapper<T1>::value &&IsExceptionWrapper<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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
| s | long long | Un paramètre de service qui sert de sélecteur de l'implémentation de la fonction ; la valeur du paramètre est ignorée |

### Valeur de retour

résultat d'assertion au format gtest.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, int) function

Are-same compare les valeurs non pointeurs.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
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

résultat d'assertion au format gtest.

## Voir aussi

* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsExceptionWrapper](../../system/isexceptionwrapper/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)