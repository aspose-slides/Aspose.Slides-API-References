---
title: Blur
second_title: Riferimento API Java per Aspose.Slides per Android
description: Rappresenta un effetto di sfocatura applicato all'intera forma, compreso il riempimento.
type: docs
url: /it/com.aspose.slides/blur/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tutte le interfacce implementate:**
[com.aspose.slides.IBlur](../../com.aspose.slides/iblur), com.aspose.slides.IVisualEffect
```
public final class Blur extends ImageTransformOperation implements IBlur, IVisualEffect
```

Rappresenta un effetto di sfocatura applicato all'intera forma, compreso il suo riempimento. Tutti i canali colore, compreso l'alpha, sono influenzati.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRadius()](#getRadius--) | Restituisce o imposta il raggio della sfocatura. |
| [setRadius(double value)](#setRadius-double-) | Restituisce o imposta il raggio della sfocatura. |
| [getGrow()](#getGrow--) | Determina se i limiti dell'oggetto devono essere ampliati a causa della sfocatura. |
| [setGrow(boolean value)](#setGrow-boolean-) | Determina se i limiti dell'oggetto devono essere ampliati a causa della sfocatura. |
| [getEffective()](#getEffective--) | Ottiene i dati effettivi dell'effetto di sfocatura con l'ereditarietà applicata. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se il [Blur](../../com.aspose.slides/blur) specificato è uguale al corrente [Blur](../../com.aspose.slides/blur). |
| [hashCode()](#hashCode--) | Funziona come funzione hash per un tipo particolare. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Restituisce o imposta il raggio della sfocatura. Lettura/Scrittura double.

**Restituisce:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Restituisce o imposta il raggio della sfocatura. Lettura/Scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### getGrow() {#getGrow--}
```
public final boolean getGrow()
```


Determina se i limiti dell'oggetto devono essere ampliati a causa della sfocatura. True indica che i limiti sono ampliati mentre false indica che non lo sono. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```


Determina se i limiti dell'oggetto devono essere ampliati a causa della sfocatura. True indica che i limiti sono ampliati mentre false indica che non lo sono. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```


Ottiene i dati effettivi dell'effetto di sfocatura con l'ereditarietà applicata.

**Restituisce:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - A [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se il [Blur](../../com.aspose.slides/blur) specificato è uguale al corrente [Blur](../../com.aspose.slides/blur).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Il [Blur](../../com.aspose.slides/blur) da confrontare. |

**Restituisce:**
boolean - true se gli oggetti sono uguali; altrimenti, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Funziona come funzione hash per un tipo particolare.

**Restituisce:**
int - Un codice hash per l'oggetto corrente.