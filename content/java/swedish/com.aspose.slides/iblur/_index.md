---
title: IBlur
second_title: Aspose.Slides för Java API-referens
description: Representerar en oskärpeeffekt som tillämpas på hela formen inklusive dess fyllning.
type: docs
url: /sv/com.aspose.slides/iblur/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

Representerar en oskärpeeffekt som tillämpas på hela formen, inklusive dess fyllning. Alla färgkanaler, inklusive alfa, påverkas.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRadius()](#getRadius--) | Returnerar eller ställer in oskärperadie. |
| [setRadius(double value)](#setRadius-double-) | Returnerar eller ställer in oskärperadie. |
| [getGrow()](#getGrow--) | Bestämmer om objektets gränser ska utökas som en följd av oskärpningen. |
| [setGrow(boolean value)](#setGrow-boolean-) | Bestämmer om objektets gränser ska utökas som en följd av oskärpningen. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Returnerar eller ställer in oskärperadie. Läs/skriv double.

**Returnerar:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

Returnerar eller ställer in oskärperadie. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

Bestämmer om objektets gränser ska utökas som en följd av oskärpningen. True indikerar att gränserna växer medan false indikerar att de inte gör det. Läs/skriv boolean.

**Returnerar:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```

Bestämmer om objektets gränser ska utökas som en följd av oskärpningen. True indikerar att gränserna växer medan false indikerar att de inte gör det. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |