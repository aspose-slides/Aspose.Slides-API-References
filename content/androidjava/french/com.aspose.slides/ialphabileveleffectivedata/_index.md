---
title: IAlphaBiLevelEffectiveData
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Objet immuable qui représente un effet Alpha à deux niveaux.
type: docs
url: /fr/com.aspose.slides/ialphabileveleffectivedata/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IAlphaBiLevelEffectiveData extends IEffectEffectiveData
```

Objet immuable qui représente un effet Alpha Bi-Level. Les valeurs Alpha (Opacité) inférieures au seuil sont transformées en 0 (complètement transparent) et les valeurs alpha supérieures ou égales au seuil sont transformées en 100 % (complètement opaque).

## Méthodes

| Méthode | Description |
| --- | --- |
| [getThreshold()](#getThreshold--) | Renvoie le seuil de l'effet. |

### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

Renvoie le seuil de l'effet. Float en lecture seule.

**Renvoie :**
float