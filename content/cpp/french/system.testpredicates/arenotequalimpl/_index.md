---
title: AreNotEqualImpl()
second_title: Référence de l'API Aspose.Slides pour C++
description: Les comparaisons d'inégalité comparent des valeurs dont l'une ou les deux sont Decimal.
type: docs
weight: 53
url: /fr/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) fonction


Les comparaisons d'inégalité comparent des valeurs dont l'une ou les deux sont [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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
| lhs | const T1\& | Valeur LHS. |
| rhs | const T2\& | Valeur RHS. |
| s | long long | Un paramètre de service qui sert de sélecteur de l'implémentation de la fonction ; la valeur du paramètre est ignorée |

### Valeur de retour

Résultat d'assertion au style gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) fonction


Les comparaisons d'inégalité comparent des types non pointeurs en utilisant la méthode Equals fournie.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Expression LHS. |
| rhs_expr | const char * | Expression RHS. |
| lhs | const T\& | Valeur LHS. |
| rhs | const T\& | Valeur RHS. |
| s | long long | Un paramètre de service qui sert de sélecteur de l'implémentation de la fonction ; la valeur du paramètre est ignorée |

### Valeur de retour

Résultat d'assertion au style gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T&, const T&, long long) fonction


Les comparaisons d'inégalité comparent des types non pointeurs en utilisant la méthode Equals fournie.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Expression LHS. |
| rhs_expr | const char * | Expression RHS. |
| lhs | T\& | Valeur LHS. |
| rhs | const T\& | Valeur RHS. |
| s | long long | Un paramètre de service qui sert de sélecteur de l'implémentation de la fonction ; la valeur du paramètre est ignorée |

### Valeur de retour

Résultat d'assertion au style gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) fonction


Les comparaisons d'inégalité comparent des types non pointeurs en utilisant l'opérateur != fourni.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Expression LHS. |
| rhs_expr | const char * | Expression RHS. |
| lhs | const T\& | Valeur LHS. |
| rhs | const T\& | Valeur RHS. |
| s | long long | Un paramètre de service qui sert de sélecteur de l'implémentation de la fonction ; la valeur du paramètre est ignorée |

### Valeur de retour

Résultat d'assertion au style gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) fonction


Les comparaisons d'inégalité comparent des valeurs boxtables avec [SmartPtr](../../system/smartptr/) en utilisant le déballage.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Expression LHS. |
| rhs_expr | const char * | Expression RHS. |
| lhs | T | Valeur LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Valeur RHS. |
| s | long long | Un paramètre de service qui sert de sélecteur de l'implémentation de la fonction ; la valeur du paramètre est ignorée |

### Valeur de retour

Résultat d'assertion au style gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) fonction


Les comparaisons d'inégalité comparent des valeurs boxtables avec [SmartPtr](../../system/smartptr/) en utilisant le déballage.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Expression LHS. |
| rhs_expr | const char * | Expression RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Valeur LHS. |
| rhs | T | Valeur RHS. |
| s | long long | Un paramètre de service qui sert de sélecteur de l'implémentation de la fonction ; la valeur du paramètre est ignorée |

### Valeur de retour

Résultat d'assertion au style gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) fonction


Les comparaisons d'inégalité comparent un type aléatoire avec nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Expression LHS. |
| rhs_expr | const char * | Expression RHS. |
| lhs | T | Valeur LHS. |
| s | std::nullptr_t | Un paramètre de service qui sert de sélecteur de l'implémentation de la fonction ; la valeur du paramètre est ignorée |

### Valeur de retour

Résultat d'assertion au style gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) fonction


Les comparaisons d'inégalité comparent un type aléatoire avec nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Expression LHS. |
| rhs_expr | const char * | Expression RHS. |
| rhs | std::nullptr_t | Valeur RHS. |
| s | T | Un paramètre de service qui sert de sélecteur de l'implémentation de la fonction ; la valeur du paramètre est ignorée |

### Valeur de retour

Résultat d'assertion au style gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) fonction


Les comparaisons d'égalité comparent des types pointeurs.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | Type LHS. |
| T2 | Type RHS. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Expression LHS. |
| rhs_expr | const char * | Expression RHS. |
| lhs | const T1\& | Valeur LHS. |
| rhs | const T2\& | Valeur RHS. |
| s | long long | Un paramètre de service qui sert de sélecteur de l'implémentation de la fonction ; la valeur du paramètre est ignorée |

### Valeur de retour

Résultat d'assertion au style gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) fonction


Les comparaisons d'égalité comparent des types aléatoires en utilisant les algorithmes gtest.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | Type LHS. |
| T2 | Type RHS. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Expression LHS. |
| rhs_expr | const char * | Expression RHS. |
| lhs | T1 | Valeur LHS. |
| rhs | T2 | Valeur RHS. |

### Valeur de retour

Résultat d'assertion au style gtest.

## Voir aussi

* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Classe [Object](../../system/object/)
* Structure [IsSmartPtr](../../system/issmartptr/)
* Structure [IsBoxable](../../system/isboxable/)
* Espace de noms [System::TestPredicates](../)
* Bibliothèque [Aspose.Slides](../../)