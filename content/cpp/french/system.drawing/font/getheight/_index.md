---
title: GetHeight()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie l'espacement des lignes de la police représentée par l'objet actuel, dans l'unité actuelle d'un objet Graphics spécifié.
type: docs
weight: 14
url: /fr/system.drawing/font/getheight/
---
## Font::GetHeight(const SharedPtr\<Graphics\>\&) méthode


Renvoie l'espacement des lignes de la police représentée par l'objet actuel, dans l'unité actuelle d'un objet [Graphics](../../graphics/) spécifié.

```cpp
float System::Drawing::Font::GetHeight(const SharedPtr<Graphics> &graphics)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Un objet [Graphics](../../graphics/) qui spécifie les unités de mesure |

## Font::GetHeight(float) méthode


Renvoie la hauteur de la police représentée par l'objet actuel lorsqu'elle est dessinée sur un dispositif d'affichage avec la résolution verticale spécifiée.

```cpp
float System::Drawing::Font::GetHeight(float dpi=DEFAULT_FONT_OPERATIONS_DPI)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| dpi | **float** | La résolution verticale du dispositif d'affichage |

### Valeur de retour

La hauteur de la police en pixels

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Graphics](../../graphics/)
* Classe [Font](../)
* Espace de noms [System::Drawing](../../)
* Bibliothèque [Aspose.Slides](../../../)