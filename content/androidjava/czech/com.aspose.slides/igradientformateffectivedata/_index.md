---
title: IGradientFormatEffectiveData
second_title: Aspose.Slides pro Android prostřednictvím Java API
description: Neměnný objekt, který obsahuje účinné vlastnosti výplně gradientu.
type: docs
url: /cs/com.aspose.slides/igradientformateffectivedata/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormatEffectiveData extends IFillParamSource
```

Neměnný objekt, který obsahuje účinné vlastnosti výplně gradientu.

--------------------

Toto rozhraní se používá jako součást [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) a [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Metody

| Metoda | Popis |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | Returns the flipping mode for a gradient. |
| [getGradientDirection()](#getGradientDirection--) | Returns the style of a gradient. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | Returns the angle of a gradient. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | Determines whether a gradient is scaled. |
| [getGradientShape()](#getGradientShape--) | Returns the shape of a gradient. |
| [getGradientStops()](#getGradientStops--) | Returns the collection of gradient stops. |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```

Vrací režim převrácení gradientu. Pouze pro čtení [TileFlip](../../com.aspose.slides/tileflip).

**Vrací:**
int
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```

Vrací styl gradientu. Pouze pro čtení [GradientDirection](../../com.aspose.slides/gradientdirection).

**Vrací:**
int
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```

Vrací úhel gradientu. Pouze pro čtení float.

**Vrací:**
float
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract boolean getLinearGradientScaled()
```

Určuje, zda je gradient škálován. Pouze pro čtení boolean.

**Vrací:**
boolean
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```

Vrací tvar gradientu. Pouze pro čtení [GradientShape](../../com.aspose.slides/gradientshape).

**Vrací:**
byte
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollectionEffectiveData getGradientStops()
```

Vrací kolekci zastávek gradientu. Pouze pro čtení [IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata).

**Vrací:**
[IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)