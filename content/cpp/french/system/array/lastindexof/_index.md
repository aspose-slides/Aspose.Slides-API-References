---
title: LastIndexOf()
second_title: Référence de l'API Aspose.Slides pour C++
description: Détermine l'index de la dernière occurrence de l'élément spécifié dans une plage d'éléments du tableau spécifiée par l'index de départ et le nombre d'éléments de la plage.
type: docs
weight: 703
url: /fr/system/array/lastindexof/
---
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) méthode


Détermine l'index de la dernière occurrence de l'élément spécifié dans une plage d'éléments du tableau spécifiée par l'index de départ et le nombre d'éléments de la plage.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| ArrayType | Type des éléments du tableau cible |
| ValueType | type de l'élément à rechercher dans le tableau |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) pour rechercher l'élément spécifié dans |
| value | const [ValueType](../valuetype/)\& | Indice de l'élément dont l'index doit être déterminé |
| startIndex | int | Index auquel la recherche commence |
| count | int | Nombre d'éléments de la plage à explorer |

### Valeur de retour

Index de la dernière occurrence de l'élément spécifié si l'élément est trouvé, sinon -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) méthode


Détermine l'index de la dernière occurrence de l'élément spécifié dans le tableau à partir de l'index spécifié.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value, int startIndex)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| ArrayType | Type des éléments du tableau cible |
| ValueType | type de l'élément à rechercher dans le tableau |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) pour rechercher l'élément spécifié dans |
| value | const [ValueType](../valuetype/)\& | Indice de l'élément dont l'index doit être déterminé |
| startIndex | int | Index auquel la recherche commence |

### Valeur de retour

Index de la dernière occurrence de l'élément spécifié si l'élément est trouvé, sinon -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) méthode


Détermine l'index de la dernière occurrence de l'élément spécifié dans le tableau.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| ArrayType | Type des éléments du tableau cible |
| ValueType | type de l'élément à rechercher dans le tableau |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) pour rechercher l'élément spécifié dans |
| value | const [ValueType](../valuetype/)\& | Indice de l'élément dont l'index doit être déterminé |

### Valeur de retour

Index de la dernière occurrence de l'élément spécifié si l'élément est trouvé, sinon -1

## Voir aussi

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)