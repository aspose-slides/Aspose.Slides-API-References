---
title: cend()
second_title: Référence API Aspose.Slides pour C++
description: Accesseur pour la méthode cend() d'une collection sous-jacente. Ne compile que si SmartPtr_ est de type spécialisation avec la méthode cend().
type: docs
weight: 417
url: /fr/system/smartptr/cend/
---
## SmartPtr::cend() const méthode

Accesseur pour [cend()](./) méthode d'une collection sous-jacente. Ne compile que si SmartPtr_ est de type spécialisation avec la méthode [cend()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::cend() const -> decltype(std::declval<const Q>().cend())
```

### Valeur de retour

itérateur vers la fin de la collection

## Voir aussi

* Classe [SmartPtr](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)