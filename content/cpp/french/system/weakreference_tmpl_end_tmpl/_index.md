---
title: WeakReference<>
second_title: Référence API Aspose.Slides pour C++
description: Représente une référence faible, qui référence un objet tout en permettant que cet objet soit supprimé.
type: docs
weight: 1496
url: /fr/system/weakreference_tmpl_end_tmpl/
---
## WeakReference<> classe

Représente une référence faible, qui référence un objet tout en permettant que cet objet soit supprimé.

```cpp
class WeakReference<> : public WeakReference<System::Object>
```

## Méthodes

| Méthode | Description |
| --- | --- |
| **bool** [get_IsAlive](./get_isalive/)() const | Obtient une indication indiquant si l'objet référencé par l'objet WeakReference actuel a été supprimé. |
| const [WeakPtr](../weakptr/)\<[Object](../object/)\>\& [get_Target](./get_target/)() const | Obtient l'objet (la cible) référencé par l'objet WeakReference actuel. |
| void [set_Target](./set_target/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Définit l'objet (la cible) référencé par l'objet WeakReference actuel. |
| [WeakReference](./weakreference/)() | Constructeur par défaut. |
| [WeakReference](./weakreference/)(std::nullptr_t) | Constructeur depuis nullptr. |
| [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Initialise une nouvelle instance de la classe WeakReference, référencant l'objet spécifié. |
| [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | Initialise une nouvelle instance de la classe WeakReference, référencant l'objet spécifié. |

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)