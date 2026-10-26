---
title: AreNotEqualImpl()
second_title: Référence de l'API Aspose.Slides pour C++
description: Compare des valeurs non égales lorsque l’une ou les deux sont Decimal.
type: docs
weight: 53
url: /fr/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

Compare des valeurs non égales lorsque l’une ou les deux sont [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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
| s | long long | Un paramètre de service qui sert de sélecteur à l'implémentation de la fonction ; la valeur du paramètre est ignorée |

### Valeur de retour

résultat d'assertion au style gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) function

Compare des valeurs non égales deux [System::String](../../system/string/) valeurs, en protégeant contre l’appel d’une fonction membre sur un [String](../../system/string/) nul. Modélisé pour les mêmes raisons d’exclusion basées sur la déduction que la surcharge AreEqualImpl [String](../../system/string/) ci-dessus.

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | type [Object](../../system/object/), limité à [System::String](../../system/string/). |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | expression LHS. |
| rhs_expr | const char * | expression RHS. |
| lhs | const T\& | valeur LHS. |
| rhs | const T\& | valeur RHS. |
| s | long long | Un paramètre de service qui sert de sélecteur à l'implémentation de la fonction ; la valeur du paramètre est ignorée |

### Valeur de retour

résultat d'assertion au style gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) function

Compare des types non pointeurs en utilisant la méthode Equals fournie.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | type [Object](../../system/object/). |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | expression LHS. |
| rhs_expr | const char * | expression RHS. |
| lhs | const T\& | valeur LHS. |
| rhs | const T\& | valeur RHS. |
| s | long long | Un paramètre de service qui sert de sélecteur à l'implémentation de la fonction ; la valeur du paramètre est ignorée |

### Valeur de retour

résultat d'assertion au style gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) function

Compare des types non pointeurs en utilisant la méthode Equals fournie.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | type [Object](../../system/object/). |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | expression LHS. |
| rhs_expr | const char * | expression RHS. |
| lhs | T\& | valeur LHS. |
| rhs | const T\& | valeur RHS. |
| s | long long | Un paramètre de service qui sert de sélecteur à l'implémentation de la fonction ; la valeur du paramètre est ignorée |

### Valeur de retour

résultat d'assertion au style gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) function

Compare des types non pointeurs en utilisant l’opérateur != fourni.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | type [Object](../../system/object/). |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | expression LHS. |
| rhs_expr | const char * | expression RHS. |
| lhs | const T\& | valeur LHS. |
| rhs | const T\& | valeur RHS. |
| s | long long | Un paramètre de service qui sert de sélecteur à l'implémentation de la fonction ; la valeur du paramètre est ignorée |

### Valeur de retour

résultat d'assertion au style gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) function

Compare des valeurs boxables avec [SmartPtr](../../system/smartptr/) en utilisant le déboxing.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | type [Object](../../system/object/). |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | expression LHS. |
| rhs_expr | const char * | expression RHS. |
| lhs | T | valeur LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | valeur RHS. |
| s | long long | Un paramètre de service qui sert de sélecteur à l'implémentation de la fonction ; la valeur du paramètre est ignorée |

### Valeur de retour

résultat d'assertion au style gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) function

Compare des valeurs boxables avec [SmartPtr](../../system/smartptr/) en utilisant le déboxing.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | type [Object](../../system/object/). |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | expression LHS. |
| rhs_expr | const char * | expression RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | valeur LHS. |
| rhs | T | valeur RHS. |
| s | long long | Un paramètre de service qui sert de sélecteur à l'implémentation de la fonction ; la valeur du paramètre est ignorée |

### Valeur de retour

résultat d'assertion au style gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) function

Compare un type aléatoire avec nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | type [Object](../../system/object/). |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | expression LHS. |
| rhs_expr | const char * | expression RHS. |
| lhs | T | valeur LHS. |
| s | std::nullptr_t | Un paramètre de service qui sert de sélecteur à l'implémentation de la fonction ; la valeur du paramètre est ignorée |

### Valeur de retour

résultat d'assertion au style gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) function

Compare un type aléatoire avec nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | type [Object](../../system/object/). |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | expression LHS. |
| rhs_expr | const char * | expression RHS. |
| rhs | std::nullptr_t | valeur RHS. |
| s | T | Un paramètre de service qui sert de sélecteur à l'implémentation de la fonction ; la valeur du paramètre est ignorée |

### Valeur de retour

résultat d'assertion au style gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

Compare des types pointeurs.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | type LHS. |
| T2 | type RHS. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | expression LHS. |
| rhs_expr | const char * | expression RHS. |
| lhs | const T1\& | valeur LHS. |
| rhs | const T2\& | valeur RHS. |
| s | long long | Un paramètre de service qui sert de sélecteur à l'implémentation de la fonction ; la valeur du paramètre est ignorée |

### Valeur de retour

résultat d'assertion au style gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) function

Compare des types aléatoires en utilisant les algorithmes gtest.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | type LHS. |
| T2 | type RHS. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | expression LHS. |
| rhs_expr | const char * | expression RHS. |
| lhs | T1 | valeur LHS. |
| rhs | T2 | valeur RHS. |

### Valeur de retour

résultat d'assertion au style gtest.

## Voir aussi

* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [String](../../system/string/)
* Class [Object](../../system/object/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)