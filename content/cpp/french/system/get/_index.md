---
title: Get()
second_title: Référence de l'API Aspose.Slides pour C++
description: Fonction permettant d'obtenir le N-ième élément du tuple fourni. Surcharge pour l'objet de base.
type: docs
weight: 2367
url: /fr/system/get/
---
## System::Get(const SharedPtr\<Object\>\&) function

Fonction permettant d'obtenir le N-ième élément du tuple fourni. Surcharge pour l'objet de base.

```cpp
template<std::size_t> auto System::Get(const SharedPtr<Object> &object)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| N | index de l'élément. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | objet à inspecter. |

### Valeur de retour

valeur du N-ième élément du tuple convertie en objet.

## System::Get(const T\&) function

Fonction permettant d'obtenir le N-ième élément du tuple fourni. Surcharge pour les objets disposant d'une méthode Deconstruct.

```cpp
template<std::size_t,typename T> auto System::Get(const T &object)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| N | index de l'élément. |
| T | type de l'objet inspecté. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| object | const T\& | objet à inspecter. |

### Valeur de retour

valeur du N-ième élément du tuple.

## System::Get(const SharedPtr\<T\>\&) function

Fonction permettant d'obtenir le N-ième élément du tuple fourni. Surcharge pour les pointeurs partagés.

```cpp
template<std::size_t,typename T> auto System::Get(const SharedPtr<T> &pointer)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| N | index de l'élément. |
| T | type de l'objet inspecté. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | objet à inspecter. |

### Valeur de retour

valeur du N-ième élément du tuple.

## System::Get(const ValueTuple\<Args...\>\&) function

Obtient le N-ième élément du tuple de valeurs.

```cpp
template<std::size_t,typename...> auto System::Get(const ValueTuple<Args...> &tuple)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| N | index de l'élément. |
| Args | éléments du tuple. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| tuple | const [ValueTuple](../valuetuple/)\<Args...\>\& | tuple dont on veut obtenir l'élément. |

### Valeur de retour

valeur du N-ième élément du tuple.

## Voir aussi

* Typedef [SharedPtr](../sharedptr/)
* Class [Object](../object/)
* Class [ValueTuple](../valuetuple/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)