---
title: STDIOStreamPositionPreference
second_title: Référence de l'API Aspose.Slides pour C++
description: "Détermine quelle position dans le flux est préférable comme position de lecture et d’écriture commune lorsque std::basic_iostream et ses descendants auront des positions de lecture et d’écriture différentes au moment de la création du wrapper."
type: docs
weight: 586
url: /fr/system.io/stdiostreampositionpreference/
---
## STDIOStreamPositionPreference enum

Détermine quelle position dans le flux est préférable comme position de lecture et d’écriture commune lorsque std::basic_iostream et ses descendants auront des positions de lecture et d’écriture différentes au moment de la création du wrapper.

```cpp
enum class STDIOStreamPositionPreference
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Zero | 0 | La position zéro sera définie comme position de lecture et d’écriture. |
| ReadPosition | 1 | La position gptr sera définie comme position de lecture et d’écriture. |
| WritePosition | 2 | La position pptr sera définie comme position de lecture et d’écriture. |

## Voir aussi

* Espace de noms [System::IO](../)
* Bibliothèque [Aspose.Slides](../../)