---
title: GetTile()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une image de tuile pour le remplissage du motif avec des couleurs spécifiées.
type: docs
weight: 53
url: /fr/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) méthode


Crée une image de tuile pour le remplissage du motif avec des couleurs spécifiées.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | L'arrière-plan [System::Drawing::Color](../../../system.drawing/color/) du motif. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | Le premier plan [System::Drawing::Color](../../../system.drawing/color/) du motif. |

### Valeur de retour

Tuile [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## IPatternFormat::GetTile(System::Drawing::Color) méthode


Crée une image de tuile pour le remplissage du motif.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | Le [System::Drawing::Color](../../../system.drawing/color/) par défaut, défini dans l'objet StyleEx de ShapeEx. Les couleurs du remplissage peuvent dépendre de cela. |

### Valeur de retour

Tuile [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [Color](../../../system.drawing/color/)
* Class [IPatternFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)