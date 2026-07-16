---
title: NotNullAreEqual()
second_title: Référence de l'API Aspose.Slides pour C++
description: Compare l'égalité des dictionnaires de types valeur.
type: docs
weight: 53
url: /fr/system.testpredicates.details.sharedptrasserts/notnullareequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\>\&) function

Compare l'égalité des dictionnaires de types valeur.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &rhs)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| K | type de clé. |
| V | type de valeur. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Expression LHS. |
| rhs_expr | const char * | Expression RHS. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | Valeur LHS. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | Valeur RHS. |

### Valeur de retour

Résultat d'assertion de style gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\>\&) function

Compare l'égalité des dictionnaires de pointeurs partagés.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &rhs)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| K | type de clé. |
| V | type de valeur. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Expression LHS. |
| rhs_expr | const char * | Expression RHS. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | Valeur LHS. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | Valeur RHS. |

### Valeur de retour

Résultat d'assertion de style gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::HashSet\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::HashSet\<T2\>\>\&) function

Compare l'égalité des ensembles de hachage.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::HashSet<T1>> &lhs, const SharedPtr<System::Collections::Generic::HashSet<T2>> &rhs)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | type d'élément du conteneur LHS. |
| T2 | type d'élément du conteneur RHS. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Expression LHS. |
| rhs_expr | const char * | Expression RHS. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T1\>\>\& | Valeur LHS. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T2\>\>\& | Valeur RHS. |

### Valeur de retour

Résultat d'assertion de style gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Queue\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Queue\<T2\>\>\&) function

Compare l'égalité des files d'attente.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Queue<T1>> &lhs, const SharedPtr<System::Collections::Generic::Queue<T2>> &rhs)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | type d'élément du conteneur LHS. |
| T2 | type d'élément du conteneur RHS. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Expression LHS. |
| rhs_expr | const char * | Expression RHS. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T1\>\>\& | Valeur LHS. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T2\>\>\& | Valeur RHS. |

### Valeur de retour

Résultat d'assertion de style gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Stack\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Stack\<T2\>\>\&) function

Compare l'égalité des piles.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Stack<T1>> &lhs, const SharedPtr<System::Collections::Generic::Stack<T2>> &rhs)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | type d'élément du conteneur LHS. |
| T2 | type d'élément du conteneur RHS. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Expression LHS. |
| rhs_expr | const char * | Expression RHS. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T1\>\>\& | Valeur LHS. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T2\>\>\& | Valeur RHS. |

### Valeur de retour

Résultat d'assertion de style gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>\&) function

Compare l'égalité des dictionnaires triés de types valeur.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &rhs)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| K | type de clé. |
| V | type de valeur. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Expression LHS. |
| rhs_expr | const char * | Expression RHS. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | Valeur LHS. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | Valeur RHS. |

### Valeur de retour

Résultat d'assertion de style gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>\&) function

Compare l'égalité des dictionnaires triés de pointeurs partagés.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &rhs)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| K | type de clé. |
| V | type de valeur. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Expression LHS. |
| rhs_expr | const char * | Expression RHS. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | Valeur LHS. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | Valeur RHS. |

### Valeur de retour

Résultat d'assertion de style gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>\&) function

Compare l'égalité des listes triées de types valeur.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &rhs)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| K | type de clé. |
| V | type de valeur. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Expression LHS. |
| rhs_expr | const char * | Expression RHS. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | Valeur LHS. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | Valeur RHS. |

### Valeur de retour

Résultat d'assertion de style gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>\&) function

Compare l'égalité des listes triées de pointeurs partagés.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &rhs)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| K | type de clé. |
| V | type de valeur. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Expression LHS. |
| rhs_expr | const char * | Expression RHS. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | Valeur LHS. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | Valeur RHS. |

### Valeur de retour

Résultat d'assertion de style gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::BitArray\>\&, const SharedPtr\<System::Collections::BitArray\>\&) function

Compare l'égalité des tableaux de bits.

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::BitArray> &lhs, const SharedPtr<System::Collections::BitArray> &rhs)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Expression LHS. |
| rhs_expr | const char * | Expression RHS. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | Valeur LHS. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | Valeur RHS. |

### Valeur de retour

Résultat d'assertion de style gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&) function

Compare l'égalité des collections de chaînes.

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Specialized::StringCollection> &lhs, const SharedPtr<System::Collections::Specialized::StringCollection> &rhs)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Expression LHS. |
| rhs_expr | const char * | Expression RHS. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | Valeur LHS. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | Valeur RHS. |

### Valeur de retour

Résultat d'assertion de style gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&) function

Compare l'égalité des collections abstraites.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::ICollection<T>> &lhs, const SharedPtr<System::Collections::Generic::ICollection<T>> &rhs)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | type d'élément. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Expression LHS. |
| rhs_expr | const char * | Expression RHS. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | Valeur LHS. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | Valeur RHS. |

### Valeur de retour

Résultat d'assertion de style gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<Object\>\&, const SharedPtr\<Object\>\&) function

Compare l'égalité de deux types [Object](../../system/object/).

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<Object> &lhs, const SharedPtr<Object> &rhs)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Expression LHS. |
| rhs_expr | const char * | Expression RHS. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Valeur LHS. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Valeur RHS. |

### Valeur de retour

Résultat d'assertion de style gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<T1\>\&, const SharedPtr\<T2\>\&) function

Compare l'égalité de types inconnus.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<T1> &lhs, const SharedPtr<T2> &rhs)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | type d'objet LHS. |
| T2 | type d'objet RHS. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Expression LHS. |
| rhs_expr | const char * | Expression RHS. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<T1\>\& | Valeur LHS. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<T2\>\& | Valeur RHS. |

### Valeur de retour

Résultat d'assertion de style gtest.

## See Also

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Dictionary](../../system.collections.generic/dictionary/)
* Class [HashSet](../../system.collections.generic/hashset/)
* Class [Queue](../../system.collections.generic/queue/)
* Class [Stack](../../system.collections.generic/stack/)
* Class [SortedDictionary](../../system.collections.generic/sorteddictionary/)
* Class [SortedList](../../system.collections.generic/sortedlist/)
* Class [BitArray](../../system.collections/bitarray/)
* Class [StringCollection](../../system.collections.specialized/stringcollection/)
* Class [ICollection](../../system.collections.generic/icollection/)
* Class [Object](../../system/object/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)