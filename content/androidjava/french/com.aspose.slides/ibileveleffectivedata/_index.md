---
title: IBiLevelEffectiveData
second_title: Aspose.Slides pour Android via la référence API Java
description: Objet immuable qui représente un effet binaire noir/blanc.
type: docs
url: /fr/com.aspose.slides/ibileveleffectivedata/
---
**Toutes les interfaces implémentées:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBiLevelEffectiveData extends IEffectEffectiveData
```

Objet immuable qui représente un effet binaire (noir/blanc). Les couleurs d'entrée dont la luminance est inférieure à la valeur de seuil spécifiée sont converties en noir. Les couleurs d'entrée dont la luminance est supérieure ou égale à la valeur spécifiée sont converties en blanc. Les valeurs d'effet alpha ne sont pas affectées par cet effet.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getThreshold()](#getThreshold--) | Renvoie la valeur du seuil. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

Renvoie la valeur du seuil. Flottant en lecture seule.

**Renvoie:** 
float