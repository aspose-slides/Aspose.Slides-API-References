---
title: IBlur
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta un effetto di sfocatura applicato all'intera forma, compresa la sua riempitura.
type: docs
url: /it/com.aspose.slides/iblur/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

Rappresenta un effetto di sfocatura applicato all'intera forma, compresa la sua riempitura. Tutti i canali di colore, compreso l'alpha, sono influenzati.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRadius()](#getRadius--) | Restituisce o imposta il raggio della sfocatura. |
| [setRadius(double value)](#setRadius-double-) | Restituisce o imposta il raggio della sfocatura. |
| [getGrow()](#getGrow--) | Determina se i limiti dell'oggetto devono essere ampliati a causa della sfocatura. |
| [setGrow(boolean value)](#setGrow-boolean-) | Determina se i limiti dell'oggetto devono essere ampliati a causa della sfocatura. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Restituisce o imposta il raggio della sfocatura. Lettura/scrittura double.

**Restituisce:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```


Restituisce o imposta il raggio della sfocatura. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```


Determina se i limiti dell'oggetto devono essere ampliati a causa della sfocatura. True indica che i limiti sono ampliati, mentre false indica che non lo sono. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```


Determina se i limiti dell'oggetto devono essere ampliati a causa della sfocatura. True indica che i limiti sono ampliati, mentre false indica che non lo sono. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |