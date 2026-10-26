---
title: RemoveAliasing()
second_title: Référence de l'API Aspose.Slides pour C++
description: Supprime l'aliasage (créé par un constructeur d'aliasage) du pointeur, en veillant à ce qu'il gère (si partagé) ou suive (si faible) le même objet vers lequel il pointe.
type: docs
weight: 170
url: /fr/system/smartptr/removealiasing/
---
## SmartPtr::RemoveAliasing() const méthode

Supprime l'aliasage (créé par un constructeur d'aliasage) du pointeur, s'assure qu'il gère (si partagé) ou suit (si faible) le même objet vers lequel il pointe.

```cpp
SmartPtr_ System::SmartPtr<T>::RemoveAliasing() const
```

### Valeur de retour

Le pointeur vers le même objet que ce pointeur pointe, qui veille sur la durée de vie du même objet.

## Voir aussi

* Typedef [SmartPtr_](../smartptr_/)
* classe [SmartPtr](../)
* espace de noms [System](../../)
* bibliothèque [Aspose.Slides](../../../)