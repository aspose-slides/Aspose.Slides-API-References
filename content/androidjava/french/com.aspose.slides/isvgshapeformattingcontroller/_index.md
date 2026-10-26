---
title: ISvgShapeFormattingController
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Contrôle la génération de formes SVG.
type: docs
url: /fr/com.aspose.slides/isvgshapeformattingcontroller/
---```
public interface ISvgShapeFormattingController
```

Contrôle la génération de formes SVG.
## Méthodes

| Méthode | Description |
| --- | --- |
| [formatShape(ISvgShape svgShape, IShape shape)](#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-) | Cette fonction est appelée avant le rendu de la forme en SVG pour permettre à l'utilisateur de contrôler le SVG résultant. |
### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public abstract void formatShape(ISvgShape svgShape, IShape shape)
```

Cette fonction est appelée avant le rendu de la forme en SVG pour permettre à l'utilisateur de contrôler le SVG résultant.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) | Objet permettant de contrôler la génération de formes SVG. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forme source. |