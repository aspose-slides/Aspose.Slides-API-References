---
title: AreEqual()
second_title: Référence de l'API Aspose.Slides pour C++
description: Compare les tableaux de non-pointeurs.
type: docs
weight: 1
url: /fr/system/testcompare/areequal/
---
## TestCompare::AreEqual(const SharedPtr\<Array\<T\>\>\&, const SharedPtr\<Array\<U\>\>\&) method


Compare les tableaux de non-pointeurs.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<T>> &arrA, const SharedPtr<Array<U>> &arrB)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type du premier élément du tableau. |
| U | Type du deuxième élément du tableau. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Tableau LHS. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<U\>\>\& | Tableau RHS. |

### Valeur de retour

true si les tailles et les données des tableaux correspondent, false sinon.

## TestCompare::AreEqual(const SharedPtr\<Array\<SharedPtr\<T\>\>\>\&, const SharedPtr\<Array\<SharedPtr\<U\>\>\>\&) method


Compare les tableaux de pointeurs.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<SharedPtr<T>>> &arrA, const SharedPtr<Array<SharedPtr<U>>> &arrB)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type de l'objet pointé du premier tableau. |
| U | Type de l'objet pointé du deuxième tableau. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Tableau LHS. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Tableau RHS. |

### Valeur de retour

true si les tailles et les objets des tableaux correspondent, false sinon.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const SharedPtr\<SCG::List\<U\>\>\&) method


Compare les listes de non-pointeurs.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const SharedPtr<SCG::List<U>> &listB)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type du premier élément de la liste. |
| U | Type du deuxième élément de la liste. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | Liste LHS. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | Liste RHS. |

### Valeur de retour

true si les tailles et les données des listes correspondent, false sinon.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) method


Compare les listes de pointeurs.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &listA, const SharedPtr<SCG::List<SharedPtr<U>>> &listB)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type de l'objet pointé du premier élément de la liste. |
| U | Type de l'objet pointé du deuxième élément de la liste. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Liste LHS. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Liste RHS. |

### Valeur de retour

true si les tailles et les objets des listes correspondent, false sinon.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const System::ArrayPtr\<U\>\&) method


Compare les listes avec des tableaux dans le cas d'éléments non-pointeurs.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const System::ArrayPtr<U> &arrB)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type de l'élément de la liste. |
| U | Type de l'élément [Array](../../array/). |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | Liste. |
| arrB | const [System::ArrayPtr](../../arrayptr/)\<U\>\& | [Array](../../array/). |

### Valeur de retour

true si les tailles et les données correspondent, false sinon.

## TestCompare::AreEqual(const System::ArrayPtr\<T\>\&, const SharedPtr\<SCG::List\<U\>\>\&) method


Compare les listes avec des tableaux dans le cas d'éléments non-pointeurs.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<T> &arrA, const SharedPtr<SCG::List<U>> &listB)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type de l'élément [Array](../../array/). |
| U | Type de l'élément de la liste. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| arrA | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | [Array](../../array/). |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | Liste. |

### Valeur de retour

true si les tailles et les données correspondent, false sinon.

## TestCompare::AreEqual(const System::ArrayPtr\<SharedPtr\<T\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) method


Compare les listes avec des tableaux dans le cas d'éléments pointeurs.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<SharedPtr<T>> &arr, const SharedPtr<SCG::List<SharedPtr<U>>> &list)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type de l'objet pointé [Array](../../array/). |
| U | Type de l'objet pointé de la liste. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | [Array](../../array/). |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Liste. |

### Valeur de retour

true si les tailles et les objets correspondent, false sinon.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const System::ArrayPtr\<SharedPtr\<U\>\>\&) method


Compare les listes avec des tableaux dans le cas d'éléments pointeurs.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &list, const System::ArrayPtr<SharedPtr<U>> &arr)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type de l'objet pointé de la liste. |
| U | Type de l'objet pointé [Array](../../array/). |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Liste. |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | [Array](../../array/). |

### Valeur de retour

true si les tailles et les objets correspondent, false sinon.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, U\>\>\&, const SharedPtr\<SCG::Dictionary\<K, U\>\>\&) method


Compare les dictionnaires de types mappés non-pointeurs.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, U>> &dictA, const SharedPtr<SCG::Dictionary<K, U>> &dictB)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| K | Type de clé. |
| U | Type mappé. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | Dictionnaire LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | Dictionnaire RHS. |

### Valeur de retour

true si les tailles et les données des dictionnaires correspondent, false sinon.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&) method


Compare les dictionnaires de types mappés pointeurs.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictB)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| K | Type de clé. |
| U | Type de l'objet pointé mappé. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Dictionnaire LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Dictionnaire RHS. |

### Valeur de retour

true si les tailles et les données des dictionnaires correspondent, false sinon.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::Dictionary\<K2, U2\>\>\&) method


Compare les dictionnaires de types différents.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K1, U1>> &dictA, const SharedPtr<SCG::Dictionary<K2, U2>> &dictB)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| K1 | Type de clé du dictionnaire LHS. |
| U1 | Type mappé du dictionnaire LHS. |
| K2 | Type de clé du dictionnaire RHS. |
| U2 | Type mappé du dictionnaire RHS. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K1, U1\>\>\& | Dictionnaire LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K2, U2\>\>\& | Dictionnaire RHS. |

### Valeur de retour

Toujours renvoie false car la conversion de type est interdite ici.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<T\>\>\&, const SharedPtr\<SCG::HashSet\<U\>\>\&) method


Compare les hashsets de non-pointeurs.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<T>> &containerPtrA, const SharedPtr<SCG::HashSet<U>> &containerPtrB)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type du premier élément du hashset. |
| U | Type du deuxième élément du hashset. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| containerPtrA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<T\>\>\& | Hashset LHS. |
| containerPtrB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<U\>\>\& | Hashset RHS. |

### Valeur de retour

true si les tailles et les données des hashsets correspondent, false sinon.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::HashSet\<SharedPtr\<U\>\>\>\&) method


Compare les hashsets de pointeurs.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<SharedPtr<T>>> &contA, const SharedPtr<SCG::HashSet<SharedPtr<U>>> &contB)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type de l'objet pointé du premier élément du hashset. |
| U | Type de l'objet pointé du deuxième élément du hashset. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| contA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Hashset LHS. |
| contB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Hashset RHS. |

### Valeur de retour

true si les tailles et les données des hashsets correspondent, false sinon.

## TestCompare::AreEqual(const SCG::QueuePtr\<T\>\&, const SCG::QueuePtr\<U\>\&) method


Compare les files d'attente de non-pointeurs.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<T> &queueA, const SCG::QueuePtr<U> &queueB)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type du premier élément de la file. |
| U | Type du deuxième élément de la file. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<T\>\& | File LHS. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<U\>\& | File RHS. |

### Valeur de retour

true si les tailles et les données des files correspondent, false sinon.

## TestCompare::AreEqual(const SCG::QueuePtr\<SharedPtr\<T\>\>\&, const SCG::QueuePtr\<SharedPtr\<U\>\>\&) method


Compare les files d'attente de pointeurs.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<SharedPtr<T>> &queueA, const SCG::QueuePtr<SharedPtr<U>> &queueB)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type de l'objet pointé du premier élément de la file. |
| U | Type de l'objet pointé du deuxième élément de la file. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | File LHS. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | File RHS. |

### Valeur de retour

true si les tailles et les données des files correspondent, false sinon.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<T\>\>\&, const SharedPtr\<SCG::Stack\<U\>\>\&) method


Compare les piles de non-pointeurs.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<T>> &stackA, const SharedPtr<SCG::Stack<U>> &stackB)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type du premier élément de la pile. |
| U | Type du deuxième élément de la pile. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<T\>\>\& | Pile LHS. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<U\>\>\& | Pile RHS. |

### Valeur de retour

true si les tailles et les données des piles correspondent, false sinon.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::Stack\<SharedPtr\<U\>\>\>\&) method


Compare les piles de pointeurs.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<SharedPtr<T>>> &stackA, const SharedPtr<SCG::Stack<SharedPtr<U>>> &stackB)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type de l'objet pointé du premier élément de la pile. |
| U | Type de l'objet pointé du deuxième élément de la pile. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Pile LHS. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Pile RHS. |

### Valeur de retour

true si les tailles et les données des piles correspondent, false sinon.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&) method


Compare les dictionnaires triés de types mappés non-pointeurs.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, U>> &dictA, const SharedPtr<SCG::SortedDictionary<K, U>> &dictB)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| K | Type de clé. |
| U | Type mappé. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | Dictionnaire LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | Dictionnaire RHS. |

### Valeur de retour

true si les tailles et les données des dictionnaires correspondent, false sinon.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>) method


Compare les dictionnaires triés de types mappés pointeurs.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictB)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| K | Type de clé. |
| U | Type de l'objet pointé mappé. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Dictionnaire LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Dictionnaire RHS. |

### Valeur de retour

true si les tailles et les données des dictionnaires correspondent, false sinon.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K2, U2\>\>\&) method


Compare les dictionnaires triés de types différents.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K1, U1>> &dictA, const SharedPtr<SCG::SortedDictionary<K2, U2>> &dictB)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| K1 | Type de clé du dictionnaire LHS. |
| U1 | Type mappé du dictionnaire LHS. |
| K2 | Type de clé du dictionnaire RHS. |
| U2 | Type mappé du dictionnaire RHS. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K1, U1\>\>\& | Dictionnaire LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K2, U2\>\>\& | Dictionnaire RHS. |

### Valeur de retour

Toujours renvoie false car la conversion de type est interdite ici.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, U\>\>\&, const SharedPtr\<SCG::SortedList\<K, U\>\>\&) method


Compare les listes triées de types mappés non-pointeurs.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, U>> &dictA, const SharedPtr<SCG::SortedList<K, U>> &dictB)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| K | Type de clé. |
| U | Type mappé. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | Liste LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | Liste RHS. |

### Valeur de retour

true si les tailles et les données des listes correspondent, false sinon.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&) method


Compare les listes triées de types mappés pointeurs.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictB)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| K | Type de clé. |
| U | Type de l'objet pointé mappé. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Liste LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Liste RHS. |

### Valeur de retour

true si les tailles et les données des listes correspondent, false sinon.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedList\<K2, U2\>\>\&) method


Compare les listes triées de types différents.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K1, U1>> &dictA, const SharedPtr<SCG::SortedList<K2, U2>> &dictB)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| K1 | Type de clé de la liste LHS. |
| U1 | Type mappé de la liste LHS. |
| K2 | Type de clé de la liste RHS. |
| U2 | Type mappé de la liste RHS. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K1, U1\>\>\& | Liste LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K2, U2\>\>\& | Liste RHS. |

### Valeur de retour

Toujours renvoie false car la conversion de type est interdite ici.

## TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr\&, const System::Collections::Specialized::StringCollectionPtr\&) method


Compare les collections de chaînes.

```cpp
static bool System::TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr &arrA, const System::Collections::Specialized::StringCollectionPtr &arrB)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| arrA | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | Collection LHS. |
| arrB | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | Collection RHS. |

### Valeur de retour

True si les tailles et les données correspondent, false sinon.

## TestCompare::AreEqual(const System::SharedPtr\<SCG::IEnumerable\<T\>\>\&, const System::SharedPtr\<SCG::IEnumerable\<U\>\>\&) method


Compare les instances IEnumerable.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::SharedPtr<SCG::IEnumerable<T>> &et, const System::SharedPtr<SCG::IEnumerable<U>> &eu)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| et | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<T\>\>\& | Objet énumérable LHS. |
| eu | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<U\>\>\& | Objet énumérable RHS. |

### Valeur de retour

True si les tailles et les données correspondent, false sinon.

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../../array/)
* Class [List](../../../system.collections.generic/list/)
* Class [Dictionary](../../../system.collections.generic/dictionary/)
* Class [HashSet](../../../system.collections.generic/hashset/)
* Class [QueuePtr](../../../system.collections.generic/queueptr/)
* Class [Stack](../../../system.collections.generic/stack/)
* Class [SortedDictionary](../../../system.collections.generic/sorteddictionary/)
* Class [SortedList](../../../system.collections.generic/sortedlist/)
* Class [StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struct [TestCompare](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)