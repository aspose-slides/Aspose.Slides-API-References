---
title: IAlphaBiLevelEffectiveData
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Unveränderliches Objekt, das einen Alpha Bi-Level Effekt darstellt.
type: docs
url: /de/com.aspose.slides/ialphabileveleffectivedata/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IAlphaBiLevelEffectiveData extends IEffectEffectiveData
```

Unveränderliches Objekt, das einen Alpha-Bi-Level-Effekt darstellt. Alpha-(Deckkraft-)Werte, die kleiner als der Schwellenwert sind, werden zu 0 (vollständig transparent) geändert, und Alpha-Werte, die größer oder gleich dem Schwellenwert sind, werden zu 100 % (vollständig undurchsichtig) geändert.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getThreshold()](#getThreshold--) | Gibt den Effekt-Schwellenwert zurück. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


Gibt den Effekt-Schwellenwert zurück. Nur-Lese-float.

**Rückgabe:**
float