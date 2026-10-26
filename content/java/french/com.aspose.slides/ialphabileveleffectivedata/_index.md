---
title: IAlphaBiLevelEffectiveData
second_title: Référence de l'API Aspose.Slides pour Java
description: Objet immuable qui représente un effet Alpha Bi-Level.
type: docs
url: /fr/com.aspose.slides/ialphabileveleffectivedata/
---
**Toutes les interfaces implémentées:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IAlphaBiLevelEffectiveData extends IEffectEffectiveData
```

Objet immuable qui représente un effet Alpha Bi-Level. Les valeurs Alpha (Opacity) inférieures au seuil sont changées à 0 (totalement transparent) et les valeurs alpha supérieures ou égales au seuil sont changées à 100 % (totalement opaque).
## Méthodes

| Méthode | Description |
| --- | --- |
| [getThreshold()](#getThreshold--) | Renvoie le seuil de l'effet. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

Renvoie le seuil de l'effet. Float en lecture seule.

**Retour:**
float