---
title: STDIOStreamWrappingMode
second_title: Référence de l'API Aspose.Slides pour C++
description: "Spécifie le mode des opérations d'E/S que les wrappers effectueront sur des flux de type std::iostreams-like."
type: docs
weight: 573
url: /fr/system.io/stdiostreamwrappingmode/
---
## STDIOStreamWrappingMode enum


Spécifie le mode des opérations d'E/S que les wrappers effectueront sur des flux de type std::iostreams-like.

```cpp
enum class STDIOStreamWrappingMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Binary | 0 | Un mode qui permet aux opérations d'entrée de décoder les données du flux de type char_type en octets, et d'encoder les octets en données de type char_type pour les opérations de sortie. |
| Conversion | 1 | Un mode qui permet aux opérations d'entrée de convertir les données du flux du type char_type vers le type **uint8_t** et inversement pour les opérations de sortie. |

## Voir aussi

* Espace de noms [System::IO](../)
* Bibliothèque [Aspose.Slides](../../)