---
title: ShapeThumbnailBounds
second_title: Référence API Aspose.Slides pour Java
description: Énumération des types de limites de vignette de forme.
type: docs
url: /fr/com.aspose.slides/shapethumbnailbounds/
---
**Héritage:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ShapeThumbnailBounds extends System.Enum
```

Énumération des types de limites de vignette de forme.
## Champs

| Champ | Description |
| --- | --- |
| [Slide](#Slide) | La vignette de forme aura la taille égale à la taille de la diapositive. |
| [Shape](#Shape) | La vignette de forme aura la taille égale au rectangle des limites de forme en tenant compte des paramètres du contour de la forme. |
| [Appearance](#Appearance) | La vignette de forme aura la taille égale à l'apparence de la forme (dans les limites d'une diapositive). |
### Slide {#Slide}
```
public static final int Slide
```

La vignette de forme aura la taille égale à la taille de la diapositive. La position de la forme sera enregistrée.

### Shape {#Shape}
```
public static final int Shape
```

La vignette de forme aura la taille égale au rectangle des limites de forme en tenant compte des paramètres du contour de la forme.

### Appearance {#Appearance}
```
public static final int Appearance
```

La vignette de forme aura la taille égale à l'apparence de la forme (dans les limites d'une diapositive). Il peut y avoir des cas où l'apparence de la forme ne rentre pas dans les limites de la forme. Par exemple, rotation, jointure en onglet d'angle aigu, effets 3D, etc.