---
title: IDuotoneEffectiveData
second_title: Aspose.Slides für Android via Java API Referenz
description: Unveränderliches Objekt, das einen Duotone-Effekt darstellt.
type: docs
url: /de/com.aspose.slides/iduotoneeffectivedata/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IDuotoneEffectiveData extends IEffectEffectiveData
```

Unveränderliches Objekt, das einen Duotone-Effekt darstellt. Für jedes Pixel kombiniert es clr1 und clr2 durch lineare Interpolation, um die neue Farbe für dieses Pixel zu bestimmen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getColor1()](#getColor1--) | Gibt das Zielfarbformat für dunkle Pixel zurück. |
| [getColor2()](#getColor2--) | Gibt das Zielfarbformat für helle Pixel zurück. |
### getColor1() {#getColor1--}
```
public abstract Integer getColor1()
```

Gibt das Zielfarbformat für dunkle Pixel zurück. Nur lesbar java.lang.Integer.

**Rückgabe:**
java.lang.Integer
### getColor2() {#getColor2--}
```
public abstract Integer getColor2()
```

Gibt das Zielfarbformat für helle Pixel zurück. Nur lesbar java.lang.Integer.

**Rückgabe:**
java.lang.Integer