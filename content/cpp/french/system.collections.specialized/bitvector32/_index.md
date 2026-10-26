---
title: BitVector32
second_title: Référence de l'API Aspose.Slides pour C++
description: Fournit un vecteur de bits léger et simple avec un accès entier ou booléen facile à un stockage de 32 bits.
type: docs
weight: 1
url: /fr/system.collections.specialized/bitvector32/
---
## BitVector32 classe

Fournit un vecteur de bits léger et simple avec un accès entier ou [Boolean](../../system/boolean/) facile à un stockage de 32 bits.

```cpp
class BitVector32
```

## Méthodes

| Méthode | Description |
| --- | --- |
|  [BitVector32](./bitvector32/)() | Initialise une nouvelle instance vide de [BitVector32](./). |
|  [BitVector32](./bitvector32/)(**int32_t**) | Initialise une nouvelle instance de la structure [BitVector32](./) avec les données internes spécifiées. |
|  [BitVector32](./bitvector32/)(const [BitVector32](./)\&) | Initialise une nouvelle instance de la structure [BitVector32](./) avec les informations de la valeur spécifiée. |
| static **int32_t** [CreateMask](./createmask/)() | Crée le premier masque d'une série. |
| static **int32_t** [CreateMask](./createmask/)(**int32_t**) | Crée le masque suivant d'une série. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**) | Crée la première section d'une série, avec la valeur maximale spécifiée. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**, **BitVector32::Section**) | Crée la section suivante d'une série, avec la valeur maximale spécifiée. |
| **bool** [Equals](./equals/)(const [BitVector32](./)\&) | Détermine si l'objet spécifié est le même que celui en cours. |
| **int32_t** [get_Data](./get_data/)() | renvoie les données brutes stockées dans ce vecteur de bits... |
| **int32_t** [GetHashCode](./gethashcode/)() const | Renvoie un code de hachage pour l'objet en cours. |
| **bool** [idx_get](./idx_get/)(**int32_t**) | Obtient une valeur indiquant si tous les bits spécifiés sont définis. |
| **int32_t** [idx_get](./idx_get/)(**BitVector32::Section**) | Obtient la valeur pour la section spécifiée. |
| void [idx_set](./idx_set/)(**int32_t**, **bool**) | Définit une valeur indiquant si tous les bits spécifiés sont définis. |
| void [idx_set](./idx_set/)(**BitVector32::Section**, **int32_t**) | Définit la valeur pour la section spécifiée. |
| static [String](../../system/string/) [ToString](./tostring/)(const [BitVector32](./)\&) | Convertit la valeur représentée par le paramètre value en chaîne. |
| [String](../../system/string/) [ToString](./tostring/)() const | Convertit la valeur représentée par l'objet actuel en chaîne. |

## Voir aussi

* Espace de noms [System::Collections::Specialized](../)
* Bibliothèque [Aspose.Slides](../../)