---
title: IGradientFormat
second_title: Aspose.Slides for Android Java API-referencia
description: Egy színátmenet formátumot ábrázol.
type: docs
url: /hu/com.aspose.slides/igradientformat/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormat extends IFillParamSource
```

Egy színátmenet formátumot ábrázol.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | Visszaadja vagy beállítja egy színátmenet forgatási módját. |
| [setTileFlip(int value)](#setTileFlip-int-) | Visszaadja vagy beállítja egy színátmenet forgatási módját. |
| [getGradientDirection()](#getGradientDirection--) | Visszaadja vagy beállítja egy színátmenet stílusát. |
| [setGradientDirection(int value)](#setGradientDirection-int-) | Visszaadja vagy beállítja egy színátmenet stílusát. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | Visszaadja vagy beállítja egy színátmenet szögét. |
| [setLinearGradientAngle(float value)](#setLinearGradientAngle-float-) | Visszaadja vagy beállítja egy színátmenet szögét. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | Megállapítja, hogy a színátmenet skálázott-e. |
| [setLinearGradientScaled(byte value)](#setLinearGradientScaled-byte-) | Megállapítja, hogy a színátmenet skálázott-e. |
| [getGradientShape()](#getGradientShape--) | Visszaadja vagy beállítja egy színátmenet alakját. |
| [setGradientShape(byte value)](#setGradientShape-byte-) | Visszaadja vagy beállítja egy színátmenet alakját. |
| [getGradientStops()](#getGradientStops--) | Visszaadja a színátmenet állomások gyűjteményét. |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```

Visszaadja vagy beállítja egy színátmenet forgatási módját. Olvasás/írás [TileFlip](../../com.aspose.slides/tileflip).

**Visszatérési érték:**
int
### setTileFlip(int value) {#setTileFlip-int-}
```
public abstract void setTileFlip(int value)
```

Visszaadja vagy beállítja egy színátmenet forgatási módját. Olvasás/írás [TileFlip](../../com.aspose.slides/tileflip).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```

Visszaadja vagy beállítja egy színátmenet stílusát. Olvasás/írás [GradientDirection](../../com.aspose.slides/gradientdirection).

**Visszatérési érték:**
int
### setGradientDirection(int value) {#setGradientDirection-int-}
```
public abstract void setGradientDirection(int value)
```

Visszaadja vagy beállítja egy színátmenet stílusát. Olvasás/írás [GradientDirection](../../com.aspose.slides/gradientdirection).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```

Visszaadja vagy beállítja egy színátmenet szögét. Olvasás/írás float.

**Visszatérési érték:**
float
### setLinearGradientAngle(float value) {#setLinearGradientAngle-float-}
```
public abstract void setLinearGradientAngle(float value)
```

Visszaadja vagy beállítja egy színátmenet szögét. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract byte getLinearGradientScaled()
```

Megállapítja, hogy a színátmenet skálázott-e. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatérési érték:**
byte
### setLinearGradientScaled(byte value) {#setLinearGradientScaled-byte-}
```
public abstract void setLinearGradientScaled(byte value)
```

Megállapítja, hogy a színátmenet skálázott-e. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```

Visszaadja vagy beállítja egy színátmenet alakját. Olvasás/írás [GradientShape](../../com.aspose.slides/gradientshape).

**Visszatérési érték:**
byte
### setGradientShape(byte value) {#setGradientShape-byte-}
```
public abstract void setGradientShape(byte value)
```

Visszaadja vagy beállítja egy színátmenet alakját. Olvasás/írás [GradientShape](../../com.aspose.slides/gradientshape).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollection getGradientStops()
```

Visszaadja a színátmenet állomások gyűjteményét. Csak olvasható [IGradientStopCollection](../../com.aspose.slides/igradientstopcollection).

**Visszatérési érték:**
[IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)