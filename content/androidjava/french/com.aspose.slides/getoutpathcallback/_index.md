---
title: Convert.GetOutPathCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /fr/com.aspose.slides/convert.getoutpathcallback/
---```
public static interface Convert.GetOutPathCallback
```
## Méthodes

| Méthode | Description |
| --- | --- |
| [invoke(Slide slide, int index)](#invoke-com.aspose.slides.Slide-int-) | Rappel qui sera invoqué pour chaque [Slide](../../com.aspose.slides/slide), le chemin de sortie devant être renvoyé. |
### invoke(Slide slide, int index) {#invoke-com.aspose.slides.Slide-int-}
```
public abstract String invoke(Slide slide, int index)
```

Rappel qui sera invoqué pour chaque [Slide](../../com.aspose.slides/slide), le chemin de sortie devant être renvoyé.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| slide | [Slide](../../com.aspose.slides/slide) | Diapositive actuelle itérée |
| index | int | Index de la diapositive actuelle |

**Renvoie :**
java.lang.String