---
title: IDuotoneEffectiveData
second_title: Aspose.Slides für Java API-Referenz
description: Unveränderliches Objekt, das einen Duoton-Effekt darstellt.
type: docs
url: /de/com.aspose.slides/iduotoneeffectivedata/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IDuotoneEffectiveData extends IEffectEffectiveData
```

Unveränderliches Objekt, das einen Duoton-Effekt darstellt. Für jedes Pixel kombiniert es clr1 und clr2 durch lineare Interpolation, um die neue Farbe für dieses Pixel zu bestimmen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getColor1()](#getColor1--) | Gibt das Zielfarbformat für dunkle Pixel zurück. |
| [getColor2()](#getColor2--) | Gibt das Zielfarbformat für helle Pixel zurück. |
### getColor1() {#getColor1--}
```
public abstract Color getColor1()
```


Gibt das Zielfarbformat für dunkle Pixel zurück. Schreibgeschützt java.awt.Color.

**Rückgabewert:**
java.awt.Color
### getColor2() {#getColor2--}
```
public abstract Color getColor2()
```


Gibt das Zielfarbformat für helle Pixel zurück. Schreibgeschützt java.awt.Color.

**Rückgabewert:**
java.awt.Color