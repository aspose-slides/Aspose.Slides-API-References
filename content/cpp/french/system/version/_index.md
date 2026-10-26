---
title: Version
second_title: Référence de l'API Aspose.Slides pour C++
description: "Représente un numéro de version. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe System::SmartPtr pour gérer des objets de ce type."
type: docs
weight: 1444
url: /fr/system/version/
---
## Version classe


Représente un numéro de version. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe [System::SmartPtr](../smartptr/) pour gérer des objets de ce type.

```cpp
class Version
```

## Méthodes

| Méthode | Description |
| --- | --- |
| int [CompareTo](./compareto/)(const [Version](./)\&) const | Compare les versions représentées par l'objet actuel et l'objet spécifié. |
| **bool** [Equals](./equals/)(const [Version](./)\&) const | Détermine si les numéros de version représentés par l'objet actuel et l'objet spécifié sont égaux. |
| int [get_Build](./get_build/)() const | Retourne le numéro de build. |
| int [get_Major](./get_major/)() const | Retourne la version majeure. |
| **int16_t** [get_MajorRevision](./get_majorrevision/)() const | Retourne la valeur haute de 16 bits du numéro de révision. |
| int [get_Minor](./get_minor/)() const | Retourne la version mineure. |
| **int16_t** [get_MinorRevision](./get_minorrevision/)() const | Retourne la valeur basse de 16 bits du numéro de révision. |
| int [get_Revision](./get_revision/)() const | Retourne le numéro de révision. |
| int [GetHashCode](./gethashcode/)() const | Retourne un code de hachage pour l'objet actuel. |
| static [Version](./) [Parse](./parse/)(const [String](../string/)\&) | Convertit la représentation sous forme de chaîne d'un numéro de version en une instance équivalente de la classe [Version](./). |
| [String](../string/) [ToString](./tostring/)() const | Retourne la représentation sous forme de chaîne du numéro de version représenté par l'objet actuel. |
| [String](../string/) [ToString](./tostring/)(int) const | Retourne la représentation sous forme de chaîne du nombre spécifié de sections du numéro de version représenté par l'objet actuel. |
|  [Version](./version/)(int, int, int, int) | Construit une instance qui représente les valeurs majeures, mineures, de build et de révision spécifiées. |
|  [Version](./version/)(int, int, int) | Construit une instance qui représente les valeurs majeures, mineures et de build spécifiées. |
|  [Version](./version/)(int, int) | Construit une instance qui représente les valeurs majeures et les valeurs spécifiées. |
|  [Version](./version/)(const [String](../string/)\&) | Construit une instance qui représente le numéro de version représenté sous forme de chaîne. |
|  [Version](./version/)() | Construit une instance qui représente le numéro de version 0.0.-1.-1. |
## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)