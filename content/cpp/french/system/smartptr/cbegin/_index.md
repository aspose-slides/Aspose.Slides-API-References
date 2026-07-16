---
title: cbegin()
second_title: Référence de l'API Aspose.Slides pour C++
description: Accesseur pour la méthode cbegin() d'une collection sous-jacente. Se compile uniquement si SmartPtr_ est un type de spécialisation avec la méthode cbegin().
type: docs
weight: 404
url: /fr/system/smartptr/cbegin/
---
## SmartPtr::cbegin() const méthode

Accesseur pour [cbegin()](./) méthode d'une collection sous-jacente. Se compile uniquement si SmartPtr_ est un type de spécialisation avec [cbegin()](./) méthode.

```cpp
template<typename Q> auto System::SmartPtr<T>::cbegin() const -> decltype(std::declval<const Q>().cbegin())
```

### Valeur de retour

itérateur vers le début de la collection

## Voir aussi

* Classe [SmartPtr](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)