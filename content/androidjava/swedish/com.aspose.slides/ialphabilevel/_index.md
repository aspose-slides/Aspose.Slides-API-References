---
title: IAlphaBiLevel
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en Alpha Bi-Level-effekt.
type: docs
url: /sv/com.aspose.slides/ialphabilevel/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

Representerar en Alpha Bi-Level-effekt. Alpha (Opacitet) värden som är mindre än tröskeln ändras till 0 (helt transparent) och alfa-värden som är större än eller lika med tröskeln ändras till 100 % (helt ogenomskinligt).

--------------------

Använd ImageTransformOperationFactory för att skapa instanser i COM.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getThreshold()](#getThreshold--) | Returnerar effektens tröskel. |
| [setThreshold(float value)](#setThreshold-float-) | Returnerar effektens tröskel. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

Returnerar effektens tröskel. Läs/skriv float.

**Returnerar:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```

Returnerar effektens tröskel. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |