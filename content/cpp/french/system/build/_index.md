---
title: Build()
second_title: Aspose.Slides pour C++ Référence de l'API
description: Construire un objet avec une possession directe.
type: docs
weight: 2263
url: /fr/system/build/
---
## System::Build(Args\&&...) fonction

Construire un objet avec une possession directe.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T> System::Build(Args &&... args)
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

ObjectBuilder configuré pour la construction directe d'objet

## Remarques

[Object](../object/) construction doit être terminée par l'appel [Get()](../get/)

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)