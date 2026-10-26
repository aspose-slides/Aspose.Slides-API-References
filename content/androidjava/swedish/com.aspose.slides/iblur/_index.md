---
title: IBlur
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en oskärpeeffekt som tillämpas på hela formen inklusive dess fyllning.
type: docs
url: /sv/com.aspose.slides/iblur/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

Representerar en oskärpeffekt som appliceras på hela formen, inklusive dess fyllning. Alla färgkanaler, inklusive alfa, påverkas.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRadius()](#getRadius--) | Returnerar eller anger oskärpe radie. |
| [setRadius(double value)](#setRadius-double-) | Returnerar eller anger oskärpe radie. |
| [getGrow()](#getGrow--) | Bestämmer om gränserna för objektet ska växa som ett resultat av oskärpan. |
| [setGrow(boolean value)](#setGrow-boolean-) | Bestämmer om gränserna för objektet ska växa som ett resultat av oskärpan. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Returnerar eller anger oskärpe radie. Läs/skriv double.

**Returnerar:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

Returnerar eller anger oskärpe radie. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

Bestämmer om gränserna för objektet ska växa som ett resultat av oskärpan. True indikerar att gränserna växer medan false betyder att de inte gör det. Läs/skriv boolean.

**Returnerar:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```

Bestämmer om gränserna för objektet ska växa som ett resultat av oskärpan. True indikerar att gränserna växer medan false betyder att de inte gör det. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |