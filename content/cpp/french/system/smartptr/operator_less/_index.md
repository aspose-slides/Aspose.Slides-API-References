---
title: operator<()
second_title: Aspose.Slides pour l'API C++
description: Fournit une sémantique de comparaison inférieure pour la classe SmartPtr.
type: docs
weight: 235
url: /fr/system/smartptr/operator_less/
---
## SmartPtr::operator<(Y *) const méthode

Fournit une sémantique de comparaison inférieure pour la classe [SmartPtr](../).

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(Y *p) const
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Y | Type de pointeur à comparer avec le pointeur actuel. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| p | Y * | Pointeur à comparer avec le pointeur actuel. |

### Valeur de retour

Vrai si l'objet référencé par [SmartPtr](../) est « moins » que p et faux sinon.

## SmartPtr::operator<(SmartPtr\<Y\> const\&) const méthode

Fournit une sémantique de comparaison inférieure pour la classe [SmartPtr](../).

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(SmartPtr<Y> const &x) const
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Y | Type de pointeur à comparer avec le pointeur actuel. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | [SmartPtr](../)\<Y\> const\& | Pointeur à comparer avec le pointeur actuel. |

### Valeur de retour

Vrai si l'objet référencé par [SmartPtr](../) est « moins » que x et faux sinon.

## Voir aussi

* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)