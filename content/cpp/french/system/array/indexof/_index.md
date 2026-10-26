---
title: IndexOf()
second_title: Référence de l'API Aspose.Slides for C++
description: Détermine l'index de la première occurrence de l'élément spécifié dans le tableau.
type: docs
weight: 131
url: /fr/system/array/indexof/
---
## Array::IndexOf(const T\&) const méthode


Détermine l'index de la première occurrence de l'élément spécifié dans le tableau.

```cpp
virtual int System::Array<T>::IndexOf(const T &item) const override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| item | const T\& | Indice de l'élément dont il faut déterminer l'index |

### Valeur de retour

Index de la première occurrence de l'élément spécifié si l'élément est trouvé, sinon -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) méthode


Détermine l'index de la première occurrence de l'élément spécifié dans le tableau.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| ArrayType | Type des éléments dans le tableau cible |
| ValueType | type de l'élément à rechercher dans le tableau |

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) pour rechercher l'élément spécifié dans |
| value | const [ValueType](../valuetype/)\& | Indice de l'élément dont il faut déterminer l'index |

### Valeur de retour

Index de la première occurrence de l'élément spécifié si l'élément est trouvé, sinon -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) méthode


Détermine l'index de la première occurrence de l'élément spécifié dans le tableau à partir de l'index spécifié.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| ArrayType | Type des éléments dans le tableau cible |
| ValueType | type de l'élément à rechercher dans le tableau |

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) pour rechercher l'élément spécifié dans |
| value | const [ValueType](../valuetype/)\& | Indice de l'élément dont il faut déterminer l'index |
| startIndex | int | Index à partir duquel la recherche commence |

### Valeur de retour

Index de la première occurrence de l'élément spécifié si l'élément est trouvé, sinon -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) méthode


Détermine l'index de la première occurrence de l'élément spécifié dans une plage d'éléments du tableau spécifiée par l'index de départ et le nombre d'éléments de la plage.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| ArrayType | Type des éléments dans le tableau cible |
| ValueType | type de l'élément à rechercher dans le tableau |

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) pour rechercher l'élément spécifié dans |
| value | const [ValueType](../valuetype/)\& | Indice de l'élément dont il faut déterminer l'index |
| startIndex | int | Index à partir duquel la recherche commence |
| count | int | Nombre d'éléments de la plage dans laquelle rechercher |

### Valeur de retour

Index de la première occurrence de l'élément spécifié si l'élément est trouvé, sinon -1

## Voir aussi

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Classe [Array](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)