---
title: IBiLevelEffectiveData
second_title: Référence de l'API Aspose.Slides pour Java
description: Objet immuable qui représente un effet bi-niveau noir/blanc.
type: docs
url: /fr/com.aspose.slides/ibileveleffectivedata/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBiLevelEffectiveData extends IEffectEffectiveData
```

Objet immuable qui représente un effet bi-niveau (noir/blanc). Les couleurs d’entrée dont la luminance est inférieure à la valeur seuil spécifiée sont changées en noir. Les couleurs d’entrée dont la luminance est supérieure ou égale à la valeur spécifiée sont définies en blanc. Les valeurs d’effet alpha ne sont pas affectées par cet effet.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getThreshold()](#getThreshold--) | Renvoie la valeur du seuil. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

Renvoie la valeur du seuil. Float en lecture seule.

**Retour :**
float