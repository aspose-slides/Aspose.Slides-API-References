---
title: AlphaBiLevel
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta un effetto Alpha Bi-Level.
type: docs
url: /it/com.aspose.slides/alphabilevel/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tutte le interfacce implementate:**
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

Rappresenta un effetto Alpha Bi-Level. I valori Alpha (Opacità) inferiori alla soglia vengono modificati a 0 (completamente trasparente) e i valori alpha maggiori o uguali alla soglia vengono modificati al 100 % (completamente opaco).
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getThreshold()](#getThreshold--) | Restituisce la soglia dell'effetto. |
| [setThreshold(float value)](#setThreshold-float-) | Restituisce la soglia dell'effetto. |
| [getEffective()](#getEffective--) | Ottiene i dati dell'effetto Alpha Bi-Level effettivo con l'ereditarietà applicata. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se il [AlphaBiLevel](../../com.aspose.slides/alphabilevel) specificato è uguale all'[AlphaBiLevel](../../com.aspose.slides/alphabilevel) corrente. |
| [hashCode()](#hashCode--) | Funge da funzione hash per un tipo particolare. |
### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```


Restituisce la soglia dell'effetto. Lettura/scrittura float.

**Restituisce:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```


Restituisce la soglia dell'effetto. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```


Ottiene i dati dell'effetto Alpha Bi-Level effettivo con l'ereditarietà applicata.

**Restituisce:**
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - Un [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se il [AlphaBiLevel](../../com.aspose.slides/alphabilevel) specificato è uguale all'[AlphaBiLevel](../../com.aspose.slides/alphabilevel) corrente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Il [AlphaBiLevel](../../com.aspose.slides/alphabilevel) da confrontare. |

**Restituisce:**
boolean - true se gli oggetti sono uguali; altrimenti, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Funge da funzione hash per un tipo particolare.

**Restituisce:**
int - Un codice hash per l'oggetto corrente.