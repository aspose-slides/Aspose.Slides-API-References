---
title: IGradientFormat
second_title: Aspose.Slides Java API referencia
description: Gradient formátumot képvisel.
type: docs
url: /hu/com.aspose.slides/igradientformat/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormat extends IFillParamSource
```

Egy gradient formátumot képvisel.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | Visszaadja vagy beállítja egy gradient forgatási módját. |
| [setTileFlip(int value)](#setTileFlip-int-) | Visszaadja vagy beállítja egy gradient forgatási módját. |
| [getGradientDirection()](#getGradientDirection--) | Visszaadja vagy beállítja egy gradient stílusát. |
| [setGradientDirection(int value)](#setGradientDirection-int-) | Visszaadja vagy beállítja egy gradient stílusát. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | Visszaadja vagy beállítja egy gradient szögét. |
| [setLinearGradientAngle(float value)](#setLinearGradientAngle-float-) | Visszaadja vagy beállítja egy gradient szögét. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | Meghatározza, hogy a gradient skálázott-e. |
| [setLinearGradientScaled(byte value)](#setLinearGradientScaled-byte-) | Meghatározza, hogy a gradient skálázott-e. |
| [getGradientShape()](#getGradientShape--) | Visszaadja vagy beállítja egy gradient alakját. |
| [setGradientShape(byte value)](#setGradientShape-byte-) | Visszaadja vagy beállítja egy gradient alakját. |
| [getGradientStops()](#getGradientStops--) | Visszaadja a gradient stop-ok gyűjteményét. |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```

Visszaadja vagy beállítja egy gradient forgatási módját. Olvasás/írás [TileFlip](../../com.aspose.slides/tileflip).

**Visszatérési érték:**
int
### setTileFlip(int value) {#setTileFlip-int-}
```
public abstract void setTileFlip(int value)
```

Visszaadja vagy beállítja egy gradient forgatási módját. Olvasás/írás [TileFlip](../../com.aspose.slides/tileflip).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```

Visszaadja vagy beállítja egy gradient stílusát. Olvasás/írás [GradientDirection](../../com.aspose.slides/gradientdirection).

**Visszatérési érték:**
int
### setGradientDirection(int value) {#setGradientDirection-int-}
```
public abstract void setGradientDirection(int value)
```

Visszaadja vagy beállítja egy gradient stílusát. Olvasás/írás [GradientDirection](../../com.aspose.slides/gradientdirection).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```

Visszaadja vagy beállítja egy gradient szögét. Olvasás/írás float.

**Visszatérési érték:**
float
### setLinearGradientAngle(float value) {#setLinearGradientAngle-float-}
```
public abstract void setLinearGradientAngle(float value)
```

Visszaadja vagy beállítja egy gradient szögét. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract byte getLinearGradientScaled()
```

Meghatározza, hogy a gradient skálázott-e. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatérési érték:**
byte
### setLinearGradientScaled(byte value) {#setLinearGradientScaled-byte-}
```
public abstract void setLinearGradientScaled(byte value)
```

Meghatározza, hogy a gradient skálázott-e. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```

Visszaadja vagy beállítja egy gradient alakját. Olvasás/írás [GradientShape](../../com.aspose.slides/gradientshape).

**Visszatérési érték:**
byte
### setGradientShape(byte value) {#setGradientShape-byte-}
```
public abstract void setGradientShape(byte value)
```

Visszaadja vagy beállítja egy gradient alakját. Olvasás/írás [GradientShape](../../com.aspose.slides/gradientshape).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollection getGradientStops()
```

Visszaadja a gradient stop-ok gyűjteményét. Csak olvasás [IGradientStopCollection](../../com.aspose.slides/igradientstopcollection).

**Visszatérési érték:**
[IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)