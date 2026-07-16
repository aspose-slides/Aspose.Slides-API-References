---
title: GetTile()
second_title: Référence API Aspose.Slides pour C++
description: Crée une image de tuile pour le remplissage du motif avec des couleurs spécifiées.
type: docs
weight: 53
url: /fr/aspose.slides/patternformat/gettile/
---
## PatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) méthode


Crée une image de tuile pour le remplissage du motif avec des couleurs spécifiées.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | L'arrière-plan [System::Drawing::Color](../../../system.drawing/color/) du motif. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | Le premier plan [System::Drawing::Color](../../../system.drawing/color/) du motif. |

### Valeur de retour

Tuile [IImage](../../iimage/).

## PatternFormat::GetTile(System::Drawing::Color) méthode


Crée une image de tuile pour le remplissage du motif.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color styleColor) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | La couleur par défaut [System::Drawing::Color](../../../system.drawing/color/) |

### Valeur de retour

Tuile [IImage](../../iimage/).

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [Color](../../../system.drawing/color/)
* Class [PatternFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)