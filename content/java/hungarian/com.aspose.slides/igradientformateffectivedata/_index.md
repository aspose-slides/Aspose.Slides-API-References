---
title: IGradientFormatEffectiveData
second_title: Aspose.Slides for Java API referenciája
description: Változtathatatlan objektum, amely hatékony színátmenetes kitöltési tulajdonságokat tartalmaz.
type: docs
url: /hu/com.aspose.slides/igradientformateffectivedata/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormatEffectiveData extends IFillParamSource
```

Imutable objektum, amely hatékony színátmenetes kitöltési tulajdonságokat tartalmaz.

--------------------

Ez az interfész a [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) és [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata) részeként használatos.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | Visszaadja a színátmenet forgatási módját. |
| [getGradientDirection()](#getGradientDirection--) | Visszaadja a színátmenet stílusát. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | Visszaadja a színátmenet szögét. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | Meghatározza, hogy a színátmenet skálázott-e. |
| [getGradientShape()](#getGradientShape--) | Visszaadja a színátmenet alakját. |
| [getGradientStops()](#getGradientStops--) | Visszaadja a színátmenet állomások gyűjteményét. |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```

Visszaadja a színátmenet forgatási módját. Csak olvasható [TileFlip](../../com.aspose.slides/tileflip).

**Visszatérési érték:**  
int
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```

Visszaadja a színátmenet stílusát. Csak olvasható [GradientDirection](../../com.aspose.slides/gradientdirection).

**Visszatérési érték:**  
int
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```

Visszaadja a színátmenet szögét. Csak olvasható float.

**Visszatérési érték:**  
float
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract boolean getLinearGradientScaled()
```

Meghatározza, hogy a színátmenet skálázott-e. Csak olvasható boolean.

**Visszatérési érték:**  
boolean
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```

Visszaadja a színátmenet alakját. Csak olvasható [GradientShape](../../com.aspose.slides/gradientshape).

**Visszatérési érték:**  
byte
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollectionEffectiveData getGradientStops()
```

Visszaadja a színátmenet állomások gyűjteményét. Csak olvasható [IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata).

**Visszatérési érték:**  
[IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)