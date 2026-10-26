---
title: IGradientFormatEffectiveData
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Oggetto immutabile che contiene le proprietà effettive di riempimento a gradiente.
type: docs
url: /it/com.aspose.slides/igradientformateffectivedata/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormatEffectiveData extends IFillParamSource
```

Oggetto immutabile che contiene le proprietà effettive di riempimento a gradiente.

--------------------

Questa interfaccia è usata come parte di [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) e [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | Restituisce la modalità di capovolgimento per un gradiente. |
| [getGradientDirection()](#getGradientDirection--) | Restituisce lo stile di un gradiente. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | Restituisce l'angolo di un gradiente. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | Determina se un gradiente è scalato. |
| [getGradientShape()](#getGradientShape--) | Restituisce la forma di un gradiente. |
| [getGradientStops()](#getGradientStops--) | Restituisce la collezione di fermate di gradiente. |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```


Restituisce la modalità di capovolgimento per un gradiente. Solo lettura [TileFlip](../../com.aspose.slides/tileflip).

**Restituisce:**
int
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```


Restituisce lo stile di un gradiente. Solo lettura [GradientDirection](../../com.aspose.slides/gradientdirection).

**Restituisce:**
int
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```


Restituisce l'angolo di un gradiente. Solo lettura float.

**Restituisce:**
float
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract boolean getLinearGradientScaled()
```


Determina se un gradiente è scalato. Solo lettura boolean.

**Restituisce:**
boolean
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```


Restituisce la forma di un gradiente. Solo lettura [GradientShape](../../com.aspose.slides/gradientshape).

**Restituisce:**
byte
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollectionEffectiveData getGradientStops()
```


Restituisce la collezione di fermate di gradiente. Solo lettura [IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata).

**Restituisce:**
[IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)