---
title: CombineMode
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie comment les régions de découpe sont combinées.
type: docs
weight: 170
url: /fr/system.drawing.drawing2d/combinemode/
---
## enum CombineMode

Spécifie comment les régions de découpe sont combinées.

```cpp
enum class CombineMode
```

### Valeurs

| Name | Value | Description |
| --- | --- | --- |
| Replace | 0 | Une région de découpe est remplacée par une autre. |
| Intersect | 1 | Les deux régions de découpe sont combinées en prenant leur intersection. |
| Union | 2 | Les deux régions de découpe sont combinées en prenant l'union des deux. |
| Xor | 3 | Les deux régions de découpe sont combinées en ne conservant que la zone englobée par l'une ou l'autre des régions, mais pas les deux. |
| Exclude | 4 | Deux régions de découpe sont combinées en prenant la zone de la première région qui n'intersecte pas la deuxième. |
| Complement | 5 | Deux régions de découpe sont combinées en prenant la zone de la deuxième région qui n'intersecte pas la première. |

## Voir aussi

* Espace de noms [System::Drawing::Drawing2D](../)
* Bibliothèque [Aspose.Slides](../../)