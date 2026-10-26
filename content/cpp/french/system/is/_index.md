---
title: Is()
second_title: Référence de l'API Aspose.Slides pour C++
description: Implémente la traduction du modèle de déclaration 'is'.
type: docs
weight: 2276
url: /fr/system/is/
---
## System::Is(const ExpressionT\&, ResultT\&) fonction


Implémente la traduction du modèle de déclaration 'is'.

```cpp
template<class PatternT,class ExpressionT,class ResultT> bool System::Is(const ExpressionT &left, ResultT &result)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| PatternT | type à vérifier. |
| ExpressionT | type d'expression gauche. |
| ResultT | type de l'expression de résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| left | const ExpressionT\& | expression qui sera vérifiée. |
| result | ResultT\& | variable à laquelle sera assigné le type vérifié. |

### Valeur de retour

true si le contrôle du type réussit, false sinon.

## System::Is(const ExpressionT\&, const ConstantT\&) fonction


Implémente la traduction du modèle constant 'is'.

```cpp
template<class ExpressionT,class ConstantT> std::enable_if_t<!std::is_base_of<Details::Pattern, ConstantT>::value, bool> System::Is(const ExpressionT &left, const ConstantT &constant)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| ExpressionT | type d'expression gauche. |
| ConstantT | type d'expression constante. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| left | const ExpressionT\& | expression qui sera vérifiée. |
| constant | const ConstantT\& | expression qui sera comparée à celle de gauche. |

### Valeur de retour

true si le contrôle du type réussit, false sinon.

## System::Is(const E\&, const A\&) fonction


Fonction de correspondance de niveau supérieur. Applique un modèle à une valeur.

```cpp
template<typename A,typename E> std::enable_if_t<std::is_base_of<Details::Pattern, A>::value, bool> System::Is(const E &e, const A &a)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| A | Type de modèle (doit hériter de Details::Pattern). |
| E | Type de la valeur à correspondre. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| e | const E\& | Valeur à comparer. |
| a | const A\& | Modèle à appliquer. |

### Valeur de retour

true si le modèle correspond à la valeur, false sinon.

## Voir aussi

* Namespace [System](../)
* Library [Aspose.Slides](../../)