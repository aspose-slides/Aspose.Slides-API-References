---
title: Blur
second_title: Riferimento API Aspose.Slides per Java
description: Rappresenta un effetto Blur applicato all'intera forma, includendo il suo riempimento.
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

Rappresenta un effetto Blur applicato all'intera forma, includendo il suo riempimento. Tutti i canali di colore, incluso l'alpha, sono interessati.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRadius()](#getRadius--) | Restituisce o imposta il raggio del blur. |
| [setRadius(double value)](#setRadius-double-) | Restituisce o imposta il raggio del blur. |
| [getGrow()](#getGrow--) | Determina se i limiti dell'oggetto devono essere ampliati a causa del blur. |
| [setGrow(boolean value)](#setGrow-boolean-) | Determina se i limiti dell'oggetto devono essere ampliati a causa del blur. |
| [getEffective()](#getEffective--) | Ottiene i dati dell'effetto Blur effettivo con l'ereditarietà applicata. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se il [Blur](../../com.aspose.slides/blur) specificato è uguale al corrente [Blur](../../com.aspose.slides/blur). |
| [hashCode()](#hashCode--) | Funziona come funzione hash per un tipo particolare. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

Restituisce o imposta il raggio del blur. Lettura/scrittura double.

**Restituisce:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Restituisce o imposta il raggio del blur. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### getGrow() {#getGrow--}
```
public final boolean getGrow()
```

Determina se i limiti dell'oggetto devono essere ampliati a causa del blur. True indica che i limiti sono ampliati mentre false indica che non lo sono. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```

Determina se i limiti dell'oggetto devono essere ampliati a causa del blur. True indica che i limiti sono ampliati mentre false indica che non lo sono. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```

Ottiene i dati dell'effetto Blur effettivo con l'ereditarietà applicata.

**Restituisce:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - Un [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).
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