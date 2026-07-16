---
title: InitObject()
second_title: Référence de l'API Aspose.Slides pour C++
description: Démarre l'initialisation d'un objet avec une possession partagée.
type: docs
weight: 2237
url: /fr/system/initobject/
---
## System::InitObject(const SharedPtr\<T\>\&) fonction

Démarre l'initialisation d'un objet avec une possession partagée.

```cpp
template<typename T> Details::ObjectBuilder<T, SharedPtr<T>> System::InitObject(const SharedPtr<T> &object)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type d'objet à initialiser |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | [Object](../object/) à initialiser |

### Valeur de retour

ObjectBuilder configuré pour la construction d'un pointeur partagé

## Remarques

[Object](../object/) initialisation doit être terminée par l'appel [Get()](../get/)

## Voir aussi

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Bibliothèque [Aspose.Slides](../../)