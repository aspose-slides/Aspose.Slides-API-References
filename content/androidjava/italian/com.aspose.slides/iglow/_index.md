---
title: IGlow
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta un effetto Glow in cui un contorno sfocato di colore viene aggiunto al di fuori dei bordi dell'oggetto.
type: docs
url: /it/com.aspose.slides/iglow/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

Rappresenta un effetto Glow, in cui un contorno sfocato di colore viene aggiunto al di fuori dei bordi dell'oggetto.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRadius()](#getRadius--) | Raggio. |
| [setRadius(double value)](#setRadius-double-) | Raggio. |
| [getColor()](#getColor--) | Formato colore. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Raggio. Lettura/scrittura double.

**Restituisce:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```


Raggio. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


Formato colore. Sola lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)