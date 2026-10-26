---
title: begin()
second_title: Référence de l'API Aspose.Slides pour C++
description: Accesseur pour la méthode begin() d'une collection sous-jacente. Ne compile que si SmartPtr_ est un type de spécialisation avec la méthode begin().
type: docs
weight: 378
url: /fr/system/smartptr/begin/
---
## SmartPtr::begin() méthode


Accesseur pour la méthode [begin()](./) d'une collection sous-jacente. Ne compile que si SmartPtr_ est un type de spécialisation avec la méthode [begin()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() -> decltype(std::declval<Q>().begin())
```


### Valeur de retour

itérateur vers le début de la collection

## SmartPtr::begin() const méthode


Accesseur pour la méthode [begin()](./) d'une collection sous-jacente. Ne compile que si SmartPtr_ est un type de spécialisation avec la méthode [begin()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() const -> decltype(std::declval<const Q>().begin())
```


### Valeur de retour

itérateur vers le début de la collection

## Voir aussi

* Classe [SmartPtr](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)