---
title: IBlur
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta un effetto di sfocatura applicato all'intera forma, inclusa la sua riempitura.
type: docs
url: /it/com.aspose.slides/iblur/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

Rappresenta un effetto di sfocatura applicato all'intera forma, inclusa la sua riempitura. Tutti i canali colore, inclusa l'alpha, sono influenzati.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRadius()](#getRadius--) | Restituisce o imposta il raggio di sfocatura. |
| [setRadius(double value)](#setRadius-double-) | Restituisce o imposta il raggio di sfocatura. |
| [getGrow()](#getGrow--) | Determina se i confini dell'oggetto devono essere aumentati a seguito della sfocatura. |
| [setGrow(boolean value)](#setGrow-boolean-) | Determina se i confini dell'oggetto devono essere aumentati a seguito della sfocatura. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Restituisce o imposta il raggio di sfocatura. Lettura/Scrittura double.

**Restituisce:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

Restituisce o imposta il raggio di sfocatura. Lettura/Scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

Determina se i confini dell'oggetto devono essere aumentati a seguito della sfocatura. True indica che i confini sono aumentati mentre false indica che non lo sono. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```

Determina se i confini dell'oggetto devono essere aumentati a seguito della sfocatura. True indica che i confini sono aumentati mentre false indica che non lo sono. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |