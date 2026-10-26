---
title: CharacterRange
second_title: Référence API Aspose.Slides pour C++
description: "Représente une plage de positions de caractères dans une chaîne. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe System::SmartPtr pour gérer les objets de ce type."
type: docs
weight: 40
url: /fr/system.drawing/characterrange/
---
## CharacterRange classe

Représente une plage de positions de caractères dans une chaîne. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe [System::SmartPtr](../../system/smartptr/) pour gérer les objets de ce type.

```cpp
class CharacterRange
```

## Méthodes

| Method | Description |
| --- | --- |
|  [CharacterRange](./characterrange/)(**int32_t**, **int32_t**) | Construit une nouvelle instance de la classe [CharacterRange](./) qui représente la plage spécifiée. |
|  [CharacterRange](./characterrange/)() | Construit une nouvelle instance de la classe [CharacterRange](./) qui représente une plage vide. |
| **int32_t** [get_First](./get_first/)() const | Renvoie la position du premier caractère de la plage représentée par l'objet actuel. |
| **int32_t** [get_Length](./get_length/)() const | Renvoie le nombre de caractères dans la plage représentée par l'objet actuel. |
| **bool** [operator!=](./operator_not_equal/)(const [CharacterRange](./)\&) const | Détermine si l'objet actuel et l'objet spécifié représentent des plages distinctes. |
| **bool** [operator==](./operator_equal_equal/)(const [CharacterRange](./)\&) const | Détermine si l'objet actuel et l'objet spécifié représentent la même plage. |
| void [set_First](./set_first/)(**int32_t**) | Définit la position du premier caractère de la plage représentée par l'objet actuel. |
| void [set_Length](./set_length/)(**int32_t**) | Renvoie le nombre de caractères dans la plage représentée par l'objet actuel. |
## Voir aussi

* Espace de noms [System::Drawing](../)
* Bibliothèque [Aspose.Slides](../../)