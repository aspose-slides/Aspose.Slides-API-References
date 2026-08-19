---
title: InnerShadow
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta un effetto Inner Shadow.
type: docs
url: /it/com.aspose.slides/innershadow/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IInnerShadow](../../com.aspose.slides/iinnershadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class InnerShadow implements IInnerShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Rappresenta un effetto Inner Shadow.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Raggio di sfocatura. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Raggio di sfocatura. |
| [getDirection()](#getDirection--) | Direzione dell'ombra. |
| [setDirection(float value)](#setDirection-float-) | Direzione dell'ombra. |
| [getDistance()](#getDistance--) | Distanza dell'ombra. |
| [setDistance(double value)](#setDistance-double-) | Distanza dell'ombra. |
| [getShadowColor()](#getShadowColor--) | Colore dell'ombra. |
| [getEffective()](#getEffective--) | Ottiene i dati dell'effetto Inner Shadow effettivo con l'ereditarietà applicata. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se il [InnerShadow](../../com.aspose.slides/innershadow) specificato è uguale al [InnerShadow](../../com.aspose.slides/innershadow) corrente. |
| [hashCode()](#hashCode--) | Funge da funzione hash per un tipo particolare. |
### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```


Raggio di sfocatura. Lettura/scrittura double.

**Restituisce:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```


Raggio di sfocatura. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public final float getDirection()
```


Direzione dell'ombra. Lettura/scrittura float.

**Restituisce:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```


Direzione dell'ombra. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public final double getDistance()
```


Distanza dell'ombra. Lettura/scrittura double.

**Restituisce:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```


Distanza dell'ombra. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```


Colore dell'ombra. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IInnerShadowEffectiveData getEffective()
```


Ottiene i dati dell'effetto Inner Shadow effettivo con l'ereditarietà applicata.

**Restituisce:**
[IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata) - Un [IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Restituisce l'oggetto Parent_Immediate. Solo lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Versione. Solo lettura long.

**Restituisce:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Restituisce il genitore IPresentationComponent. Solo lettura [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Restituisce:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se il [InnerShadow](../../com.aspose.slides/innershadow) specificato è uguale al [InnerShadow](../../com.aspose.slides/innershadow) corrente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Il [InnerShadow](../../com.aspose.slides/innershadow) da confrontare. |

**Restituisce:**
boolean - true se gli oggetti sono uguali; altrimenti, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Funge da funzione hash per un tipo particolare.

**Restituisce:**
int - Un codice hash per l'oggetto corrente.