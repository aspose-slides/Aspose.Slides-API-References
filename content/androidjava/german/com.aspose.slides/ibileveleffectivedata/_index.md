---
title: IBiLevelEffectiveData
second_title: Aspose.Slides für Android über Java API Referenz
description: Unveränderliches Objekt, das einen Bi-Level Schwarz/Weiß-Effekt repräsentiert.
type: docs
url: /de/com.aspose.slides/ibileveleffectivedata/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBiLevelEffectiveData extends IEffectEffectiveData
```

Unveränderliches Objekt, das einen Bi-Level- (schwarz/weiß)-Effekt darstellt. Eingabefarben, deren Luminanz kleiner als der angegebene Schwellenwert ist, werden zu Schwarz geändert. Eingabefarben, deren Luminanz größer oder gleich dem angegebenen Wert ist, werden zu Weiß gesetzt. Die Alpha-Effektwerte bleiben von diesem Effekt unberührt.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getThreshold()](#getThreshold--) | Gibt den Schwellenwert zurück. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

Gibt den Schwellenwert zurück. Nur lesend float.

**Rückgabewert:**
float