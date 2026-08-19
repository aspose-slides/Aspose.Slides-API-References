---
title: IAlphaBiLevel
second_title: Aspose.Slides för Java API-referens
description: Representerar en Alpha Bi-Level-effekt.
type: docs
url: /sv/com.aspose.slides/ialphabilevel/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

Representerar en Alpha Bi-Level-effekt. Alpha (opacitet)-värden mindre än tröskeln ändras till 0 (helt transparent) och alpha-värden som är större än eller lika med tröskeln ändras till 100% (helt opak).

--------------------

Använd ImageTransformOperationFactory för att skapa instanser i COM.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getThreshold()](#getThreshold--) | Returnerar effekttröskel. |
| [setThreshold(float value)](#setThreshold-float-) | Returnerar effekttröskel. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


Returnerar effekttröskel. Läs/skriv float.

**Returnerar:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```


Returnerar effekttröskel. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |