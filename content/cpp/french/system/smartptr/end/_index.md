---
title: end()
second_title: Référence de l'API Aspose.Slides pour C++
description: Accesseur de la méthode end() d'une collection sous-jacente. Ne se compile que si SmartPtr_ est un type de spécialisation avec la méthode end().
type: docs
weight: 391
url: /fr/system/smartptr/end/
---
## SmartPtr::end() méthode


Accesseur de la méthode [end()](./) d'une collection sous-jacente. Ne se compile que si SmartPtr_ est un type de spécialisation avec la méthode [end()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::end() -> decltype(std::declval<Q>().end())
```


### Valeur de retour

itérateur vers la fin de la collection

## SmartPtr::end() const méthode


Accesseur de la méthode [end()](./) d'une collection sous-jacente. Ne se compile que si SmartPtr_ est un type de spécialisation avec la méthode [end()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::end() const -> decltype(std::declval<const Q>().end())
```


### Valeur de retour

itérateur vers la fin de la collection

## Voir aussi

* Classe [SmartPtr](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)