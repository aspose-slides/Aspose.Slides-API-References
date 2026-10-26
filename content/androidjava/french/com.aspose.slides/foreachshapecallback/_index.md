---
title: ForEach.ForEachShapeCallback
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: 
type: docs
url: /fr/com.aspose.slides/foreach.foreachshapecallback/
---```
public static interface ForEach.ForEachShapeCallback
```
## Méthodes

| Méthode | Description |
| --- | --- |
| [invoke(Shape shape, BaseSlide slide, int index)](#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-) | Rappel qui sera invoqué pour chaque [Shape](../../com.aspose.slides/shape) dans le [Presentation](../../com.aspose.slides/presentation). |
### invoke(Shape shape, BaseSlide slide, int index) {#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Shape shape, BaseSlide slide, int index)
```

Rappel qui sera invoqué pour chaque [Shape](../../com.aspose.slides/shape) dans le [Presentation](../../com.aspose.slides/presentation).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.slides/shape) | Forme actuellement itérée |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Diapositive actuellement itérée |
| index | int | Index de la diapositive de mise en page actuelle |