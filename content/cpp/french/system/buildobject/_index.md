---
title: BuildObject()
second_title: Référence API Aspose.Slides pour C++
description: Construisez un objet avec une propriété partagée.
type: docs
weight: 2224
url: /fr/system/buildobject/
---
## System::BuildObject(Args\&&...) fonction


Construisez un objet avec une propriété partagée.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T, SharedPtr<T>> System::BuildObject(Args &&... args)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type d'objet à construire |
| Args | Types d'arguments pour la construction de l'objet |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| args | Args\&&... | Arguments à transmettre au constructeur de l'objet |

### Valeur de retour

ObjectBuilder configuré pour la construction d’un pointeur partagé
## Remarques



Crée un SharedPtr<T> et renvoie un constructeur pour celui-ci
La construction [Object](../object/) doit être terminée par l'appel [Get()](../get/)

## Voir aussi

* Typedef [SharedPtr](../sharedptr/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)