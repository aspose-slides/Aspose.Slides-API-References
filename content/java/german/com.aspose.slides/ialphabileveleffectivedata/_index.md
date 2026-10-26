---
title: IAlphaBiLevelEffectiveData
second_title: Aspose.Slides für Java API Referenz
description: Unveränderliches Objekt, das einen Alpha-Bi-Level-Effekt darstellt.
type: docs
url: /de/com.aspose.slides/ialphabileveleffectivedata/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IAlphaBiLevelEffectiveData extends IEffectEffectiveData
```

Unveränderliches Objekt, das einen Alpha-Bi-Level-Effekt darstellt. Alpha-(Deckkraft-)Werte, die kleiner als der Schwellenwert sind, werden auf 0 (vollständig transparent) geändert, und Alpha-Werte, die größer oder gleich dem Schwellenwert sind, werden auf 100 % (vollständig undurchsichtig) geändert.
## Methoden

| Method | Beschreibung |
| --- | --- |
| [getThreshold()](#getThreshold--) | Gibt den Effekt-Schwellenwert zurück. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


Gibt den Effekt-Schwellenwert zurück. Nur lesbarer float.

**Rückgabe:**
float