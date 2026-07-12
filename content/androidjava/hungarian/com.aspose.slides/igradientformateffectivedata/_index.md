---
title: IGradientFormatEffectiveData
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Megváltoztathatatlan objektum, amely hatékony színátmenet kitöltési tulajdonságokat tartalmaz.
type: docs
url: /hu/com.aspose.slides/igradientformateffectivedata/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormatEffectiveData extends IFillParamSource
```

Megváltoztathatatlan objektum, amely hatékony színátmenet kitöltési tulajdonságokat tartalmaz.

--------------------

Ez az interfész a [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) és [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata) részeként használatos.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | Visszaadja a színátmenet forgatási módját. |
| [getGradientDirection()](#getGradientDirection--) | Visszaadja a színátmenet stílusát. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | Visszaadja a színátmenet szögét. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | Megállapítja, hogy a színátmenet méretezett-e. |
| [getGradientShape()](#getGradientShape--) | Visszaadja a színátmenet alakját. |
| [getGradientStops()](#getGradientStops--) | Visszaadja a színátmenet állomásainak gyűjteményét. |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```

Visszaadja a színátmenet forgatási módját. Csak olvasható [TileFlip](../../com.aspose.slides/tileflip).

**Visszatér:**
int
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```

Visszaadja a színátmenet stílusát. Csak olvasható [GradientDirection](../../com.aspose.slides/gradientdirection).

**Visszatér:**
int
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```

Visszaadja a színátmenet szögét. Csak olvasható float.

**Visszatér:**
float
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract boolean getLinearGradientScaled()
```

Megállapítja, hogy a színátmenet méretezett-e. Csak olvasható boolean.

**Visszatér:**
boolean
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```

Visszaadja a színátmenet alakját. Csak olvasható [GradientShape](../../com.aspose.slides/gradientshape).

**Visszatér:**
byte
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollectionEffectiveData getGradientStops()
```

Visszaadja a színátmenet állomásainak gyűjteményét. Csak olvasható [IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata).

**Visszatér:**
[IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)