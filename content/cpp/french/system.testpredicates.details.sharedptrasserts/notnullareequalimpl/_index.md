---
title: NotNullAreEqualImpl()
second_title: Référence de l'API Aspose.Slides pour C++
description: Compare l'égalité des tableaux ou listes.
type: docs
weight: 40
url: /fr/system.testpredicates.details.sharedptrasserts/notnullareequalimpl/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) fonction

Compare l'égalité des tableaux ou listes.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Paramètres de modèle

| Parameter | Description |
| --- | --- |
| T1 | type de conteneur LHS. |
| T2 | type de conteneur RHS. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Expression LHS. |
| rhs_expr | const char * | Expression RHS. |
| lhs | const T1\& | Valeur LHS. |
| rhs | const T2\& | Valeur RHS. |
| s | long long | Un paramètre de service qui sert de sélecteur de l'implémentation de la fonction ; la valeur du paramètre est ignorée |

### Valeur de retour

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) fonction

Compare l'égalité des instances IEnumerable.

```cpp
template<typename T1,typename T2> std::enable_if<!TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value &&TypeTraits::BothEnumerable<typenameT1::Pointee_, typenameT2::Pointee_>::value &&(!TypeTraits::has_data_method<typenameT1::Pointee_>::value||!TypeTraits::has_data_method<typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Paramètres de modèle

| Parameter | Description |
| --- | --- |
| T1 | type d'élément LHS. |
| T2 | type d'élément RHS. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Expression LHS. |
| rhs_expr | const char * | Expression RHS. |
| lhs | const T1\& | Valeur LHS. |
| rhs | const T2\& | Valeur RHS. |
| s | long long | Un paramètre de service qui sert de sélecteur de l'implémentation de la fonction ; la valeur du paramètre est ignorée |

### Valeur de retour

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, int32_t) fonction

Compare l'égalité des types inconnus en utilisant la méthode Equals.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int32_t)
```


### Paramètres de modèle

| Parameter | Description |
| --- | --- |
| T1 | type d'objet LHS. |
| T2 | type d'objet RHS. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Expression LHS. |
| rhs_expr | const char * | Expression RHS. |
| lhs | const T1\& | Valeur LHS. |
| rhs | const T2\& | Valeur RHS. |

### Valeur de retour

gtest-styled assertion result.

## Voir aussi

* Typedef [BothArrayOrList](../../system.testpredicates.typetraits/botharrayorlist/)
* Typedef [BothEnumerable](../../system.testpredicates.typetraits/bothenumerable/)
* Struct [has_data_method](../../system.testpredicates.typetraits/has_data_method/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)